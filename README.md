# School_District_Analysis
Module 4

python3.7

new_full_student_data.csv

## Module 4 Challenge
>Maria has gotten a new version of the student data with several changes. This includes an additional column: "school budget". She wants you to rework part of your analysis by using the new dataset.
Using New_full_student_data,csv we looked at average scores for different subjects as well as they type of school and average funding allowing us to examine a coorelation between school funding and student test scores. 
### Challenge Deliverables 
>Deliverable 1: Collect the student data into a DataFrame.
```
new_full_student_data = os.path.join('../Resources/new_full_student_data.csv')
student_df = pd.read_csv(new_full_student_data)
```
>Deliverable 2: Prepare a cleaned version of the DataFrame.
I used the `.dropna()` and `.drop_duplicates()` functions to drop rows with missing and duplicated information to clean this data set 

>Deliverable 3: Summarize key pieces of the data.
By looking at score averages by different groupings we can examine trends in student test scores. We can also look at the lowest scores to see patterns in the data. 

>Deliverable 4: Drill down into the data to analyze specific subsets.
`.loc` and `.iloc` were helpful in analyzing subsets of our data

>Deliverable 5: Compare and contrast the data through grouping and aggregation functions.
While examining the data we found that Montgomery High had the most studnts while Chang High had the least with less than 10% as many students. 

>Deliverable 6: A written analysis of your results (README.md).
Charter schools had a slightly lower overall bidget but higher average test scores when compared to public schools. However, looking at budgets as 'dollars per student' and the relation between that and test scores might allow us to make a more informed decision on budgets 
