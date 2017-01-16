<<<<<<< HEAD
#Case study 2: Cross sell BIL - Analytics In SME Business

## Challenge

  Since the end of 2015, SME has been concentrating on developing unsecured loan portfolio. Out of all types of unsecured loans, BIL is the most profitable one with a NIM of about 11%. However, out of 13,656 customers having SME loans, only 1,566 customers have BIL (11% penetration) with 40% of them having/had at least 2 BIL contracts. The challenge for SME business is to find the most potential customers for cross selling BIL 

 More specifically, the current situation for different segments is given as follows:

* SME customers having at least one loan: 13,656 as of Jul, 2016
* SME customers having BIL: 1,566 (11% of customer base having loans) 

## Methodology

In order to find the potential customers for cross selling BIL, BICC analyzed customer demographic and product holding data of SME loan customers. BICC then used 2 methods - basket analysis (briefly explained in case study 1) and multivariate analysis to identify the potential customers. 

**Multivariate analysis** (MVA) is based on the statistical principle of multivariate statistics, which involves observation and analysis of more than one statistical outcome variable at a time

## Results and Recommendations

  After analyzing various data variables through multivariate analysis, BICC found that majority of BIL customers have the following characteristics:
  
* Vintage <= 3 years (76%)
* Belong to top 4 industries as shown in the chart on left (43%)

Based on the outcome above, BICC recommended to target a further 2,441 customers bringing the total of potential customers for cross selling BIL to 2,568.

## Implementation and Business Impact

### Implementation

The  customer list (2,568 customers) was shared with SME BD/marketing departments for designing and executing initiatives in order to cross sell BIL. Before customers were targeted, 2 actions were taken by the product department in business unit:

* Product policy was revised to accommodate BIL
* Lending criteria were expanded in order to include more and more customers

### Business Impact

  BICC estimate the TOI impact after converting all potential SME customers is: **92 Billion VND per year**. As of 24 Sep, 2016, a total of 38 SME customers have been cross sold BIL already (1% conversion rate), bringing in 1.4 Billion VND of total TOI impact.
  
# Case Study 3: Cross sell credit card and UPL - Analytics In Retail Business

## Challenge

  Retail division is implementing deep farming strategy in 2016, a core plank of which is cross selling credit card and UPL to active customers. Historical conversion rates of cross selling programs have been quite low with 0.66% for NPA (non-preapproved) credit card, 4.28% for PA (pre-approved) credit card and 1.87% for NPA UPL. The challenge is to identify high potential customers who can be targeted for these two products.

  Current situation is given as follows:

* 1.23 million total retail customers, 70% of them active (as of Feb, 2016)
* Credit card and UPL penetration rates quite low (10% and 8% respectively)

## Methodology

  To find potential customers, BICC created an opportunity vs. value (TOI) matrix and defined a good target base from very high TOI or very high opportunity customers. Further to this, logistic regression based cross sell models were built for credit card and UPL in order to generate cross sell leads for all sales channels. **Logistic regression** measures relationship between categorical dependent and independent variables using a logistic function.

## Results and Recommendations

  A1, A2, and A4 are good customer segments which retail division should focus for deep farming. Total customers in good customer base: 92,844.

  For PA cross sell programs, all good customers should be highly prioritized for contacting through all sales channels. For customers who can not be converted, BICC to generate NPA leads for credit card and UPL cross sell based on the propensity scores generated through the models.
  
  From 2016, retail division has been focusing on PA programs to drive cross selling. But good customers who somehow were not qualified for PA conditions were not contacted for cross selling at all. By utilizing cross sell models, BICC now can extract around 20,000 customers for NPA programs. BICC estimates the number of cross sold products will be 1,229 credit cards and 1,223 UPLs out of the NPA base.

## Implementation and Business Impact

### Implementation

Credit card and UPL potential NPA leads were uploaded to CRM system for branches and central farming team for cross selling.

BICC worked closely with BMT department of retail division to communicate and instruct sales channels in those programs while proposing support policies in order to get highest conversion rates.

BICC also created reports to help track programs’ performance while continuing to apply further analytics to improve the performance of regression models and generate new cross sell leads.

### Business Impact

BICC estimate the TOI impact after converting all potential customers is: **13 Billion VND per year**. As of 24 Sep, 2016, a total of 200 credit cards and 279 UPL contracts have been cross sold already (around 2% conversion rate), bringing in 2.7 Billion VND of total TOI impact.

# Case Study 4: Reduce credit card attrition

