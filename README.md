<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue">
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-yellow">
  <img src="https://img.shields.io/badge/Status-Completed-brightgreen">
  <img src="https://img.shields.io/badge/Project-Customer%20Churn%20EDA-blueviolet">
</p>

# Customer Churn Exploratory Data Analysis (EDA)



## Project Overview



Customer churn represents a significant revenue risk for subscription-based businesses.

With an observed churn rate of approximately **34%**, the company faces substantial lifetime value erosion driven by early-stage attrition, contract structure, pricing sensitivity, and service experience.



This project applies structured Exploratory Data Analysis (EDA) and statistical testing to identify the most influential churn drivers and validate revenue-related business logic within the dataset.



## Business Problem



A subscription-based telecommunications company is experiencing elevated customer attrition, with roughly one-third of customers discontinuing service.



Churn reduces revenue stability, increases acquisition costs, and weakens long-term profitability. However, the company lacks clarity on:



*	Which customer characteristics influence churn?

*	How contract structure affects retention

*	Whether pricing impacts churn probability

*	Which service features stabilize customer retention



This analysis provides statistical validation of churn drivers to inform targeted retention strategy.



## 🛠 Methodology

The project followed a structured EDA workflow:



### 1.Data Validation & Cleaning



*	Checked duplicates and missing values

*	Handled invalid entries

*	Applied IQR method for outlier assessment

*	Standardized categorical formats



### 2. Exploratory Analysis



*	Distribution analysis (histograms, boxplots)

*	Churn segmentation comparisons

*	Revenue logic validation



### 3. Statistical Testing



*	Independent t-tests (normally distributed variables)

*	Mann–Whitney U tests (non-normal distributions)

*	Chi-square tests (categorical associations)

*	Cramér’s V (effect size measurement)

*	Pearson correlation analysis (numeric relationships)



## Key Results

*	Overall churn rate is approximately 34%.

*	Short-tenure customers are significantly more likely to churn.

*	Higher monthly charges are associated with increased churn likelihood.

*	Tenure and total charges show strong positive correlation (r = 0.77), confirming revenue accumulation over time.

*	Month-to-month customers churn at over 43%, compared to ~21% for long-term contracts.

*	Customers without technical support churn at nearly double the rate of those subscribed.

*	Payment method, internet service type, and online security show minimal association with churn.

*	No extreme multicollinearity detected among numeric predictors



## Business Insights

*	Early-stage customers represent the highest revenue risk segment.

*	Contract structure significantly influences customer commitment.

*	Technical support acts as a retention stabilizer.

*	Pricing increases churn sensitivity when perceived value is insufficient.

*	Revenue stability is structurally dependent on customer tenure.



## Recommendations

*	Strengthen onboarding and early engagement strategies to reduce early-stage churn.

*	Incentivize migration from month-to-month contracts to longer-term plans.

*	Bundle and actively promote technical support services as retention tools.

*	Reassess value communication for higher-priced plans to reduce pricing sensitivity.

*	Develop targeted retention strategies for short-tenure, high-risk customers.



## Next Steps

*	Build a predictive churn classification model (Logistic Regression, Random Forest, or Gradient Boosting).

*	Perform feature importance analysis to quantify churn driver strength.

*	Develop a churn risk scoring system for proactive customer segmentation.

*	Design and test targeted retention interventions for high-risk groups.

*	Build an executive dashboard to monitor churn drivers and retention trends over time.



## Tools & Technologies

* Python

* Pandas

* NumPy

* Matplotlib

* Seaborn

*	SciPy

*	Jupyter Lab



## Project Structure



Customer_Churn_EDA/

├── data/

├── notebooks/

├── images/

├── README.md        

├── requirements.txt  

└── .gitignore        



## Environment & Reproducibility



The analysis was conducted in a dedicated Anaconda virtual environment to ensure reproducibility and dependency control:



* Python 3.10.19  

* Anaconda Distribution  

* JupyterLab Interface  

* Isolated project-specific environment  



All analytical dependencies are documented in `requirements.txt`.

