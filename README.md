# FCC Demographic Data Analyzer

This project analyzes demographic data extracted from the 1994 Census database using Python and Pandas. It answers key questions about the dataset related to race distribution, education levels, income, work hours, and occupations.

## Dataset

The dataset used is `adult.data.csv`, which contains demographic information such as age, workclass, education, race, sex, native country, salary, and more.

## Features / Questions Answered

- Count of each race represented in the dataset
- Average age of men
- Percentage of people with a Bachelor's degree
- Percentage of people with advanced education (`Bachelors`, `Masters`, `Doctorate`) earning more than 50K
- Percentage of people without advanced education earning more than 50K
- Minimum number of hours worked per week
- Percentage of people working minimum hours who earn more than 50K
- Country with the highest percentage of people earning more than 50K and that percentage
- Most popular occupation for high earners (`>50K`) in India

## How to Run

1. Make sure you have Python 3 installed.
2. Install pandas if you haven't already:

   ```bash
   pip install pandas
