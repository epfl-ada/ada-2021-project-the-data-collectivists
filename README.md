# ADA - Milestone P2
Group: **The Data Collectivists**

<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
  * [Data](#Data)
  * [General Idea](#general-idea)
* [Methods](#methods)
  * [Data Extraction](#data-extraction)
  * [Preprocessing](#preprocessing)
  * [Processing and Graphics](#processing-and-graphics)
* [Built With](#built-with)

<!-- ABOUT THE PROJECT -->
## About the Project

[TO_DO]

### Data

[Quotebank](https://zenodo.org/record/4277311#.YYqEUGXPxb8), an open corpus of 178 million quotations attributed to the speakers who uttered them, extracted from 162 million English news articles published between 2008 and 2020.
[TO_DO]

### General Idea

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
* Filter quotations that mentions keywords that we choose to tackle 


### Processing and Graphics
[TO DO]

<!-- BUILT WITH -->
## Built With

* [Python 3.7](https://www.python.org)
* [Quotebank](https://zenodo.org/record/4277311#.YYqEUGXPxb8)
* [Pandas](https://pandas.pydata.org)
* [Seaborn](https://seaborn.pydata.org)
