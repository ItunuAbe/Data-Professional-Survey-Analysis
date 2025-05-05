## Data Professional Survey Response Analysis.

### Data Overview
 The dataset contains survey responses from data professionals in different countries and industries. This analysis aims to explore trends in career switch to tech, identify priorities, and what to look out for as a data professional. The dataset consists of 28 columns and 630 records.
 
### Data Wrangling(cleaning) Process:

The dataset was downloaded in Excel format, and then uploaded to power query for cleaning. The steps are:
#### 1.	Removed columns with null values.

![Screenshot (53)](https://github.com/ItunuAbe/Data-Professional-Survey-Analysis/assets/110028869/89e9206e-e9e9-42cd-a361-7a99b7cc9529)

#### 2.	Standardized the following columns by merging all job roles that appear under “Others (Please Specify) to make the analysis more accurate. I use the Split column menu, choosing the custom delimiter.
•	Which Title Best Fits Your Current Role?
•	Favorite Programming Language?
•	What Industry do you work in?
•	Which Country do you live in?

![Screenshot (54)](https://github.com/ItunuAbe/Data-Professional-Survey-Analysis/assets/110028869/081ddd12-690c-4c15-b516-912c1f38517c)

![Screenshot (55)](https://github.com/ItunuAbe/Data-Professional-Survey-Analysis/assets/110028869/a47ad8a2-500b-4317-89c8-5d6646ddf2c2)

![Screenshot (56)](https://github.com/ItunuAbe/Data-Professional-Survey-Analysis/assets/110028869/ed94c08b-bfc5-4f77-a2ea-4206f915814f)

#### 3.	To derive a calculated column from the Current Yearly Salary column, I split the column into two using the Split Column menu, choosing the Digit to Non-Digit Option to break up the numbers. Then I used the Replace Value menu to Find and Replace ‘’K” and “-“ with an empty cell.

![Screenshot (57)](https://github.com/ItunuAbe/Data-Professional-Survey-Analysis/assets/110028869/b9be0f28-d931-45ff-bf85-ae1f9469835c)

![Screenshot (58)](https://github.com/ItunuAbe/Data-Professional-Survey-Analysis/assets/110028869/77ec14c1-0b56-4738-b802-05f4e4c27663)

![Screenshot (59)](https://github.com/ItunuAbe/Data-Professional-Survey-Analysis/assets/110028869/2addb171-27af-4b49-b3d0-da5675f0d90b)
   
#### 4.	The data type of the newly created columns was changed from Text to Whole Number to allow calculations.

![Screenshot (60)](https://github.com/ItunuAbe/Data-Professional-Survey-Analysis/assets/110028869/e5809eaa-76b6-434a-b057-dc8c7030fa50)

#### 5.	Under the Add Column Tab, I use the Custom Column menu to create a calculated column (Average Salary) using Formular.

![Screenshot (61)](https://github.com/ItunuAbe/Data-Professional-Survey-Analysis/assets/110028869/226638d0-74de-47f7-a6c0-861eeee406cf)
  
#### 6.	Finally, the data was loaded into Power BI for analysis.

## Exploratory Data Analysis

In my exploratory data analysis phase, I focused on identifying patterns and insights related to career paths, compensation, and preferences within the data profession. I examined key variables such as gender distribution, career switch trends, salary ranges, preferred programming languages, happiness levels, and job search priorities.

## Insights

![Screenshot (63)b](https://github.com/ItunuAbe/Data-Professional-Survey-Analysis/assets/110028869/fdb2371a-8231-4c00-a584-c89386be2b37)


![Screenshot (64)b](https://github.com/ItunuAbe/Data-Professional-Survey-Analysis/assets/110028869/cd288f3d-3a6b-481c-bb7f-fc7d6cfdc0b6)

#### In my exploratory data analysis phase, I focused on identifying patterns and insights related to career paths, compensation, and preferences within the data profession. I examined key variables such as gender distribution, career switch trends, salary ranges, preferred programming languages, happiness levels, and job search priorities.

#### Using a doughnut chart, I visualized that 74% of respondents were male, and 59% had transitioned into a data-related role from a different career, highlighting the field’s accessibility. Salary analysis through bar charts revealed a positive correlation between education level and income, with Data Scientists leading the earnings chart, while Database Developers earned the least, averaging $33,000/year.

#### Programming preferences showed Python as the most widely used language, followed by R.

#### Regarding entry into the data field, 43% found it neither easy nor difficult, while only 4% found it very easy. Gauge charts illustrated varying happiness levels — happiness with salary rated at 4.3/10, indicating general dissatisfaction, whereas satisfaction with work-life balance and learning opportunities scored slightly above average.

#### When exploring job priorities, 47% of professionals ranked better salary as their top motivator, followed by the desire for remote work and work-life balance.



## Conclusion

If you are thinking of switching career to data, I recommend learning Python as a programming language. Also, do not stop expanding your knowledge base, the analysis shows that data scientists and PhD education level earn a lot more. Gender is not a barrier!


