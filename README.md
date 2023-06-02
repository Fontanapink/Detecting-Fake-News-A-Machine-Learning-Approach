# Detecting-Fake-News-A-Machine-Learning-Approach
## Table of Contents
- [Detecting-Fake-News-A-Machine-Learning-Approach](#detecting-fake-news-a-machine-learning-approach)
  - [Table of Contents](#table-of-contents)
  - [Project Description](#project-description)
  - [Team Members](#team-members)
  - [Folder descriptions:](#folder-descriptions)
  - [Documents](#documents)
  - [Erdos deadlines:](#erdos-deadlines)
      - [Data gathering and defining stakeholders + KPIs - May 19, 2023](#data-gathering-and-defining-stakeholders--kpis---may-19-2023)
      - [Data cleaning + preprocessing - May 19, 2023](#data-cleaning--preprocessing---may-19-2023)
      - [Exploratory data analysis + visualizations \[Checkpoint\] - May 26, 2023](#exploratory-data-analysis--visualizations-checkpoint---may-26-2023)
      - [Written proposal of modeling approach \[Checkpoint\] - May 26, 2023](#written-proposal-of-modeling-approach-checkpoint---may-26-2023)
      - [Machine learning models or equivalent \[Checkpoint\] - Jun 1, 2023](#machine-learning-models-or-equivalent-checkpoint---jun-1-2023)
      - [Final project due - Jun 3, 2023](#final-project-due---jun-3-2023)

## Project Description
The spread of misinformation, or "fake news," is a significant issue in today's digital society. This project aims to tackle this challenge by developing a machine-learning model capable of analyzing news articles and classifying them as "real" or "fake."

In this project, we are using known classifier models to predict if news articles are FAKE or REAL. However, this has been done before. Therefore, to see if we can increase the accuracy of these models, we are going to create synthetic features for the characteristics of these news that we think are important. We will then use these features to train our models and see if we can increase the accuracy of our predictions.

Some of the synthetic features we are going to create are:
- The number of grammatical and spelling errors in the article
- The number of times the article uses the word "I" or "me"
- The use of emmotional words in the article
- The number of words used with capital letters
- The use of numbers in the article
- The use of long words (more than 10, 15 characters) in the article
- Topic modeling of the article using BERT

## Team Members
- Pedro Fontanarrosa
- Daniel Gao

-----------

## Folder descriptions:
- EDA: Contains the exploratory data analysis notebooks
- Datasets: Contains the datasets used in the project
- Models: Contains the machine learning models used in the project
- Meeting Notes: Contains the meeting notes from the weekly meetings
- Housekeeping files (README, .gitignore, .vscode, etc.)


## Documents

[Ideas/concerns/opinions for project](https://docs.google.com/document/d/1DNczb1nMEhkRcQA6TphjL8hI46tRyMtm9uL3yfk-20M/edit?usp=sharing)

[Stakeholders, Deliverables, and Dataset document](https://docs.google.com/document/d/11QYoArg_Tspz9DMUaUZW-JQ5L7bWfVSuiV1cnxe9IOw/edit?usp=sharing)

[Datasets](https://docs.google.com/document/d/1ZAJRoiReq_z9ilW6BCkTsyaTOXu-gpDJs10uEqnFxuU/edit?usp=sharing)

[Ideas for Final Presentation / Future Work](https://docs.google.com/document/d/1T8lCy2qAjvcLXcrrfsuiwQAvY7i7cMD7Fh3RMFQyEWU/edit?usp=sharing)

[Final Presentation](https://docs.google.com/presentation/d/1kVk1IUnFhH4zG_ar8WkQFQJYWjOv9jYq3tiJ93qjXNY/edit?usp=sharing)



## Erdos deadlines:

#### Data gathering and defining stakeholders + KPIs - May 19, 2023
Find the dataset you will be working with. Describe the dataset and the problem you are looking to solve (1 page max). List the stakeholders of the project and company key performance indicators (KPIs) (bullet points).

#### Data cleaning + preprocessing - May 19, 2023

Look for missing values and duplicates. Basic data manipulation & preliminary feature engineering.

#### Exploratory data analysis + visualizations [Checkpoint] - May 26, 2023

Distributions of variables, looking for outliers, etc. Descriptive statistics.

#### Written proposal of modeling approach [Checkpoint] - May 26, 2023

Test linearity assumptions. Dimensionality reductions (if necessary). Describe your planned modeling approach, based on the exploratory data analysis from the last two weeks (< 1 page, bullet points).

#### Machine learning models or equivalent [Checkpoint] - Jun 1, 2023

Results with visualizations and/or metrics. List of successes and pitfalls.

#### Final project due - Jun 3, 2023



