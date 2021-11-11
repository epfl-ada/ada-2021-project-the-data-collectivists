# ADA - Milestone P2
Group: **The Data Collectivists**

<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
  * [Introduction](#Introduction)
  * [Data](#Data)
* [Methods](#methods)
  * [Data Extraction](#data-extraction)
  * [Preprocessing](#preprocessing)
  * [Processing and Graphics](#processing-and-graphics)
* [Built With](#built-with)

<!-- ABOUT THE PROJECT -->
## About the Project

### Introduction

The peace and prosperity that we encountered in developped countries of the North in the last century has led many nations in a path of constant technological progress and economic growth. This prosperity however might be threatened by newfound global issues that not only jeopardize the economy, but also the future of humanity. The recent COVID-19 pandemic has shown once more how the current socio-economic system ubiquitous in most occidental democracies has potentially fatal flaws that we need to address before it is crushed under its own weight.

While most people agree about the uncertainty of the next hundred years, we still have yet to agree on a solution. Some of which are more oriented towards a progressive society, while others prefer a more conservative approach. While multiple point of view rely on economic and environmental claims to base their theories on, some others are based on hate and fear of the difference, hate and fear of the change we might need to forge a more inclusive society. In order to better tackle the issues we face, we need to understand how some ideologies are gaining more traction inside the public debate, to observe how they might shape the minds of citizens.

We are interested today about the rise of far-right extremism speech **between XXXX and XXXX**, observed through a dataset of quotes from the press, highlighting the evolution of opinions and ideas that shape the past, present, and the future of our society.

### Data

[Quotebank](https://zenodo.org/record/4277311#.YYqEUGXPxb8), an open corpus of 178 million quotations attributed to the speakers who uttered them, extracted from 162 million English news articles published between 2008 and 2020.
[TO_DO]


<!-- METHODS -->
## Methods

Our pipeline is designed in 3 majors steps. We first extract the **178 millions** quotations-speakers pairs from the [Quotebank](https://zenodo.org/record/4277311#.YYqEUGXPxb8) dataset. 
Then, preprocessing the extracted data is a must if we consider performing a correct and non-biased (or less possible at least) analysis. Finally, it make use of **Natural Language 
Processing** (NLP) models such as to tackle our problematic.

### Data Extraction

[TO DO]

### Preprocessing

* Remove news outlets relaying less than 100 quotes that do not contribute to reflecting global trends.
* Remove quotes with low numOccurences
* Remove quotes with no QIDs
* Remove quotes with several QIDs
* Filter quotations that mentions keywords that we choose to tackle 


### Processing and Graphics
[TO DO]

<!-- BUILT WITH -->
## Built With

* [Python 3.7](https://www.python.org)
* [Quotebank](https://zenodo.org/record/4277311#.YYqEUGXPxb8)
* [Pandas](https://pandas.pydata.org)
* [Seaborn](https://seaborn.pydata.org)