## Challenge

  Retail division has a strategy to sell 1 million credit cards in the future. However, despite the efforts to issue more and more credit cards to retail customers, many are still being closed voluntarily in 2016. The challenge for retail division is to reduce voluntary attrition rate through identifying potential closed card holders as well as understanding and minimizing drivers which increase card attrition.
  
  The current situation is given as follows:
  
* Average monthly voluntary closure rate of credit cards: 1.48% of total cards
* The voluntary closure rate of credit cards has been on the rise 

## Methodology

  In order to find potential closed card holders, BICC ran a **logistic regression** model with 83 variables from customer demographics, customer product holding and credit card transaction data of customers. BICC analyzed all voluntarily closed credit cards in Jul, 2016 to confirm key voluntary attrition drivers. 

  Moreover, BICC used historical data analysis to determine optimal time to take action and profit & loss analysis to find good profitable cards which can be retained.
  
## Results and Recommendations

  The regression model has GINI (a measure of model strength) of 68% and historical data testing showed that higher scored customers have higher closure rate. Therefore, model predicted well the potential voluntarily closed card holders. BICC recommended to take action for these customers by calling them before they decide to close their cards (early retention call). The list of potential customers would be generated by BICC on a monthly basis.

  Detailed analysis of credit cards closed voluntarily in Jul, 2016 emphasized the impact of annual fee to attrition rate. 90% of closed cards were not qualified for current annual fee waiving policy while 55% of closed cards were in or close to the fee due month. BICC recommended to have new annual fee waiving policy which can help retain good customers. The new policy, combined with early retention call, will create a big impact on retaining these customers.
  
  Historical analysis showed that one third of total closures happened within 3 months prior to annual fee due month. BICC recommended to take action before this period of time for all cards. BICC considered all credit cards having annual fee due month in Q4 of 2016 and applied profit & loss analysis to give 4 options for new annual fee waiving policy. BICC recommended to choose option 1 or option 3 to have a balance between fee gained and cards retained.
  
## Implementation and Business Impact

### Implementation

* Early retention call

  BICC extracted the list of potential closed card holders and sent to happy call team for calling customers to introduce credit card benefits or inform about annual fee waiving policy
  BICC worked closely with retail credit card team to track the result and had adjustments to increase calling effectiveness
* New annual fee waiving policy 

  Retail head/managers to decide the option for annual fee waiving. After that, credit card team will create policy and process to launch new annual fee waiving mechanism
  
### Business Impact

BICC estimate the loss impact of credit card attrition is: **62 Billion VND per year**. As of 20 Sep, 2016, we recorded a closure rate of 1.6%, which is 0.5% less than the historical average, bringing a reduction in loss (in other words, gain) of 16.5 Billion VND per year.

# Reduce declined credit card transactions

## Challenge

  One of the most important KPI of retail credit card team is to get 36 Billion VND of monthly TOI which can be achieved by increasing number and amount of transactions. However, there is a very high percentage of card holders who face declined transactions and many of them might decrease their card usage over time or even worse, close the card altogether. The challenge for retail business is to understand the loss impact of declined transactions and having actions to reduce the losses.
  
  Current situation is given as follows:
  
* The declined transactions rate for credit card holders in each 3-month period is high (~40%)
* The number of declined transactions is on the rise

## Methodology


  Finally, BICC used **profit & loss analysis** to estimate total loss from declined transaction.
  
## Results and Recommendations

  BICC recommended three key actions:

* Activate the e-commerce payment function by default
* Have limit incremental policy
* Send customers SMS when they face declined transactions

## Implementation and Business Impact

### Implementation

* Activate e-commerce payment function by default

BICC extracted list of card holders who have never activated  e-commerce payment function. Credit card team worked with marketing team to send SMS to those card holders about automatically activating the function. Card holders had the right to cancel it by sending feedback SMS

* New limit incremental policy for card holders

Credit card team proposed new limit incremental policy for card holders who have good repayment history. BICC helped to generate the qualified card holders list. Credit card team then worked with IT and other parties to increase overall limit of eligible card holders as well as inform to them by SMS

### Business Impact

BICC estimate the loss impact of credit card declined transactions is: **20 Billion VND per year**. As of 24 Sep, 2016, we recorded a declined rate of 16%, which is 4% less than the historical average, bringing a reduction in loss (in other words, gain) of 4.5 Billion VND per year.

For more information: Please contact Mr. Hoang Duc Anh - Team Lead of Business Analytics. Email: anhhd3@vpbank.com.vn. Phone number: 0977738939














  

  



































































