# DSC-630
This project will use data science techniques to study an IRS dataset with individual 2018 tax data. With this data, we will present a prediction of the taxes that will be collected in the 2020 year. Several variables such as income, deductions, overpayments, taxes paid, interest paid, characteristics of the taxpayers such as status, dependents and type of employment will be analyzed. Location variables such as state, county, and ZIP code tabulations will also be analyzed.

Background

Problem Statement

Predict tax collection for the year 2020. 
Requirements

This project will help identify if taxes for the upcoming year will increase or decrease.  Determine what percentage continues to increase.  What percentage has decreased. 

Preliminary Requirement

Technical Approach

We will be using descriptive analysis and data modeling. We would also add new approach as we learn from this course.
Data Source

We will use an IRS dataset with statistics of income which was tabulated using individual income tax returns (Forms 1040) filed with the Internal Revenue Service (IRS) during the 12-month period, January 1, 2019 to December 31, 2019. The data is segmented by the ZIP code of each State in the United States.
Analysis

With the dataset that we selected we will clean the data, remove nulls, handle outliers, organize/shape.  Also, identify patterns, anomalies, any correlations between variables, matrices, and linear regression. 
Data preparation: we will validate problems with data
	Missing values
	Outliers
	High cardinality
	Spikes
Selection of required data
Data integration and formatting
Data cleaning
Data transformation and enrichment
Data visualization
Requirement Development

3 computers…
Python programming environment, 
Python 3.7.4 <--Usa Python 3.7 32 bits
Anaconda Navigator 1.9.7 <-- Usa Python 3.6 64bits
Jupyter Notebook 5.5.0
GitHub Repository…

Model Deployment

Models utilized will be machine learning and will be deployed on GitHub for continuous integrated deployment. 
Testing and Evaluation

For testing we will use the Train, Test, Split analysis with random seeds on our algorithm.  As well as Predict and Confusion Matrix.  The following of our model with be tested:
Accuracy
Recall
F1 Score
Precision
ROC Curve

Expected Results

Through the analysis of the individual tax data collected in 2018 by IRS, we will use a prediction model that anticipates the real money collected for individual taxes in future years...
Execution and Management of Project

Project Plan

•	Milestone 2 – Data Selection and Project Proposal

•	Milestone 3 – Preliminary Analysis

•	Milestone 4 – Project Presentation & Status

•	Milestone 5 – Final project paper and presentation







Risk

The risk is making a biased prediction, because the data can have errors. Individual Tax returns may contain errors reported directly by taxpayers, for example:
•	State codes were based on the ZIP code shown on the return.

•	State totals may not be comparable to State totals published because of disclosure protection procedures or the exclusion of returns.

•	Data do not represent the full U.S. population because many individuals are not required to file an individual income tax return.

•	The address shown on the tax return may differ from the taxpayer’s actual residence.

•	Tax returns filed without a ZIP code and returns filed with a ZIP code that did not match the State code shown on the return were excluded.

•	Tax returns filed using Army Post Office (APO) and Fleet Post Office addresses, foreign addresses, and addresses in Puerto Rico, Guam, Virgin Islands, American Samoa, Marshall Islands, Northern Marianas, and Palau were excluded.

•	ZIP codes with less than 100 returns and those identified as a single building or nonresidential ZIP code were categorized as “other” (99999).

•	Income and tax items with less than 20 returns for a particular AGI class were combined with another AGI class within the same ZIP Code.  Collapsed AGI classes are identified with a double asterisk (**).
•	All number of returns variables have been rounded to the nearest 10.

•	Income and tax items with less than 20 returns within a ZIP code were excluded.

•	Tax returns with a negative adjusted gross income were excluded.



Deliverable

A document that will explain the variables that were used in the prediction model, the type of model used, the possible errors, and the results of the predictive model....

Timeframe

11 weeks....
 
