# PostgreSQL-with-CMS-Data

This lab uses a subset of data from CMS’ 2010 Synthetic Medicare Beneficiary Claims. Two tables were created from medicare_2010_pop_data.csv and medicare_2010_payer_data.csv files. 


## Questions: 

### Q1
Find the average months of HMO coverage when the patient was reported to have cancer.

### Q2
Return the top five rows where the age of death is below the average age of death, ordered by id in ascending order.

### Q3
Find the total carrier reimbursements for every state, ordered by state in ascending order.

### Q4
Find out which state spends the most money on carrier reimbursements for depression. Return columns for the state and total carrier reimbursements spent on depression.

### Q5
Rank each state by their number of heart failure claims in proportion to their total claims, ordered by the proportion in descending order. Your query should return two columns.

### Q6
For everyone who is deceased, find their deviation in age from the average age of the deceased, in years and rounded to two decimal places. Return columns for id, sex, race, and deviation from the average age.

### Q7
Imagine you are doing a social study on the health of certain races in different regions of the country. For the race that most frequently submits claims in Texas, find the state which has the lowest frequency of claims from the same race. Return the percentage of carrier reimbursement cost that race is responsible for, the average number of HMO months of coverage, and average beneficiary responsibility for those two states and that race. Order by state in ascending order.

### Q8
Imagine you are an insurance company and you want to know which ailments are the most common, when they usually occur, and how much they cost. Return the percentage of claims to the nearest two decimal places for each ailment (Alzheimers, heart failure, etc.) along with the average age of patients in integer years and the average carrier reimbursement for those ailments.
