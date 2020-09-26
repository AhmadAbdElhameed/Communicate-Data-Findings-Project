# Communicate-Data-Findings-Project
Prosper Loan Dataset Analysis 

Dataset
The data consists of information regarding 113,937 loans granted by Prosper, including Prosper score or borrower risk, 
listing category or loan type, employment status, number of current credit lines, 
number of open revolving accounts, debt to income ratio, and original loan amount.
The dataset can be found in Udacity's repository :https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv
with feature documentation available :https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0
you will need to see this for removing code from slides : https://stackoverflow.com/questions/51549048/how-to-convert-jupyter-notebook-ipython-to-slideshow-not-using-command-line


Finding :
In the exploration, I found several interesting relationships between the dependent variable (LoanSatus) and these features:
 income range or original loan amount, and borrower APR . I choose to present the loan statuses distribution and 
its relationship with the variables listed above.

Regarding the relationship between loan status and borrower APR, with a high APR increase the chance for Defaluted or Charged off.
Additionally, employed borrowers had the highest amount of charged-off loans that borrowers under the remaining employment status 
and the highest loan amount increase chance to Defaluted or Charged off,the most Defaulted with borrowers 
have income more than +100,000 dollar,which was the opposite of my expectations .


Key Insights for Presentation :

1- The distribution of APR looks multimodal. A small peak centered almost at 0.06, a large peak centered at 0.18. 
There is also a small peak centered 0.31 and 0.33. Additionally, there is a very shape peak between 0.36 and 0.38. 
Only very few loans have APR greater than 0.4.

2- Distribution has unimodal peak around 0.2 with unusual peak around 0.35 which indicates most people prefer 1:3 ratio 
of debt to Income which is a good thing.
 
3- The range of APR decrease with the increase of loan amount, the borrower APR decrease with increase of loan amount

4- The highest loans amount have the highest risk to Defaluted, they have the same median but Defaluted have the bigger range.

5- The income rate distribution is analyzed to know the average income rate of listings. the plot shows that the loans fall when the 
income less than 50000 $

6- I see when the interest rate for the loan is high,the chance for chargedOff or Defaulted is increased event with the people with high income range.

7-As we see the highest loan amount increase chance to Defaluted ,the most Defaulted with borrowers have income more than +100,000 dollar 

