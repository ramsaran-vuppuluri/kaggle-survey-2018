# Kaggle Data Scientist & Machine Learning survey 2018

Kaggle had initiated an industry-wide survey in 2017 that presents a truly comprehensive view of the state of data science and machine learning. In 2018, the study was live for a week in October and had collected responses from 23,859 individuals.

Data set used for the analysis is has 390+ columns. Not all columns are needed at any given point of the study. For this reason, the notebook is further divided into multiple subsections which will start with a business question, followed by data analysis. Only the columns that are related to the business question are extracted for analysis.

Furthermore, we are persisting extracted columns into separate CSV files that are utilized for generating visualizations using Tableau for Medium blog post.

One significant advantage with this approach is we are not ignoring the whole row if the respondent has not to answer specific questions. We are going to include all the answers (non-freeform) in the analysis.

## Project Components

#### Individual Information Analysis

In this Jupyter notebook, exploratory data analysis is performed to extrapolate the following traits of survey respondents:
1. Age
2. Gender
3. Country of residence
4. Coding & Machine learning experience.

#### Education & Training Analysis

In this Jupyter notebook, exploratory data analysis is performed to extrapolate the formal & informal education sources of survey respondents.

#### Technical Stack Analysis

In this Jupyter notebook, exploratory data analysis is performed to extrapolate the following traits of survey respondents:
1. Languages 
2. Frameworks
3. Tools & Utilities

#### Employment Information Analysis

In this Jupyter notebook, exploratory data analysis is performed to extrapolate the employment status, current job title and salary insights of survey respondents.

#### Metrics of Quality Assessment Analysis

In this Jupyter notebook, exploratory data analysis is performed to extrapolate:
1.  How do business measure the success of data science projects
2. How do data scientists quantify model results

Each of the above project components persists snippets of clean CSV files and the seaborn visualizations. Clean data CSV files are used to generate Tableau visualizations used by the blog post. 

## Libraries
    
    | Library       | Version   |
    | ------------- |-----------|
    |Pandas         | 0.22.0    |
    |seaborn        | 0.8.1     |
    
## External links
Tableau https://public.tableau.com/profile/ram.saran.vuppuluri#!/

Medium https://towardsdatascience.com/state-of-data-science-machine-learning-e8bdd4f21b6b
