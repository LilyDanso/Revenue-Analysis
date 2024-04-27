## EDUCATIVE ONLINE COURSES ANALYSIS

### Table of Content
- [Project overview](Project-overview)
- [Data Source](Data-Source)
- [Tools](Tools)
- [Data Cleaning/Preparation](Data-Cleaning/Preparation)
- [Exploratory Data Analysis](Exploratory-Data-Analysis)
- [Data Analysis](Data-Analysis)
- [Result/Findings](Result/Findings)
- [Recommendations](Recommendations)



#### Project overview
This data analysis project aims to provide insights into the performance of courses offered by Educative- an Education Tech Company
and identify areas with growth potential, and come up with a data-driven strategy to increase next quarter's revenue.


![Screenshot (9)](https://github.com/LilyDanso/Revenue-Analysis/assets/157654354/4da5630b-987f-4a61-b980-11b1beb0a4eb)



#### Data Source
Educative Courses Data: The primary datasets used for this analysis are Data_Sheet_Educative_Courses_-_Business_Courses.xlsx , Data_Sheet_Educative_Courses_-_Design_Courses.xlsx, Data_Sheet_Educative_Courses_-_Music_Courses.xlsx and Data_Sheet_Educative_Courses_-_Web_Development.xlsx which contains the verious courses offered by Educative,the number of subscription, prices, Level, number of lecture hours, Ratings, etc.

#### Tools
- Excel  - Data Cleaning and Analysis
- Power BI - Creating reports and dashboard.


#### Data Cleaning/Preparation
  In the initial data preparation phase, I performed the following tasks:
  1. Data loading and inspection.
  2. Handling missing values.
  3. Handling duplicate values.
  4. Ensured each column has proper headers.


#### Exploratory Data Analysis
 1. What is the total number of subscriptions across the four main subjects?
 2. what is the total revenue per Subject over the 6 years?
 3. What is the total revenue per Subject at each level?
 4. what is the average price per subject and at each level?
 5. what is the performance of each subject?
 6. what is the revenue and subscription trend over 6 years?


![image](https://github.com/LilyDanso/Revenue-Analysis/assets/157654354/dd8df25e-9a26-47f1-a47a-fff822d4d09f)


![Screenshot (10)](https://github.com/LilyDanso/Revenue-Analysis/assets/157654354/d51bccd4-19b0-4545-bbb5-910f3a58220f)



#### Data Analysis
``` Excel
=VLOOKUP(A2,'Educative Data_cleaned'!A2:N21,{4,11},FALSE)

sort(z to A)
```
created ‘published_date’ ,‘free_or_paid‘ column.

Used pivot table for data summarization and created the following charts:
- Total number of subscribers for each subject (Pie Chart)
- Average subscriber count per subject (Bar Chart)
- Average cost per subject at each level (Bar Chart)
- Average content duration per subject (Bar Chart)
- Average rating per subject for each level (Column Chart)



#### Result/Findings
The result of this analysis are summarized as follows:
- Across the four subjects, Web development have the highest number of subscriptions of 7.8M out of a total 12M with the highest income revenue over the period of 6 years
- Paid courses have the highest number of subscription indicating that pricing does not affect subscription rate.
- The number of subscription have a direct effect on revenue.i.e the higher the subscription, the higher the Revenue.
- The number of subscription reduced from the 1st quarter of 2016 to the 3rd quarter of 2017 resulting in a drastic decline in revenue. This was as a result of lack of awareness about 
  the courses due to ineffective marketing strategies.



#### Recommendations

Based on the findings of this this analysis, the following recomendations where given;
1. There should be an Allocation of additional funds for comprehensive market research to 
understand evolving trends and learner preferences. Tailoring marketing strategies to 
effectively communicate the value of courses, addressing the identified lack of 
awareness.
2. Management should conduct a pricing analysis considering the findings that pricing does 
not have a negative effect on course subscriptions. Optimize pricing strategies based on 
market demand, course popularity, and learner feedback to maximize revenue potential particularly focusing on Web development courses.


