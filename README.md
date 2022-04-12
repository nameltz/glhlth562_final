# glhlth562_final

---

#### Introduction

In this project, I examined the relationship between student debt and state spending on higher education from 2004-2019. 

#### Background

Student debt in the United States has grown tremendously throughout recent decades. What was once a fairly rare occurrance is now a common one: 42 million Americans — about 1 in every 8 — have student loans. That growth has been driven by a range of factors, including an increase in the number of borrowers, a higher average amount borrowed, a low rate of repayment, and changes in the types of colleges attended. Today, 75% of student loan borrowers took out loans to go to two- or four-year colleges — representing about 50% of outstanding debt. 25% of student loan borrowers took out loans for grad school — representing the other 50% of outstanding debt. [source](https://www.brookings.edu/policy2020/votervital/who-owes-all-that-student-debt-and-whod-benefit-if-it-were-forgiven/)

During the same period, the state largely withdrew from the New Deal-era investments public education and social services, tightening eligibility and reducing benefits for programs including unemployment insurance, Temporary Assistance for Needy Families, food stamps and Medicaid. 

#### Research Question

What is the relationship between per-capita student debt and investments in higher education at the state level from 2004-2019? 

#### Data

To answer my question, I analyzed state-level household debt statistics from the Federal Reserve Bank of New York and Census Bureau state and local government expenditure data compiled by the Urban-Brookings Tax Policy Center.  
The data on debt comes from the New York Fed Consumer Credit Panel, a  longitudinal database with detailed information on consumer debt and credit. The panel is constructed from a nationally representative random sample of Equifax credit report data to track individuals’ and households’ access to and use of credit on a quarterly basis. It includes the Q4 `per-capita debt` and `delinquency rates` by `state` for `student loan` debt.
[link to data](https://www.newyorkfed.org/microeconomics/hhdc/background.html)

The data on state and local government expenditures on `Higher Education` came from the Census Bureau's Annual Survey of State and Local Government Finances. Per-capita spending is calculated using American Community Survey 1-year population estimates for each state. 
[link to data](https://www.taxpolicycenter.org/statistics/state-and-local-general-expenditures-capita)

My initial plan was to analyze the relationship between household debt and investments in government services more broadly, but the amount of data was overwhelming. I decided to focus on student debt and higher education spending because the amount of student debt in the U.S. has increased dramatically in recent decades and **tripled** during the study period of 2004 to 2019. 

#### Methods

I used exploratory data analysis to answer my research question. 

First I adjusted all student loan and state spending data to 2019$ in order to analyze trends over time. 

I looked at the aggregate trends across the United States to confirm that both state level spending on higher education per capita has decreased over time and student debt per capita has increased over time.

I then broke it down by state to see if there are differences between states. 

I built a dashboard to visualize the changes in student debt and state spending over higher education over time, as well as student loan delinquency rates which indicate if individuals are struggling to pay back their student loans. 

#### Findings 

State spending on higher education per capita has decreased in real dollars during the study period. Student loans per capita have also increased per capita during the study period.  

There are several states which are among the 10 most indebted per capita and the 10 lowest spenders per capita: Georgia, Massachussetts, New Jersey, New York, Pennsylvania, and South Dakota. 

There is a positive relationship between state spending on higher education and student loan debt, which means a great deal more sohpisticated analysis needs to be done to understand the mechanisms driving student loan debt. 

#### Limitations 

There are a number of limitations to the study.

First is the short time frame: it may take a longer period of time for decisions about education spending to influence student loan burdens. 

There are also limitations associated with the data: per capita spending is an incomplete metric as it doesn’t provide information about state demographics, policy decisions, or the choices residents make. It is not clear whether 

Spending on higher education is often driven by the number of students in public universities. The per capita nature of the data masks this relationship. This may be the reason for the positive relationship between per capita spending on higher education and student loans: more spending and more student loans mean more individuals are attending public universities in the state. 




