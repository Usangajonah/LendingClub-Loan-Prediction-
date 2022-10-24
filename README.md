# LOAN PREDICTION USING DECISION TREE AND RANDOM FOREST
![loan1](https://user-images.githubusercontent.com/109528502/197563284-4251a3d1-2dad-41f1-accc-6447f9dfb1d2.jpeg)

## ABOUT PROJECT
 For this project we will be exploring publicly available data from "LendingClub.com". Lending Club connects people who need money (borrowers) with people who have money (investors). Hopefully, as an investor you would want to invest in people who showed a profile of having a high probability of paying you back. We will try to create a model that will help predict this.

Lending club had a very interesting year in 2016, so let's check out some of their data and keep the context in mind. This data is from before they even went public.

## PYTHON LIBRARIES IMPORTATIONS
A library which is a collection of functions that we include in our python code and called as necessary. With libraries, pre-existing functions can be imported which will efficiently expand the code performance. For this project, I will import the following libraries pandas, numpy, matplotlib, seaborn, sklearn e.t.c. Then set %matplotlib inline since I'm using a Jupiter notebook

## GETTING DATA
We will use lending data from 2007-2010 and be trying to classify and predict whether or not the borrower paid back their loan in full. You can download the data from [here]. 

### Here are what the columns represent:
* credit.policy: 1 if the customer meets the credit underwriting criteria of       LendingClub.com , and 0 otherwise.
* purpose: The purpose of the loan (takes values "credit_card", "debt_consolidation", " educational", "major_purchase", "small_business", and "all_other").
* int.rate: The interest rate of the loan, as a proportion (a rate of 11% would be stored as 0. 11). Borrowers judged by LendingClub.com to be more risky are assigned higher interest rates.
* installment: The monthly installments owed by the borrower if the loan is funded. 
* log.annual.inc: The natural log of the self-reported annual income of the borrower.
* dti: The debt-to-income ratio of the borrower (amount of debt divided by annual income).
* fico: The FICO credit score of the borrower. 
* days.with.cr.line: The number of days the borrower has had a credit line. 
* revol.bal: The borrower's revolving balance (amount unpaid at the end of the credit card billing cycle).
* revol.util: The borrower's revolving line utilization rate (the amount of the credit line used relative to total credit available).
* inq.last.6mths: The borrower's number of inquiries by creditors in the last 6 months. 
* delinq.2yrs: The number of times the borrower had been 30+ days past due on a payment in the past 2 years.
* pub.rec: The borrower's number of derogatory public records (bankruptcy filings, tax liens, or judgments).


You can read the full documentation [here]()

other relevant links:

[Twitter](https://twitter.com/Jobenofficial?t=F06epko9lD5L8p3-VkkT9w&s=09)

[LinkedIn](https://www.linkedin.com/in/jonahusanga)

[Medium](https://usangajonah.medium.com/)
