# Predicting Corporate Bankruptcies

This project began as my graduation project for Brainstation NYC's Data Science Bootcamp during Fall 2023.  As of December 2023, my project has been trained on large public corporate bankruptcies from the past decade and attempts to forecast and quantify the likelihood of bankruptcies in S&P 500.

Rather than observe the changes in security prices to indicate impending bankruptcy, this project attempts to understand bankruptcy at the accounting level.  As of December 2023 this analysis uses 37 features derived from corporate Income Statements, Balance Sheets, and Statements of Cash Flow.

Future updates will expand the set of forecast copmanies from the S&P 500 to the Russell 3000, incorporate macroeconomic context, and attempt to forecast bankruptcy on longer timeframes (currently the model predicts bankruptcy within the next year.)

You can find a link to my project [here](http://3.85.50.226:8501/).

# Project overview
A timeline of updates, additions, and improvements.

1 - Identify potential data sources on bankruptcy, conduct basic EDA and identify areas to generate valuable insight

2 - Conduct more advanced data preprocessing, EDA and baseline model creation

3 - (Completed ahead of Capstone Demo Day) Acquire and clean detailed financial data from coprorate bankruptcies in the past decade as well as detailed financial data from current public companies in the S&P 500.


## Motivation

I have a background in investment banking and corporate finance and am interested in understanding when and why companies go bust.

I chose this project initially as it offered several advantages that would be helpful at the beginning of DS / programming career:
- Ability to practice python packages and ML techniques I learned in class on data from a domain that I have an existing deep understanding of
   Current:
    - Major packages used: NumPy, Pandas, SciKit Learn
    - ML techniques used: Logistic Regression, Decision Trees, Random Forest
    Planned:
    - Neural Networks, XG Boost
- Practice quering APIs at multiple endpoints to retrieve financial data
    - Current: XBRL API
    - Planned: SEC API (please note the underlying data is the same though querying approaches differ)

