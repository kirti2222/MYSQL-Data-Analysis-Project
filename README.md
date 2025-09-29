# Project Title: The Impact of Lifestyle on Health: A MySQL Data Project
## Project Objective
To analyze the health and activity metrics to derive key insights and answer specific data-driven questions related to the health and lifestyle of individuals
## Dataset Used
https://github.com/kirti2222/MYSQL-Data-Analysis-Project/blob/main/healthcare_dataset.csv
## Project Questions
1. What is the average age of all the individuals in the dataset?
2. How many individuals are male and how many are females?
3. Find the minimum, maximum and average of daily steps, hours of sleep and calories intake?
4. Count the number of individuals who are smokers and non-smokers.
5. What is the average BMI of all the individuals?
6. Calculate the average daily steps of males and females seperately.
7. Determine the average hours of sleep for individuals categorized into age groups.
8. Find the average BMI of all the individualsbased on their daily steps activity levels.
9. Calculate the average heart rate of individuals who have heart disease and those who do not have.
10. Determine the percentage of smokers who have heart disease and non-smokers who have heart disease.
11. Identify the top 10 individuals by ID,Age,Gender with the highest daily steps who also have a BMI greater than 25.
## Project Process
1. Every Data Analysis Question was translated into valid SQL queries. For Example: How many individuals are males and females?
2. Aggregate functions like avg, min, max were used to calculate summary statistics.
3. Group By Query was used to calculte metrics for specific groups such as gender, smoking status or heart disease.
4. Case statement was used to find out derived categories such as grouping indivisuals into age groups.
5. Functions such as truncate or round was used for presntation purposes to format the results such as average age to 49.
6. Where clause was uset to filter the data. For example: where BMI>25and the order by and limit clause to identify top records.
7. The output of records were recorded from the MYSQL environmemt (Result Grid) for each query.
8. The documnetation of the original analytical questions, the MYSQL query used and the reult grid were documented, organized into a structured project document format (PDF) for presentation.
## Project Insight
1. The average age of individuals in the dataset is 49.
2. The average Body Mass Index (BMI) is 26.
3. The typical individual gets around 6 hours of sleep , and takes approximately 10,717 daily steps.
4. The dataset contains slightly more males (523) than females (477).
5. Males, on average, take a higher number of daily steps (10,960) compared to females (10,450)
6. The vast majority of individuals in the dataset are non-smokers (809), with only 191 individuals reporting as smokers
7. Non-smokers have a slightly higher percentage of heart disease (9.6415%) compared to smokers (7.8534%). This suggests that other factors beyond smoking may be more dominant in this specific dataset's heart disease rates.
8. Individuals who do not have heart disease have a slightly higher average heart rate (84.82) than those who do have heart disease (83.68).
9. The average BMI remains very similar across all activity levels, with Low, Medium, and High activity groups all having an average BMI of approximately 26.78 or 26.69. This suggests that daily steps alone might not be a strong predictor of BMI in this dataset.
10. Across all analyzed age groups, Young Adults (18-25), Adults (26-64), and Seniors (65+),the average hours of sleep is consistently 6 hours.
## Final Conclusion
The project successfully utilized MySQL to analyze the health activity dataset, revealing several key insights into the study population's average metrics and lifestyle correlations.The analysis establishes that the average individual in this dataset is a middle-aged adult (49 years) with a normal to overweight BMI (26) and a moderately active lifestyle, averaging over 10,000 daily steps. The project's deeper findings suggest that for this specific population heart disease prevalence is slightly lower among smokers compared to non-smokers, suggesting that other, unexamined risk factors or behaviors may be stronger determinants of heart disease in this sample. Physical activity, as measured by daily steps, and hours of sleep show little to no variation across different age groups or activity levels, with all major age groups averaging 6 hours of sleep and BMI remaining constant regardless of categorized activity level. In conclusion, while the population appears generally active, the lack of strong correlation between key lifestyle factors (steps, sleep) and general health metrics (BMI, heart disease) suggests that a more detailed analysis incorporating diet, genetics, or specific medical conditions is necessary to fully explain the observed health outcomes.







