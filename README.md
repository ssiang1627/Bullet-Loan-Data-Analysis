## Loan Data [(kaggle)](https://www.kaggle.com/zhijinzhai/loandata)
## Overview
This data set includes customers who have paid off their loans, who have been past due and put into collection without paying back their loan and interests, and who have paid off only after they were put in collection. The financial product is a bullet loan that customers should pay off all of their loan debt in just one time by the end of the term, instead of an installment schedule. Of course, they could pay off earlier than their pay schedule.

## Data Description
- Loan_id : A unique loan number assigned to each loan customers
- loan_status : Whether a loan is paid off, in collection, new customer yet to payoff, or paid off after the collection efforts
- Principal : Basic principal loan amount at the origination
- terms : Can be weekly, biweekly, and monthly payoff schedule
- effective_date : When the loan got originated and took effects
- due_date : Since it’s one-time payoff schedule, each loan has one single due date
- paidoff_time : The actual time a customer pays off the loan
- pastdue_days : How many days a loan has been past due
- age, education, Gender : A customer’s basic demographic information
- paid_off_duration (added) : How many days it took for customer to pay loan off

## Objective
 1. To detect the customer behavior of this financial product
 2. Try to pridict whether the loan would be paid off or not

## Procedure
 1. EDA
 2. Data Cleaning
 3. Classification Models 
