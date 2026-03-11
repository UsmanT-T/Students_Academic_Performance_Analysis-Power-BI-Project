# Students’ Academic Performance Analysis – Power BI Project

## Table of Contents 

[Project Objective](#project-objective)

[Dataset Used](#Dataset-used)

[Key Performance Indicators](#Key-performance-indicators)  

[Slicers](#Slicers)

[Questions Answered by the Dashboard](#Questions-answered-by-the-dashboard)

[Process](#Process)

[DASHBOARDS](#Dashboards)

[Project Insights](#Project-insights)

[Conclusion](#Conclusion)

## Project Objective
The project aims to analyze students’ academic performance in Math, Reading, and Writing by examining how factors such as gender, parental level of education, test preparation, lunch type, and race/ethnicity influence their scores. It also seeks to identify patterns and disparities in performance to provide insights that can support data-driven educational decisions.

## Dataset Used
<a href="https://github.com/UsmanT-T/Employees_Analytical_Dashboard-Power-BI-Project/edit/main/README.md">Power BI data</a>

## Key Performance Indicators
This report was developed to answer the following key performance questions:
- Students Count.
-	Average Reading Score.
-	Average Math Score.
- Average Writing Score.
-	Overall Average. 

## Slicers
-	Gender
-	Test preparation course
-	Parental level of education

## Questions Answered by the Dashboard
The dashboards answer several key analytical questions regarding students’ academic performance:
1.	What is the overall academic performance of the students?
  - This is shown through the total number of students and the average scores in Math, Reading, and Writing.
2.	How does test preparation affect students’ academic performance?
  - The dashboard compares the average subject scores of students who completed the test preparation course with those who did not.
3.	Does parental level of education influence students’ academic outcomes?
  - It analyzes how students’ average scores vary across different parental education levels.
4.	Are there differences in academic performance between male and female students?
  - The dashboard compares gender-based performance across Math, Reading, and Writing.
5.	How does lunch type (an indicator of socioeconomic status) affect students’ scores?
  - It examines performance differences between students receiving standard lunch and free/reduced lunch.
6.	How does academic performance vary across race/ethnicity groups?
  - The dashboard evaluates subject score averages across different race/ethnicity categories.
7.	What is the distribution of students across key categories?
  - It shows how students are distributed based on test preparation participation and lunch type.

## Process
The following steps were carried out to build the report:
1.	Data Collection
- The dataset containing students’ academic performance and demographic information was obtained and imported into the analysis tool for further processing.
2.	Data Cleaning
- The dataset was reviewed to identify and handle missing values, remove duplicates, and correct inconsistencies in the data. Column names and data formats were standardized to ensure the dataset was accurate and ready for analysis.
3.	Data Preparation and Transformation
- Relevant variables were organized and prepared for analysis. New metrics such as average scores for Math, Reading, and Writing, as well as overall performance indicators, were calculated to support deeper insights.
4.	Exploratory Data Analysis (EDA)
- The dataset was explored to understand patterns, relationships, and trends. Comparisons were made across factors such as gender, parental level of education, test preparation course, lunch type, and race/ethnicity to determine how they influence students’ academic performance.
5.	Data Visualization
- Visual charts and graphs were created to present the findings clearly. These included bar charts, donut charts, and KPI indicators to highlight key metrics and comparisons across different categories.
6.	Dashboard Development
- An interactive dashboard was designed to bring all the visualizations together in a single view. Filters and slicers were added to allow users to interact with the data and analyze student performance across different variables.

## DASHBOARDS
![Students&#39; Academic Performance Dashboard](https://github.com/user-attachments/assets/17933a87-f968-493f-a959-2d18d9a14c4d)
![Students&#39; Academic Performance Dashboard 1](https://github.com/user-attachments/assets/b357123d-a6fb-4a36-9b8a-51f385706da0)

## Project Insights
The dashboard revealed the following insights:
1. Parental Level of Education Has the Strongest Positive Correlation with Performance
- The stacked bar chart “Parental Level of Education Influence Students’ Academic Outcomes” shows a clear downward trend: students whose parents hold a Master’s degree have the highest average scores across Reading, Writing, and Math (top of the chart), followed closely by Bachelor’s degree. Scores progressively decline through Associate’s, Some College, Some High School, and are lowest for High School parents. This indicates that higher parental education is associated with better student outcomes (likely due to greater academic support, resources, or expectations at home). The gap between the highest and lowest parental education groups is substantial roughly 15–20 points across subjects.
2. Completing the Test Preparation Course Significantly Boosts All Scores
- Both dashboards highlight the impact of test prep.
- The horizontal bar chart (second image) and pie chart (first image) show students who completed the course consistently score approximately 5–10 points higher in Math, Reading, and Writing than those who took “None.”
- The completed group’s bars reach approximately 68–72, while the “None” group hovers around 60–65. This demonstrates that structured preparation has a measurable, positive effect regardless of other demographics.
3. Lunch Type (Socioeconomic Proxy) Strongly Affects Performance
- The “Impact of Lunch Type to Students Performance” bar chart and accompanying pie chart reveal:
- Students with Standard lunch (64.5% of the sample) outperform those with Free/Reduced lunch (35.5%) by about 8–10 points across all three subjects.
- Standard lunch averages sit around 70–72, while Free/Reduced averages are in the low 60s. This pattern serves as a clear indicator of socioeconomic status influencing academic results (e.g., nutrition, stress, or home resources).
4. Gender Differences Follow Classic Subject Patterns
- The “Subject Performance between Genders” grouped bar chart shows:
- Females outperform males in Reading and Writing (females ~71–73, males ~65–67).
- Males have a slight edge in Math (males ~68, females ~63–64). Overall, females have a higher total average in language-based subjects, while the gender gap in math is smaller but favors males consistent with many standardized testing studies.
5. Race/Ethnicity Groups Show Noticeable Performance Variation
- The “Race/Ethnicity Group across Average Subjects” chart (first image) ranks the five groups:
- Group E has the highest averages across all subjects (top bars ~72–75).
- Performance declines steadily to Group A, which has the lowest scores (~62–65). Groups C, B, and D fall in between, with slight variations by subject. This highlights disparities that may correlate with other factors (parental education, test prep access, etc.).
6. Overall Statistics (Consistent Across Both Dashboards)
- Total students: 1,000
- Overall average score: 67.77
- Subject averages: Math: 66.09, Reading: 69.17, Writing: 68.05

## Conclusion   
The analysis of students’ academic performance reveals that several demographic and educational factors influence outcomes in Math, Reading, and Writing. Students who completed the test preparation course generally performed better than those who did not, indicating that additional academic support plays an important role in improving performance. The results also show noticeable differences in performance across gender, parental level of education, lunch type, and race or ethnicity groups. Students whose parents have higher levels of education and those with access to standard lunch tend to achieve higher average scores, suggesting that parental background and socioeconomic conditions may impact academic success. Overall, the project highlights the importance of supportive learning environments, access to educational resources, and targeted academic preparation in improving students’ performance. These insights can help educators and decision makers implement strategies that support students who may be at risk of lower academic outcomes.
