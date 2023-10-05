#  Predicting Student Dropout Rates in Online Courses

## Problem

Develop a machine learning model that predicts which students are most likely to drop out of online courses based on their engagement, interaction, and performance data.

## Goal
The goal of this project is to identify at-risk students early in their course journey, enabling educational institutions to provide timely support and interventions to improve retention rates

## Data
The dataset includes student enrollment data, course interaction logs, grades, demographic information, and historical dropout records.

## Data Collection
Gather data from various sources, such as enrollment data, course interaction logs, grades, demographic information, and historical dropout records. We may need to collaborate with online learning platforms to access this data.

## Type of Learning
Supervised Learning: You have labeled data (dropout or not)

## Machine Learning Problem Types
- Based on Type of Data: Supervised Learning
- Based on Type of Output: Classification.
- Based on Business Goals: Aligns with the company's goal to identify at-risk - students early in their course journey and rescue these numbers.
- Based on Data Representation: Structured Data
- Based on Problem Complexity: Binary Classification (dropout or not)
- Based on Feedback Mechanism: Batch Training

## Exploratory Data Analysis (EDA) and Determine Data Quality Issues
- Data Overview
The dataset includes student enrollment data, course interaction logs, grades, demographic information, and historical dropout records

- Data Relationships
Some correlations found between dropout frequency and date.
Some correlations found between Gender and Course content.
Some correlations found between course level and skilled or not.
Some correlations found between dropout frequency and mentor rate.
Some correlations found between dropout frequency and cost.

| Name | Gender | Age | Nationality | Course name | Course logs | Grades | History |
|------|--------|-----|-------------|-------------|-------------|--------|---------|
|      |        |     |             |             |             |        |         |


## After preprocessing

| Name | Gender | Age | Language | Course name | Course cost | Grades | Skilled or not | Course level | Mentor rate | Internet available | Dropout date |
|------|--------|-----|----------|-------------|-------------|--------|----------------|--------------|-------------|--------------------|--------------|
|      |        |     |          |             |             |        |                |              |             |                    |              |
|      |        |     |          |             |             |        |                |        