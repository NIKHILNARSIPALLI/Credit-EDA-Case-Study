# Credit EDA Case study

  This is an introduction report on the project – “ Credit EDA case study ”. The dataset 
is acquired from “ kaggle.com ”. This case study gives an idea of applying EDA in a real 
business scenario.

----------------------------

### About this dataset

  The dataset – “Credit EDA case study ”, contains two datasets. This project is based 
on information about loan-providing companies that find it hard to give loans to people due to 
their insufficient or non-existent credit history. Because of that, some consumers use it to 
their advantage by becoming defaulters.

  The data given in the first dataset contains information about the loan application at 
the time of applying for the loan and the second contains information about the client’s 
previous loan data and previous application status. When a client applies for a loan, there 
are four types of decisions that could be taken by the client/company:

• Approved: The company has approved the loan application.

• Cancelled: The client cancelled the application sometime during approval. Either the 
             client changed his/her mind about the loan or due to a higher risk of the client he 
             received worse pricing which he did not want.

• Refused: The company had rejected the loan (because the client does not meet their 
           requirements etc.).

• Unused Offer: The client has cancelled the Loan offer but is at a different stage of the 
                process.

These statuses are given in the 2nd dataset, in which the previous application status of 
the clients is provided. 

Concludingly in this case study, we will use EDA to understand how customer attributes 
and loan attributes influence the tendency of default

--------------------------------

### Dataset description

o No. of rows in the 1st dataset (current application) = 307511 o No. of 
  columns in 1st dataset (current application) = 122
  

o No.of rows in the 2nd dataset (previous application) = 1670214 o No.of 
  columns in 2nd dataset (previous application) =37

o This case study dataset contains 
- Categorical data 
- Numerical data

------------------------------------

### Reason for selecting this project

  This case study aims to give an idea of applying EDA in a real business scenario. In 
this case study, there is an opportunity to develop and understand risk analytics in banking 
and financial services and also understand how data is used to minimize the risk of losing 
money while lending to customers.

  Among other reasons, the most prominent reason for working with this case study is 
that it gives me an opportunity to understand the way a business entity might take its 
business decisions ridden on the vast data such a corporation might possess.

-------------------------------------

### Business objectives

  This case study aims to identify patterns which indicate if a client has difficulty paying 
their instalments which may be used for taking actions such as denying the loan, reducing 
the amount of the loan, lending (to risky applicants) at a higher interest rate, etc. This will 
ensure that the consumers capable of repaying the loan are not rejected.

  In other words, we analyze and understand the driving factors (or driver variables) 
behind loan default, i.e. the variables which are strong indicators of default. We can utilize 
this knowledge for portfolio and risk management

--------------------------------------

### Project domain

This project – “Credit EDA case study”, comes under the Banking and Finance department 
domain.

---------------------------------------

### Approach for this case study

• Import the required libraries
• Read the datasets
• Data cleaning and Filling negligible missing values
• Removing unwanted rows and columns
• Analyze columns and derive metrics
• Univariate Analysis, bivariate and multivariate analysis of all contentrelated columns
• Visualizing the data and concluding

-------------------------------------------

### Libraries used

o Numpy 
o Pandas 
o Matplotlib
o Seaborn

--------------------------------------------

### Technology and Software to be used:

• Google Collab
• Git Hub
• Tableau

----------------------------------------------

### Aims and Goals for this case study

o The main agenda of this case study is to analyze the factors that might cause loan 
  defaulting.

o Analyze which type of clients are more prone to repay the loans disbursed by the 
  bank.

o Analyzing and understanding the driving factors or driver variables behind loan 
  defaulting

o Analyze the types of loans that make most of the defaults.

o Analyzing the current applicants using their previous applications data

-------------------------------------------------

### Conclusions

• In the distribution of income range the female count is higher than male, 
  and the income range from 100000 to 200000 is having more number of 
  credits, and females are more than male in having credits in this range. 

• In the distribution of income type graph, income type 
  ‘working’,’commercial associate’, and ‘State servant’ have higher credits 
  than others, and less number of credits are for income type
  ‘students’,’pensioner’,’Businessman’ and ‘maternity leave’. 

• In the distribution of contract type graph, the contract type ‘cash loans’
  is having higher number of credits than ‘Revolving loans’.

• In the distributiuon of organization type for target 0 graph, the clients 
  which have applied for credits are from most of the organizations type 
  ‘business entity type 3’, Self employed’, ‘other’,’medicine’ and 
  ‘government’, and less clients are from industry type 8, type 6, type 10, 
  religion and trade type 5, type 4.

• For correlation for target 0 graph, credit amount is inversely 
  proportional to the date of birth, which means credit amount is higher 
  for low-age and vice verse. Credit amount is inversely proportional to 
  the number of children client have, means credit amount is higher for 
  less children count client have and vice-versa. Income amount id 
  inversely proportional to the number of children client have, means 
  more income for less children client have and vice-versa. Less children 
  client have in densely populated area. Credit amount is higher to 
  densely populated area. The income is also higher in densely populated 
  area.

• For correlation of target 1 graph, The client’s permanent address does 
  not match contact address are having less children and vice-versa. The 
  clients permanent address does not match work address are having les 
  children and vice-versa

----------------------------------------------------

### Sugestions:

1. Banks should focus more on contract type ‘Student’ ,’pensioner’ and 
  ‘Businessman’ with housing ‘type other than ‘Co-op apartment’ for successful 
   payments.

2. Banks should focus less on income type ‘Working’ as they are having most 
   number of unsuccessful payments.

3. Also with loan purpose ‘Repair’ is having higher number of unsuccessful 
   payments on time.

4. Get as much as clients from housing type ‘With parents’ as they are having 
   least number of unsuccessful payments.

-------------------------------------------------------

### References:

Dataset link - https://www.kaggle.com/datasets/venkatasubramanian/credit-eda-case-study?resource=download&select=previous_application.csv

Project GitHub link:  https://github.com/NIKHILNARSIPALLI/Credit-EDA-Case-Study

---------------------------------------------------------

### End of the report
