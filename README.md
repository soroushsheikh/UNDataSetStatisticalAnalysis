# Statistical and Predictive Analysis on the United Nations Global Terrorism Database (GTD)

This project is an in-depth analysis of the United Nations Global Terrorism Database (GTD), conducted using the R programming language. The aim of the project was to explore the GTD, identify patterns and trends, and develop a predictive model to classify the success of terrorist attacks based on various factors.

## Data
The GTD contains information on terrorist attacks around the world from 1970 to 2019, including attack details, perpetrators, and victims. The data was obtained from the [START Consortium](https://www.start.umd.edu/gtd/) and was preprocessed and cleaned for analysis.

## Methodology
The project was divided into three main sections: exploratory data analysis (EDA), statistical analysis, and predictive modeling.

### Exploratory Data Analysis

Exploratory Data Analysis (EDA) was a critical step in understanding the Global Terrorism Database (GTD) and identifying trends and patterns in the data. The purpose of EDA was to visualize the data using various graphs and charts to highlight patterns in the data.

In this section, our analysis focused on several aspects of the data. Firstly, we examined temporal patterns throughout the years, to identify any trends or changes in terrorism patterns over time. Secondly, we analyzed attack casualties and its relations to other numerical and categorical variables to gain insights into the characteristics of different types of attacks. Thirdly, we conducted correlation analysis to determine the strength and direction of relationships between variables in the data. Fourthly, we analyzed the attacks in different regions of the world to gain insights into global terrorism patterns. Lastly, we examined different types of attacks to identify any patterns in the methods used in terrorist attacks.

![EDA](https://github.com/soroushsheikh/UNDataSetStatisticalAnalysis/blob/main/EDA.png)

Overall, EDA was a crucial step in understanding the GTD data and provided valuable insights into the trends and patterns in global terrorism. The visualizations and analysis performed in this section laid the groundwork for subsequent predictive modeling and analysis.

### Statistical Analysis
The statistical analysis focused on identifying significant factors that contribute to the success of terrorist attacks, as well as confirming patterns that were identified during the exploratory data analysis.

To this end, we analyzed several patterns, including the average fatalities of attacks and their relationship with different regions of the world. Specifically, we compared fatalities in the US and Canada. We also explored the relationship between multiple attack incidents and attack types, as well as the success rate of attacks.

our statistical analysis involved the use of various hypothesis testing methods, including t-tests, pairwise t-tests, chi-squared test for independence, and analysis of variance. These tests allowed us to formally confirm patterns that we had observed during our exploratory data analysis, and to make meaningful inferences about the relationships between variables. The use of rigorous statistical methods ensured that our findings were reliable and reproducible, and allowed us to draw more robust conclusions about the factors that contribute to the success of terrorist attacks.

### Predictive Modeling
In the Predictive Modelling phase, we aimed to build models that could predict the number of casualties and the success of a terrorist attack. We used linear regression to predict the number of casualties and logistic regression to predict the success of an attack. To improve the accuracy of the models, we used various factors as predictors.

To evaluate the quality of our models, we used cross-validation and ROC curves. Cross-validation was used to estimate how well the models would generalize to new data. The ROC curves were used to determine the trade-off between the true positive rate and the false positive rate for different thresholds.
