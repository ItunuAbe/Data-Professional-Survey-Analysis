<h2>**Analysis report and findings of Data Professional dataset**</h2>
Data Overview
 The dataset contains survey responses from data professionals in different countries and industries. This analysis aims to explore trends in career switch to tech, identify priorities, and what to look out for as a data professional. The dataset consists of 28 columns and 630 records.
Data Wrangling(cleaning) Process:
The dataset was downloaded in Excel format, it was then uploaded into power query for cleaning. The steps are:
1.	Removed columns with null values. 
2.	Standardized the following columns by merging all job roles that appear under “Others (Please Specify) to make the analysis more accurate. I use the Split column menu, choosing the custom delimiter.
•	Which Title Best Fits Your Current Role?
•	Favorite Programming Language?
•	What Industry do you work in?
•	Which Country do you live in?
3.	To derive a calculated column from the Current Yearly Salary column, I split the column into two using the Split Column menu, choosing the Digit to Non-Digit Option to break up the numbers. Then I used the Replace Value menu to Find and Replace ‘’K” and “-“ with an empty cell.
4.	The data type of the newly created columns was changed from Text to Whole Number to allow calculations.
5.	Under the Add Column Tab, I use the Custom Column menu to create a calculated column (Average Salary) using Formular.
6.	Finally, the data was loaded into Power BI for analysis.
Exploratory Data Analysis
In the phase I explored to understand the patterns and trends within the dataset to derive meaningful insights, I focused on various aspects such as gender and career switch percentage, average salary of different classes of data professionals, favorite programming language, happiness level, and top priority for a job.
Insights
I visualized gender and career change percentages using doughnut chart, of which 74% of the population were male and 59% of the survey takers switched careers into Data. 
The average salary was visualized using a bar chart, obviously showing that the higher the level of education, the higher the salary. Also, data scientists are shown at the top of the chart for the highest paid while database developers earn an average of $33,000 yearly.
Python won the most-used programming language used by the data professional, followed by R.
43% (269) of the population finds it neither easy nor difficult to break into Data, 25% (156) finds it difficult, 21% (134) finds it easy, 7% finds it very difficult and 4% finds it very easy.
Various level of Happiness was visualized using a gauge chart, happiness with salary is below the average of 5, showing 4.3, meaning most people are not happy with their current salary. Happiness with work-life balance and learning new things is a bit higher than the average.
The Top priority when searching for a new job for 47% of the population is a better salary, followed by Remote work and Good Work-Life Balance.

Conclusion
If you are thinking of switching career to data, I recommend learning Python as a programming language. Also, do not stop expanding your knowledge base, the analysis shows that data scientists and PhD education level earn a lot more. Gender is not a barrier!


