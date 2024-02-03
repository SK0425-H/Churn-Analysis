### What is Customer Churn?
Customer churn occurs when individuals or subscribers terminate their association with a company or service provider. In the highly competitive telecom industry, where customers have a plethora of options, annual churn rates typically range from 15-25 percent.

Given the vast number of customers, personalized retention efforts are challenging for most companies due to the associated high costs. However, identifying potential churn in advance enables companies to concentrate retention efforts on "high-risk" customers, aiming to expand coverage and enhance customer loyalty.

Detecting early signs of churn requires a comprehensive understanding of customer interactions across various channels. Successfully addressing churn not only helps companies maintain their market position but also fosters growth. Retaining existing customers proves more cost-effective than acquiring new ones, making client attrition reduction and effective retention strategies crucial for success in this industry. The ultimate goal is to increase the customer base, lower initiation costs, and maximize profits.

### Data Understanding
Total Charges - Had to convert to numeric, and found 11 missing values, but the % of missing values is immensely low i.e. 0.15%, its a Data Analysts call to either remove these records or impute them.   
### Data cleaning
Dividing the tenure column into tenure groups is a common preprocessing step in data cleaning for churn analysis. This transformation simplifies the analysis by categorizing customers based on their tenure, making it easier to identify patterns and trends. 
Deleting the original tenure column, after creating the groups, helps reduce redundancy in the dataset and ensures a more streamlined and efficient analysis process. This process facilitates better insights into the relationship between tenure and churn, contributing to a more effective churn analysis.  

### Univariate Analysis 
involves examining the categorical columns of the customer churn table in relation to the churn category. The aim is to identify key performance indicators (KPIs) that can contribute to reducing the churn rate.

### Bivariate Analysis 
takes the entire dataset and categorizes records into active and churned customers. By creating separate data frames for these groups, a comparative analysis is conducted between the columns in the query table. This approach helps identify factors that significantly impact the churn rate. Various graphs are generated during this analysis to visually represent the relationships.

### Numerical Analysis 
employs the lmplot method to generate a scatter plot between total charges and monthly charges, facilitating the identification of their relationship. Additionally, KDE plots are created for both monthly charges and total charges to assess the density of these factors in the dataset. These analytical techniques contribute to a comprehensive understanding of the factors influencing customer churn.
### Insights
-Month to Month customers are more likely to churn.

-Senior Citizens are more likely to churn.

-Customers without dependents exhibit a lower churn rate.

-Customers who do not engage in streaming movies are more likely to experience high churn.

-Customers who do not utilize streaming TV services are more prone to experiencing high churn.

-Customers without access to tech support are more likely to be associated with high churn.

-Customers without device protection are more likely to experience high churn.

-Customers with a tenure of 1-12 months are characterized by a high churn rate.

-Customers who opt for paperless billing tend to have a higher churn rate.

-Customers utilizing phone services exhibit a high churn rate.

-Female users actively using optic internet services tend to have a higher churn rate.

-Female customers who do not use online security features are more likely to be associated with a high churn rate.

-Females without any partner are more likely to churn.

-Males using Credit cards are more likely to churn.

-Females who do not utilize device protection are more likely to experience a higher churn rate.

-Females with tenure in the 1-12 month range are characterized by a higher churn rate.

-Male customers who use electronic cheque services are more likely to exhibit a high churn rate.
