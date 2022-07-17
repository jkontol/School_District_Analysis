# The Analysis of a School District and How Charter Schools Drive Improvement

##Purpose
For this project we will analyze the performance of a school district. Student data will be merged with school data to analyze performance by student, by school, and by district. Fifteen schools and 39,190 schools will be assessed based on math performance and reading performance.

##The Process

Before diving into the analysis it is important to be working with a clean dataset without missing chunks of information. Once we remove any formatting errors, and fill in any missing data we can begin looking into how this district is perfoming.
![identify_missing_data](https://user-images.githubusercontent.com/107225004/179381316-57562aee-c24a-42bb-96f2-3c0d3fb8548a.png)

By merging the data together we can get a better view of how each student is performing, and then roll up those results to grade level, school, and then district.


![merge_data](https://user-images.githubusercontent.com/107225004/179381322-60a3d6a7-3836-42ab-9f3b-da4d0b46b573.png)

Thomas High School was identified as having data issues. Using Pandas it is easy to calculate the grades, and identify passing students. 
![Thomas_High_School_Passing_Data](https://user-images.githubusercontent.com/107225004/179381326-603d8992-1e31-425e-93f4-3e4db2bd7c5a.png)
Once the data is calculated and validated it can then be placed into the existing dataset using the loc method.
![Replace_Incorrect_Data](https://user-images.githubusercontent.com/107225004/179381354-30a6466b-abcc-4ad2-a8f8-c1069da4e3e5.png)

##The Analysis

Utilizing Pandas gives the ability to dig deep into the data and look at many angles. The first view is looking at scores by grade. This can help schools identify if a particular curriculum is not effective in either math or reading. 

![Math_scores_by_grade](https://user-images.githubusercontent.com/107225004/179381424-0b8003f0-e7f0-405e-b714-e19754a1da71.png)

School level data also gives a view of overall district performance to identify any problem areas. 
![summary_by_school](https://user-images.githubusercontent.com/107225004/179381441-3348dcb1-447c-43ec-8132-67f180569170.png)

Another factor that can greatly impact school performance is the budget. Do higher budget schools outperform their lower budget counterparts. Wilson Hight School is a high performing school with a low budget however Hernandez High School is performing poorly despite having a larger budget per student. 

Perhaps adding in school size can better show the impact of the budget on a school. 
![Spending_and_school_size](https://user-images.githubusercontent.com/107225004/179381536-4225078c-fe3c-4ee0-b566-04e2a5cac7d4.png)

Helping the district identify the Top Five Performers can help give a model of what makes a good school. How can they take what is working at these schools and apply it to some of the lower performing school. 
![Top_Five_Schools](https://user-images.githubusercontent.com/107225004/179381553-ceaf81bf-052e-4c78-bd93-2c3b280af7c5.png)

##Recommendations

Looking at the schools individually is an important step to finding small ways to make improvements. Each school can identify where their holes lie, and work on filling them. 
![summary_by_school](https://user-images.githubusercontent.com/107225004/179381636-6a6ee47a-9f04-4be4-b66c-c91951ea6377.png)

The most telling view in this analysis is District Schools vs. Charter Schools. Charter schools outperform District schools by a large margin. It is recommended that steps be taken to identify what is driving that gap, and how it can be closed.  
![School_Types](https://user-images.githubusercontent.com/107225004/179381572-6129ba5c-bb11-4a9a-a200-bb810eeea275.png)

