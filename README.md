 
#     2014 2015 estimated Government Project finance allocations to National Government Ministries
##     <span style="color:blue">Installation</span>.
The code was written on [Google Colab](https://colab.research.google.com/notebooks/intro.ipynb#recent=true), 
however you can preview it attached in this repository as a jupyter notebook.
##    What is the Project all about ? 
In this project we aim to check andd see the governments spending and how they allocate their money to the 
ministries we will find out which ministry are mostly funnded what is the highest donation / grant / loan 
given, and how they allocate it. 
## Assumptions 
We will assume that the data is accurate and true. 
## The datasets 
We will be working with one dataset 
[2014 2015 estimated Government Project finance allocations to National Government Ministries](https://www.opendata.go.ke/datasets/2014-2015-estimated-government-project-finance-allocations-to-national-government-ministries), this dataset shows the ministry, the total budget,
loan budget, budget supported by donors, and the total project cost. 
## The cleaning of the datasets 
We will be using pandas to clean the data, as it is easy to use and works well. 
We renamed the columns to easier and more accessible names, in addition to this we converted the ministry 
column to lower case for uniformity and accesibility purposes. 
We then proceeded to drop all the duplicated columns. 
## The analysis of the data 
We will be answering the following questions :
   1. How many ministries are there? 
     24
   2. Which ministry had the most funding
      State department of infrastructure 
   3. Which mode of funding has the most monetary value ? 
       Total_Budget_Estimate- 87753743927
       Total_Loan_Budget- 374828343219
       Total_Grant_Budget- 111348673071                                            
       Total_Budget_Supported__by_Donors_KES- 486176671965
       By observation we can see that money donated by donors makes up most of the budget.
   4. Which mode of funding is used the least
