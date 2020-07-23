# A/B Test Results
## Analyzing an E-commerce's A/B Test Results 
This project focuses on understanding the results of an A/B test run by an e-commerce website. The company developed a new page to increase conversion rates. The goal of this analysis is to explore and reveal insights to help the company understand if they should implement this new page, keep the old page, or run the experiment longer to make their decision.

# Datasets
This project consists of two datasets. One includes experimment information such as user_id, timestamp, group, landing page version, and converstion rates. The second dataset includes the same information but categorized by country. Both datasets were provided by Udacity and are included in this repo as 'ab_data.csv' and 'countries.csv', respectively. Similar datasets can be found on Kaggle like the [A/B Test Results an e-commerce website'](https://www.kaggle.com/brittoh/a-b-test-results-an-e-commerce-website/notebook#A/B-Test-Results-an-e-commerce-website) project.

# Software
The following was used to build the analysis:
* Python and libraries:
  * Matplotlib
  * NumPy
  * pandas
  * random
  * SciPy
  * statsmodels
* Jupyter Notebooks

# Summary of Findings
There is not sufficient evidence to suggest any signficant differences between the new and old landing page on conversion rates. Other variables could be identified to further test their impact on conversion rate. However this would require additional time, finances, and resources. Based on the current analysis, the new page is not bringing much value with no significant impact. For this reason, it would make sense to keep the old page, develop and test additional features.

# Credits
* [Kaggle: A/B Test Results an E-Commerce Website](https://www.kaggle.com/brittoh/a-b-test-results-an-e-commerce-website/notebook#A/B-Test-Results-an-e-commerce-website)
* [pandas.DataFrame.join](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.join.html)
* [Udacity](https://www.udacity.com/course/data-analyst-nanodegree--nd002)
