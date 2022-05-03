# E-commerce AB Testing Project Walk Through

For this project, I will be working to understand the results of an A/B test run by an e-commerce website if they should implement the new page, keep the old page, or perhaps run the experiment longer to make their decision.   

This project includes the following contents:
* Introduction
* 1 - Exploratory Data Analysis & Data Cleaning
* 2 - Probability
* 3 - A/B Test
* 4 - Regression


Before Part 2: Probability, I will perform data cleaning such as checking missing data, discrepancies between the columns etc.

### Language and Package
This project is using Python3. The packages are used in this project including Numpy, Panda, random, matplotlib.pyplot, scipy.stats, and  statsmodels.api.

### Metadata of variables
1. [ab_data.csv](https://github.com/jemc36/Udacity-DAND-AB-test-ecommerce/blob/master/ab_data.csv)  

| Variable Name | Metadata                   |
|---------------|----------------------------|
| user_id       | 6-digit numbers            |
| timestamp     | string                     |
| group         | string: control, treatment |
| landing_page  | string: old_page, new_page |
| converted     | numeric: 0:No, 1:Yes       |

2. [countries.csv](https://github.com/jemc36/Udacity-DAND-AB-test-ecommerce/blob/master/countries.csv)  

| Variable Name | Metadata           |
|---------------|--------------------|
| user_id       | 6-digit numbers    |
| country       | string: US, CA, UK |

### Methodology
* A/B Test
* Two-Proportion z Test
* Logistic Regression