=======
#Case study 2: Cross sell BIL - Analytics In SME Business

## Challenge

  Since the end of 2015, SME has been concentrating on developing unsecured loan portfolio. Out of all types of unsecured loans, BIL is the most profitable one with a NIM of about 11%. However, out of 13,656 customers having SME loans, only 1,566 customers have BIL (11% penetration) with 40% of them having/had at least 2 BIL contracts. The challenge for SME business is to find the most potential customers for cross selling BIL 

 More specifically, the current situation for different segments is given as follows:

* SME customers having at least one loan: 13,656 as of Jul, 2016
* SME customers having BIL: 1,566 (11% of customer base having loans) 

## Methodology

In order to find the potential customers for cross selling BIL, BICC analyzed customer demographic and product holding data of SME loan customers. BICC then used 2 methods - basket analysis (briefly explained in case study 1) and multivariate analysis to identify the potential customers. 

**Multivariate analysis** (MVA) is based on the statistical principle of multivariate statistics, which involves observation and analysis of more than one statistical outcome variable at a time

## Results and Recommendations

  After analyzing various data variables through multivariate analysis, BICC found that majority of BIL customers have the following characteristics:
  
* Vintage <= 3 years (76%)
* Belong to top 4 industries as shown in the chart on left (43%)

Based on the outcome above, BICC recommended to target a further 2,441 customers bringing the total of potential customers for cross selling BIL to 2,568.

## Implementation and Business Impact

### Implementation

The  customer list (2,568 customers) was shared with SME BD/marketing departments for designing and executing initiatives in order to cross sell BIL. Before customers were targeted, 2 actions were taken by the product department in business unit:

* Product policy was revised to accommodate BIL
* Lending criteria were expanded in order to include more and more customers

### Business Impact

  BICC estimate the TOI impact after converting all potential SME customers is: **92 Billion VND per year**. As of 24 Sep, 2016, a total of 38 SME customers have been cross sold BIL already (1% conversion rate), bringing in 1.4 Billion VND of total TOI impact.
  
# Case Study 3: Cross sell credit card and UPL - Analytics In Retail Business

## Challenge

  Retail division is implementing deep farming strategy in 2016, a core plank of which is cross selling credit card and UPL to active customers. Historical conversion rates of cross selling programs have been quite low with 0.66% for NPA (non-preapproved) credit card, 4.28% for PA (pre-approved) credit card and 1.87% for NPA UPL. The challenge is to identify high potential customers who can be targeted for these two products.

  Current situation is given as follows:

* 1.23 million total retail customers, 70% of them active (as of Feb, 2016)
* Credit card and UPL penetration rates quite low (10% and 8% respectively)

## Methodology

  To find potential customers, BICC created an opportunity vs. value (TOI) matrix and defined a good target base from very high TOI or very high opportunity customers. Further to this, logistic regression based cross sell models were built for credit card and UPL in order to generate cross sell leads for all sales channels. **Logistic regression** measures relationship between categorical dependent and independent variables using a logistic function.

## Results and Recommendations

  A1, A2, and A4 are good customer segments which retail division should focus for deep farming. Total customers in good customer base: 92,844.

  For PA cross sell programs, all good customers should be highly prioritized for contacting through all sales channels. For customers who can not be converted, BICC to generate NPA leads for credit card and UPL cross sell based on the propensity scores generated through the models.
  
  From 2016, retail division has been focusing on PA programs to drive cross selling. But good customers who somehow were not qualified for PA conditions were not contacted for cross selling at all. By utilizing cross sell models, BICC now can extract around 20,000 customers for NPA programs. BICC estimates the number of cross sold products will be 1,229 credit cards and 1,223 UPLs out of the NPA base.

## Implementation and Business Impact

### Implementation

Credit card and UPL potential NPA leads were uploaded to CRM system for branches and central farming team for cross selling.

BICC worked closely with BMT department of retail division to communicate and instruct sales channels in those programs while proposing support policies in order to get highest conversion rates.

BICC also created reports to help track programs’ performance while continuing to apply further analytics to improve the performance of regression models and generate new cross sell leads.

### Business Impact

BICC estimate the TOI impact after converting all potential customers is: **13 Billion VND per year**. As of 24 Sep, 2016, a total of 200 credit cards and 279 UPL contracts have been cross sold already (around 2% conversion rate), bringing in 2.7 Billion VND of total TOI impact.

# Case Study 4: Reduce credit card attrition

