# Rabiat Blessing Ibrahim

Cloud and DevOps engineer building deep analytics and machine learning capability
alongside a strong infrastructure background, currently pursuing a Master of Science
in Analytics (Applied Machine Intelligence) at Northeastern University, Vancouver.

Very few engineers combine hands-on cloud infrastructure experience with genuine
analytics depth. I am developing both deliberately, not moving from one to the
other, because the intersection is where I can offer the most value: building
systems that are not just reliable and scalable, but also generate and act on the
data that drives real business decisions.

## Technical Skills

**Languages:** Python, SQL, R, VBA
**Cloud and DevOps:** AWS (SageMaker, CloudWatch, Cost Explorer), Docker, Kubernetes,
Terraform, GitHub Actions
**Data and ML:** scikit-learn, pandas, Flask, BigQuery, Spark, NLP

## Featured Projects

**[Cloud Resource Management and Cost Optimization System](https://github.com/EseoheB/cloud-cost-optimization-db)**
A 19-table MySQL database for tracking cloud usage, budgets, department chargeback,
and invoice reconciliation. Benchmarked indexes on 2 million synthetic usage events
with EXPLAIN ANALYZE, cutting a per-resource cost query from 1.5 s to 23 ms. Results
feed a [live Tableau dashboard](https://public.tableau.com/app/profile/rabiat.blessing.ibrahim/viz/CloudCostOptimizationDashboard_17918460822610/CloudCostOptimization).

**[NYC Taxi BigQuery Analysis](https://github.com/EseoheB/nyc-taxi-bigquery-analysis)**
SQL analysis of 146 million NYC yellow taxi trips in Google BigQuery, built as a
three-person team project. My queries compare card and cash riders by hour and
measure revenue per mile, where fixing an outlier problem revealed that hours with
longer trips earn less per mile (r = -0.90).

**[Climate Emission Strategy Analysis](https://github.com/EseoheB/climate-emission-strategy-analysis)**
Analysis of 2.4 million emission reduction records from Climate TRACE, ranking
decarbonization strategies by raw impact versus impact adjusted for implementation
difficulty. Identifies sectors where the two rankings disagree and surfaces the
more actionable choice.

**[MLOps Pipeline](https://github.com/EseoheB/mlops-pipeline)**
End-to-end machine learning pipeline that classifies documents from the 20 Newsgroups
dataset with TF-IDF and logistic regression, reaching 90.56% accuracy. Covers
preprocessing, training, and evaluation, and serves the model through a Flask API
with /health and /predict endpoints.

**[HIV Trends in Sub-Saharan Africa](https://github.com/EseoheB/sub-saharan-hiv-analysis)**
MySQL database combining UNAIDS HIV estimates with World Bank economic data for 49
countries, 2007-2024, with R scripts and a
[live Tableau dashboard](https://public.tableau.com/app/profile/rabiat.blessing.ibrahim/viz/Sub-SaharanAfricaHIVTrends2007-2024/HIVTrendsinSub-SaharanAfrica).
Found and fixed 116 values that understated new infections and deaths, revealing a
60% drop in new infections across the region.

### [Understanding Magazine Subscription Behavior](https://github.com/EseoheB/marketing-campaign-subscription-prediction)
Predicted which customers will subscribe using logistic regression and SVM in Python, handling a 14.9% subscribe rate with balanced class weights. The SVM reached 86.70% AUC, and past campaign response, recent purchases, and customer tenure were the strongest drivers.
**Tools:** Python, pandas, scikit-learn, matplotlib, seaborn

## Currently

Adding my remaining analytics and cloud projects to GitHub, each with documented
queries, real results, and notes on what the data did and didn't show.
