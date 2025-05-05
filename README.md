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

## 📊 Exploratory Data Insights: Data Professionals Survey

In my exploratory data analysis phase, I focused on identifying patterns and insights related to career paths, compensation, and preferences within the data profession. I examined key variables such as gender distribution, career switch trends, salary ranges, preferred programming languages, happiness levels, and job search priorities.



![Screenshot (63)b](https://github.com/ItunuAbe/Data-Professional-Survey-Analysis/assets/110028869/fdb2371a-8231-4c00-a584-c89386be2b37)


![Screenshot (64)b](https://github.com/ItunuAbe/Data-Professional-Survey-Analysis/assets/110028869/cd288f3d-3a6b-481c-bb7f-fc7d6cfdc0b6)


#### In my exploratory data analysis phase, I focused on identifying patterns and insights related to career paths, compensation, and preferences within the data profession. I examined key variables such as gender distribution, career switch trends, salary ranges, preferred programming languages, happiness levels, and job search priorities.

#### Using a doughnut chart, I visualized that 74% of respondents were male, and 59% had transitioned into a data-related role from a different career. The data professional landscape, as represented by this survey, is predominantly male, with a significant proportion of individuals having transitioned into the field from other careers. This highlights the growing appeal and accessibility of data-related roles.

#### Salary analysis through bar charts revealed a positive correlation between education level and income, with Data Scientists leading the earnings chart, while Database Developers earned the least, averaging $33,000/year.

#### Python stands out as the most favored programming language among data professionals, indicating its central role in the field, closely followed by R. This information is crucial for understanding the prevalent skill sets and potentially future technology adoption trends.

#### Regarding entry into the data field, 43% found it neither easy nor difficult, while only 4% found it very easy. The experience of breaking into the data field suggests a moderate barrier to entry. However, a significant portion does find it challenging, indicating areas where potential support or resources might be beneficial.

#### Gauge charts illustrated varying happiness levels — happiness with salary rated at 4.3/10, indicating general dissatisfaction, whereas satisfaction with work-life balance and learning opportunities scored slightly above average. 

#### When exploring job priorities, 47% of professionals ranked better salary as their top motivator, followed by the desire for remote work and work-life balance. Job satisfaction, particularly concerning salary, appears to be a point of concern for many data professionals, as indicated by the below-average happiness score. In contrast, aspects like work-life balance and opportunities for learning new things contribute to higher levels of happiness.

#### Finally, when seeking new employment, a better salary is the paramount priority for the majority of data professionals, followed by the desire for remote work options and a good work-life balance. This highlights the key motivators and priorities driving career decisions within this sector.

## 🔍 Conclusion & Recommendation
This analysis reveals critical insights into the data industry workforce. While the field attracts a large percentage of career switchers and offers strong salary growth with education, challenges remain in work satisfaction—particularly around compensation. The dominance of Python, combined with a demand for remote flexibility and work-life balance, signals evolving industry expectations. These findings highlight the importance of aligning organizational offerings with the evolving priorities of data professionals to attract and retain top talent.

If you’re considering a career switch into data, start by learning Python—it’s the most widely used language among professionals. Keep expanding your knowledge, as advanced education (especially PhDs) correlates strongly with higher earnings. And remember, gender is not a barrier—opportunity in data is open to all.



