# ADA - Milestone P2
Group: **The Data Collectivists**

<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
  * [Introduction](#Introduction)
  * [Data](#Data)
* [Methods](#methods)
  * [Data Extraction and Exploration](#data-extraction-and-exploration)
  * [Preprocessing](#preprocessing)
  * [Processing and Graphics](#processing-and-graphics)
* [Built With](#built-with)
* [Bibliography](#bibliography)

<!-- ABOUT THE PROJECT -->
## About the Project

### Introduction

The peace and prosperity that we encountered in developped countries of the North in the last century has led many nations in a path of constant technological progress and economic growth. This prosperity however might be threatened by newfound global issues that not only jeopardize the economy, but also the future of humanity. The recent COVID-19 pandemic has shown once more how the current socio-economic system ubiquitous in most occidental democracies has potentially fatal flaws that we need to address before it is crushed under its own weight.

While most people agree about the uncertainty of the next hundred years, we still have yet to agree on a solution. Some of which are more oriented towards a progressive society, while others prefer a more conservative approach. While multiple point of view rely on economic and environmental claims to base their theories on, some others are based on hate and fear of the difference, hate and fear of the change we might need to forge a more inclusive society. In order to better tackle the issues we face, we need to understand how some ideologies are gaining more traction inside the public debate, to observe how they might shape the minds of citizens.

We are interested today about the rise of far-right extremism speech **between XXXX and XXXX**, observed through a dataset of quotes from the press, highlighting the evolution of opinions and ideas that shape the past, present, and the future of our society.

### Research questions

Is far-right extremism speech on the rise since 2016 ? How accurately can we identify a trend with the Quotebank dataset, when put in perspective with right-wing extremist terrorist attacks ? Can we highlight some news outlets that spread hate speech more than other, and if so, is it consistent over the years ? Is it also consistent with their political opinion ? 

### Data

[Quotebank](https://zenodo.org/record/4277311#.YYqEUGXPxb8), an open corpus of 178 million quotations attributed to the speakers who uttered them, extracted from 162 million English news articles published between 2008 and 2020. To narrow down our study, we will focus on the time period between 2016 and 2020, an interval where major political events shaped the way far-right extremism is spreading in the media, while limiting the size of the dataset. 
In order to build our timeline, we plan on using the Washington Post study of the CSIS database **[[1]](#bibliography)** that lists major right-wing extremist incidents that happened between 1994 and 2021. This will allow us to study the correlation between the rise of these attacks and the normalization of hate speech in the media.
Moreover, we will also need to define what is and how to discriminate hate speech. This 


<!-- METHODS -->
## Methods

Our pipeline is designed in 3 majors steps. We first [extract](#data-extraction-and-exploration) the corresponding datasets unprocessed for data exploration. A preliminary analysis of the data has led us to the [preprocessing](#preprocessing) rules we established to only keep relevent data for our study.
The actual study is divided in multiple approaches. The first of which is a quantitative study of the number of occurences of certain expressions to better build a timeline, putting it in perspective with major political events that shaped the far-right speech spread (Donald Trump presidency, the Charlottesville terrorist attack...).
For our second approach, we are interested in looking at a more qualitative approach, where we actually look at the content of each quote. Using Natural Language Processing (NLP) techniques, some related papers built datasets and models able to predict the hatefulness of a sentence **[[2]](#bibliography)**. This would allow us to get a set of keywords and a way to include context for the determination of the "hatefulness" of a quote. **ESSAYER DE FAIRE CA POUR LE RENDU SUR UN PETIT SAMPLE** 

### Data Extraction and Exploration

With an initial analysis, we identified several interesting values for the dataset, orienting our choices for the preprocessing step:

* Number of quotes with no QID:
* Number of quotes with multiple QIDs:

![graph](img/graph.jpg
_Figure 1: Distribution of the number of occurences per quotes in the 2016~2020 Quotebank dataset_

-> on voit que les quotes avec 1 occurences servent a rien: threshold = XXXXXX

![graph2](img/graph2.jpg
_Figure 2: Distribution of the number of quotes per news outlets in the 2016~2020 Quotebank dataset_

-> les news articles avec peu de trucs on les tej

### Preprocessing

To clean the dataset, we 

* Remove news outlets relaying less than XXXXX quotes that do not contribute to reflecting global trends.
* Remove quotes with low numOccurences (les than XXXX)
* Remove quotes with no QID
* Remove quotes with multiple QIDs
* Filter quotations that mentions keywords that we choose to tackle 


### Processing and Graphics

on fait quoi ici ?

## Built With

* [Python 3.7](https://www.python.org)
* [Quotebank](https://zenodo.org/record/4277311#.YYqEUGXPxb8)
* [Pandas](https://pandas.pydata.org)
* [Seaborn](https://seaborn.pydata.org)

## Bibliography

1. [Washington Post article](https://www.washingtonpost.com/investigations/interactive/2021/domestic-terrorism-data/) [Github repository](https://github.com/wpinvestigative/csis_domestic_terrorism)
2. Qian, J., Bethke, A., Liu, Y., Belding, E., & Wang, W. Y. (2019). A benchmark dataset for learning to intervene in online hate speech.
