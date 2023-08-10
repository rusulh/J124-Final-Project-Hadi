<h1> J 124 Final Project: Pregnancies, Births and Abortions in the United States, 1973–2017

<h2> By Rusul Hadi</h2>
<h2> Story Summary; Decades of Choice </h2>

In summary, my data analysis identified that over the past twenty-five years, pregnancy rates have experienced a decline among women aged 24 or younger. These observed patterns highlight distinct shifts in birth and abortion rates.
The trends at the state level largely align with national trends over time. However, notable geographic variations emerge: In 2017, pregnancy rates were notably higher among younger individuals in the South and Southwest regions, compared to other areas. These trends led me to investigate the total pregnancy count in each year among different group ages, as well as how these rates varied. 

<h2>Sourcing</h2>

I conducted an examination of the [Pregnancies, Births and Abortions Rates in the United States](https://www.guttmacher.org/report/pregnancies-births-abortions-in-united-states-1973-2017) which was obtained from the Guttmacher Institute. The crux of my investigation pertains to the statistical counts of pregnancies including births, abortions, and fetal losses from 1973 to 2017.

### Interview Contacts
1) Isaac Maddow-Zimet, The Guttmacher Institute 
	* Email: imaddowzimet@guttmacher.org
	* Phone Number: (212)248-1111 
	* Isaac Maddow-Zimet became a part of the Guttmacher Institute in 2010, and he has held his present role since 2017. His primary research focuses on topics such as unintended pregnancy, adolescent sexual health and conduct, American sex education, and the issue of unsafe abortion in nations where abortion is prohibited or significantly regulated. I want to interview him and ask to further questions regarding the abortion rates in the United States and what are the causes of the high rates. 
2) Kathryn Kost, The Guttmacher Institute
	* Email: kkost@guttmacher.org
	* Phone Number: (212)248-1111
	* Within the Guttmacher Institute, Dr. Kost's research encompasses a variety of subjects essential for comprehending reproductive behaviors and patterns within the United States. This includes examining sexual behavior trends, profiling abortion patients, investigating the health impacts of unintended pregnancies, and providing estimations related to contraceptive effectiveness. I want to ask how she investigates the health impacts and how she is able to prove estimations. 

### Additional Sources 

1) [Trends in Teen Pregnancy and Childbearing](https://opa.hhs.gov/adolescent-health/reproductive-health-and-teen-pregnancy/trends-teen-pregnancy-and-childbearing)
* This source provides the proportion of teen births and international comparison.
* This information can be used to identify additional trends among teen birth rate in the United States over the years

2) 

<h2> Data Visualizations

### 1) [Birth Rates in 2017](https://www.datawrapper.de/_/1AgeA/)
<img width="619" alt="Screen Shot 2023-08-09 at 12 00 51 PM" src="https://github.com/rusulh/J124-Final-Project-Hadi/assets/140214843/2d0ce983-70e2-4d0b-822d-924de251ff17">

## Data Analysis Process
I initiated my analysis by performing data cleaning as the initial step. Upon examination, the data displayed a predominantly normalized state, necessitating minimal refinement.


Scope of analysis: in the context of a dataset pertains to the specific boundaries and parameters that outline the extent and focus of the study conducted on the dataset
1. Create a pivot table to show the total pregnancy count by each year and age group 15-17?
2. What was the birth rate for women aged 30-34 in California in 2017?
3. Calculate the average birth rate for women aged 40-44 across all states in 2017?
4. Which age group had the highest pregnancy rate in the year 2000?
5. Using a pivot table, find the total number of pregnancies among (age 30-39) in the year 1980?

### Key Assumptions
* All questions were addressed solely using the provided dataset.
* The dataset covers a significant number of years to capture meaningful trends. The data for each age group is complete and representative. 
* Birth rates are calculated uniformly and consistently across all states. The dataset includes accurate and comprehensive birth rate data for all states in 2017.
* Birth rates are calculated using the same methodology for all age groups. The dataset provides accurate and complete birth rate data for all age groups in 2017. 

### Analysis
1. Create a pivot table to show the total pregnancy count by each year and age group 15-17?

First, I created a pivot table. In the pivot table I dragged the following fields to the respective areas:
Rows: Year
Values: Pregnancy Count for group age 15-17

<img width="127" alt="total pregnancy count by year   age group 15-17" src="https://github.com/rusulh/J124-Final-Project-Hadi/assets/140214843/264ed23f-1ef3-41ff-a45e-dabfd7caa77b">

> The total pregnancy count by each year and age group 15-17 is 2405.7

2. What was the birth rate for women aged 30-34 in California in 2017?

I filtered and sorted the data to focus on California, then I found the row corresponding to the age-group 30-34 and ientified the birth rate value in the corresponding cell for California and the age-group 30-34.

<img width="1056" alt="Screen Shot 2023-08-09 at 6 18 43 PM" src="https://github.com/rusulh/J124-Final-Project-Hadi/assets/140214843/ff85a6e0-2a90-4b66-81a3-4a3f79cf8003">

> The birth rate among women aged 30 to 40 in 2017 was recorded as 101.7

3. Calculate the average birth rate for women aged 15-17 across all states in 2017?

I filtered the data to focus on the age-group 15-17, then I clculated the sum of birth rates for women aged 40-44 across all states. I counted the number of states in the dataset, then divided the total sum of birth rates by the number of states to calculate the average birth rate for women aged 40-44. I used the avergae formula:

Average = Total Sum of Birth Rates / Number of States

<img width="1149" alt="Screen Shot 2023-08-09 at 6 36 22 PM" src="https://github.com/rusulh/J124-Final-Project-Hadi/assets/140214843/c7335039-d013-4572-8f7a-46561e9bcb78">

> The sum of birth rates for women aged 40-44 across all states is 401.3

then, I used the formula Average = Total Sum of Birth Rates / Number of States

<img width="159" alt="Screen Shot 2023-08-09 at 6 40 45 PM" src="https://github.com/rusulh/J124-Final-Project-Hadi/assets/140214843/9a2af4b9-c840-4795-8259-9d1daa7e9362">

> The average birth rate for women aged 15-17 across all states in 2017 equals to 7.9

4. Which age group had the highest pregnancy rate in the year 2000?

I filtered and sorted the data to focus on the year 2000, then I observed the highest pregnancy rate among the different ages. 

<img width="1186" alt="Screen Shot 2023-08-09 at 6 47 36 PM" src="https://github.com/rusulh/J124-Final-Project-Hadi/assets/140214843/cb749204-09f3-423d-8832-a079b7053419">

> The age group with the highest pregnancy rate in the year 2000 is 18-19.

5. Using a pivot table, find the total number of pregnancies among (age 30-39) in the year 1980?

I created a pivot table. In the pivot table I dragged the following fields to the respective areas:

Rows: Year 1980
Values (SUM): Pregnancy Count for group age 30-39

<img width="248" alt="Screen Shot 2023-08-09 at 7 17 02 PM" src="https://github.com/rusulh/J124-Final-Project-Hadi/assets/140214843/b0dba6ca-f29a-45bb-8a5b-4c118728761c">

> There were 34 pregnancies recorded for individuals aged 30 to 39 in the year 1980.



