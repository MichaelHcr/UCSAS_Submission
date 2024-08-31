# Team Wailian - UCSAS 2024 Repository 🐶🐶🐶

Welcome to team Wailian's repository for the [2024 USOPC Data Challenge](https://statds.org/events/ucsas2024/challenge.html#overview)!

## 🎯 Goal
The goal of the competition is to **identify the groups of 5 athletes** who will enable the USA Olympic Men’s and Women’s Artistic Gymnastics teams to **optimize success** in Paris 2024 based on data from athletes' performance in gymnastics competitions in the past year.

## 🧾 Contents
This repository contains our final report (pdf) and a few Jupyter notebook (.ipynb) files each serving a specific purpose in the data analysis pipeline.
- **report.pdf**: This is our final report, recording our data-processing methods, analysis and modeling results, and our final recommendations for the optimal USA teams to join the Olympics 2024.
- **data_cleaning.ipynb**: This notebook contains all the necessary steps taken for data cleaning, including cleaning repeated athlete names, handling missing values, correcting misformatted information, and data transformation.
- **EDA.ipynb**: This notebook is dedicated to Exploratory Data Analysis (EDA). It includes data visualization, analysis of score distributions of individual apparatus, and correlation among scores.
- **modeling_and_individual_analysis.ipynb**: This notebook outlines 2 models to predict optimal all-round teams of 5 athletes. The second half of this notebook consists of deeper analyses carried out on the competitive landscape of each apparatus and USA athletes' placement in the world.

## 📊 Data Files
Data files used for analyses are located in the data_files folder:
- **women_individual.csv**: Summary of performance for each female athlete.
- **men_individual.csv**: Summary of performance for each male athlete.
- **women_raw.csv**: Cleaned data frame recording all competition performances for female athletes.
- **men_raw.csv**: Cleaned data frame recording all competition performances for male athletes.