## Challenge

  Retail division has a strategy to sell 1 million credit cards in the future. However, despite the efforts to issue more and more credit cards to retail customers, many are still being closed voluntarily in 2016. The challenge for retail division is to reduce voluntary attrition rate through identifying potential closed card holders as well as understanding and minimizing drivers which increase card attrition.
  
  The current situation is given as follows:
  
* Average monthly voluntary closure rate of credit cards: 1.48% of total cards
* The voluntary closure rate of credit cards has been on the rise 

## Methodology

  In order to find potential closed card holders, BICC ran a **logistic regression** model with 83 variables from customer demographics, customer product holding and credit card transaction data of customers. BICC analyzed all voluntarily closed credit cards in Jul, 2016 to confirm key voluntary attrition drivers. 

  Moreover, BICC used historical data analysis to determine optimal time to take action and profit & loss analysis to find good profitable cards which can be retained.
  
## Results and Recommendations

  The regression model has GINI (a measure of model strength) of 68% and historical data testing showed that higher scored customers have higher closure rate. Therefore, model predicted well the potential voluntarily closed card holders. BICC recommended to take action for these customers by calling them before they decide to close their cards (early retention call). The list of potential customers would be generated by BICC on a monthly basis.

  Detailed analysis of credit cards closed voluntarily in Jul, 2016 emphasized the impact of annual fee to attrition rate. 90% of closed cards were not qualified for current annual fee waiving policy while 55% of closed cards were in or close to the fee due month. BICC recommended to have new annual fee waiving policy which can help retain good customers. The new policy, combined with early retention call, will create a big impact on retaining these customers.
  
  Historical analysis showed that one third of total closures happened within 3 months prior to annual fee due month. BICC recommended to take action before this period of time for all cards. BICC considered all credit cards having annual fee due month in Q4 of 2016 and applied profit & loss analysis to give 4 options for new annual fee waiving policy. BICC recommended to choose option 1 or option 3 to have a balance between fee gained and cards retained.
  
## Implementation and Business Impact

### Implementation

* Early retention call

  BICC extracted the list of potential closed card holders and sent to happy call team for calling customers to introduce credit card benefits or inform about annual fee waiving policy
  BICC worked closely with retail credit card team to track the result and had adjustments to increase calling effectiveness
* New annual fee waiving policy 

  Retail head/managers to decide the option for annual fee waiving. After that, credit card team will create policy and process to launch new annual fee waiving mechanism
  
### Business Impact

BICC estimate the loss impact of credit card attrition is: **62 Billion VND per year**. As of 20 Sep, 2016, we recorded a closure rate of 1.6%, which is 0.5% less than the historical average, bringing a reduction in loss (in other words, gain) of 16.5 Billion VND per year.

# Reduce declined credit card transactions

## Challenge

  One of the most important KPI of retail credit card team is to get 36 Billion VND of monthly TOI which can be achieved by increasing number and amount of transactions. However, there is a very high percentage of card holders who face declined transactions and many of them might decrease their card usage over time or even worse, close the card altogether. The challenge for retail business is to understand the loss impact of declined transactions and having actions to reduce the losses.
  
  Current situation is given as follows:
  
* The declined transactions rate for credit card holders in each 3-month period is high (~40%)
* The number of declined transactions is on the rise

## Methodology


  Finally, BICC used **profit & loss analysis** to estimate total loss from declined transaction.
  
## Results and Recommendations

  BICC recommended three key actions:

* Activate the e-commerce payment function by default
* Have limit incremental policy
* Send customers SMS when they face declined transactions

## Implementation and Business Impact

### Implementation

* Activate e-commerce payment function by default

BICC extracted list of card holders who have never activated  e-commerce payment function. Credit card team worked with marketing team to send SMS to those card holders about automatically activating the function. Card holders had the right to cancel it by sending feedback SMS

* New limit incremental policy for card holders

Credit card team proposed new limit incremental policy for card holders who have good repayment history. BICC helped to generate the qualified card holders list. Credit card team then worked with IT and other parties to increase overall limit of eligible card holders as well as inform to them by SMS

### Business Impact

BICC estimate the loss impact of credit card declined transactions is: **20 Billion VND per year**. As of 24 Sep, 2016, we recorded a declined rate of 16%, which is 4% less than the historical average, bringing a reduction in loss (in other words, gain) of 4.5 Billion VND per year.

For more information: Please contact Mr. Hoang Duc Anh - Team Lead of Business Analytics. Email: anhhd3@vpbank.com.vn. Phone number: 0977738939














  

  



































































>>>>>>> origin/master
