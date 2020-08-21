# hdbproj
# Introduction/Preface

The purpose of this study is to use descriptive and inferential statistical methods to derive information from HDB apartments and their features. 

The data set used can be found at https://data.gov.sg/dataset/resale-flat-prices


# Key Assumptions
- Data used is sourced from data.gov.sg for HDB resale prices. The data set starts from January of 2017 and ends at March of 2020.



- Inflation will not be factored in. Within a three year span, inflation fluctuations affect prices by less than 0.1% (Statista, 2020).



- The research question is: Which predictor is most heavily weighted in determining resale price?
    - How can HDB apartments be classified and clustered according to their features?
    

    
- Due to time and resource constraint, only 2 variables will be chosen for the multiple linear regression. More than 2 variables might lead to overfitting of the model to the training data, resulting in sub-optimal predictive performance
    - 4 Univariate Linear Regressions will be conducted to determine which are the most heavily weighted predictors of price per square meter, followed by a Multiple Linear Regression collecting the most relevant and weighted predictors

## Reference

Statista, 2020. Singapore: Inflation rate from 1984 to 2021. https://www.statista.com/statistics/379423/inflation-rate-in-singapore/
