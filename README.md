## Project 1 — What Factors have impact on developers’ work and life
There was a online developer survey on Stack Overflow in Year 2019. It is about the developer's work and education, tech culture, stack overflow usage, etc.  
When the survey result released, developers may may be curious about the salary of other people, how they can earn so much money, why they have a satisfied career development. This project is going to have a simple study about the factors that influence developers’ work and life.

### Libraries used
- _numpy_  
- _pandas_  
- _matplotlib_  

### Files in the repository
- _Project1.ipynb_ - the Jupyter notebook, containing all the project code  
- _config.yml_ - theme configuration file

### Business Understanding
#### Which factors affect salary?  
#### Which factors have impact on career satisfaction?  
#### Which factors influence the expectation of life in next generation?  

### Data Understanding
- Correct data type for some fields
- Find and analyze the categorical fields, then handle the NA value by droping, filling or converting dummy.

### Data preparation
Drop record of NA data such as age, which is important, not sensitive and not difficult to fill. Developers refused to fill this kind of information are considered not serious, and the answers provided by them are considered not helpful;  
Fill categorical NA data such as education level with 'Other';  
Create dummy variables for categorical data, for those containing multiple values with seperator ';' in a cell, split them and create dummy variables.  

### Model
Linear Regression

### Prediction and Evaluation
The score is very bad at first. After simplifying the model by removing some fields, the score is OK.

### Result
1. Factors influence salary: Years of coding and age are positive, certainly, because experience are important. In my opinion, code review hour should be positive, which helps people to learn. Maybe because it wastes time or sacrifice too working time. Working hours are positive but small, this makes sense, working efficiency is important;.  
2. Factors influence career satisfaction: Salary seems not have as much impact on career satisfaction as I thought. Young people seems are more likely to be satisfied by their career development;  
3. Factors influence expectation of life in next generation: Older people tend to have negative opinion. Years of coding and hours of code review is positive, maybe experienced people understands information technology changing life better. People satisfied with their career has positive opinion.  

### Improvement in the future
We can include more parameters and adopt models more complicated.
