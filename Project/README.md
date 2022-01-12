# Data-Engineering-Milestone1
This is a project for our data engineering and visualization course, this repo is for grading of milestone 1.  
&nbsp;
## Project goals and motivation
The goal of this project is to apply our data engineering and visualization methods to [this dataset](https://www.kaggle.com/heesoo37/120-years-of-olympic-history-athletes-and-results?select=athlete_events.csv), the goal of this milestone is to explore our data, clean our data (find missing values), plotting our data.



&nbsp;
## Dataset Overview
- This is a historical dataset on the modern Olympic Games, including all the Games from Athens 1896 to Rio 2016.
- The dataset used was imported from [this website](www.sports-reference.com) in May 2018.
- The file athlete_events.csv contains 271116 rows and 15 columns. Each row corresponds to an individual athlete competing in an individual Olympic event (athlete-events). The columns are:
    1. ID -  <font size="2"> Unique number for each athlete</font>
    2. Name - <font size="2"> Athlete's name</font>
    3. Sex - <font size="2"> Male or Female</font>
    4. Age - <font size="2"> Integer</font>
    5. Height - <font size="2"> In centimeters</font>
    6. Weight - <font size="2"> In kilograms</font>
    7. Team - <font size="2"> Team name</font>
    8. NOC - <font size="2"> National Olympic Committee 3-letter code</font>
    9. Games - <font size="2"> Year and season</font>
    10. Year - <font size="2"> Integer</font>
    11. Season - <font size="2">Summer or Winter</font>
    12. City - <font size="2"> Host city</font>
    13. Sport - <font size="2"> String</font>
    14. Event - <font size="2"> String</font>
    15. Medal - <font size="2"> Gold, Silver, Bronze, or NA</font>
> **Additional note:**  the Winter and Summer Games were held in the same year up until 1992. After that, they staggered them such that Winter Games occur on a four year cycle starting with 1994, then Summer in 1996, then Winter in 1998, and so on. A common mistake people make when analyzing this data is to assume that the Summer and Winter Games have always been staggered.
## Steps:
1. Reading the csv file and using the info() and describe() functions to explore the data.
2. Searching for missing values using isnull() and sum() functions.
3. Cleaning the data by finding plausible values for missing values.
4. Checking the dataset after filling the missing values and observing the difference in the describe() function.
5. Showing non-trivial information and insights using different visualisation methods. 
7. Integrating new datasets and updating records for consistency of data.
6. Handling outliers for weight, height, age and NOC and visualizing the data before and after handling.
7. Data Analysis visualizing the newly added research questions.

## Data research questions
- What is the distribution percentage between males vs females? 
- What is the distribution of age among the athletes?
- What is the top 10 countries with different medals obtained?
- How the participation of gender changes over time?
- What is the count of male olympic winners throughout the years?
- What is the count of female olympic winners throughout the years?
- What is the BMI Distribution of gold medalists volleyball players compared to basketball players? 
- What is the distribution of olympic athletes according to their weight status?