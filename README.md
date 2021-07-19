# School_District_Analysis
* Description: Use of Jupyter Notebook to create insights to a school´s budget allocations
* Objective: Read school's and student's raw data, clean and analize data, merge data sets, perform calculations and create tables.
---
## Cleaning and Replacing Data
* The data was cleaned by removing the prefixes and suffixes from student names column located at the data base "student_data"
* The math and reading scores from a school on the 9th grades were dropped because of academic dishonesty. The data was replaced for NaN and was not included on the analysis for the School Budget.
## Data Frame School Summary
* The first table created was School Summary:
The raw data was cleaned, filtered and analized for each school name with the following key      metrics.
### Key Metrics
* School Type : categorizes de type of school (Charter or district)
* Total Students : the number of students per school using the method .value_counts() on the data frame school_data_complete.
* Total School Budget: the metric was obtained by using the .groupby() method and using the average to place it for every school.
* Per Student Budget: Divided the Total school budget betwwen the total students per school.
* Average Math Score : Obtaining the mean for each student math score and visualizing it by school.
* Average Reading Score : Obtaining the mean for each student reading score and visualizing it by school.
* % Passing Math : This metric is the percentage of students who passed Math. 
The count() of students who passed Math divided by the total students
* % Passing Reading : This metric is the percentage of students who passed Reading.
The count() of students who passed Math divided by the total students
* % Overal Passing : This metric is the percentage of students who passed Math and Reading. 
The count() of students who passed Math divided by the total students

![image](https://user-images.githubusercontent.com/85810058/126104570-11338c1d-f633-4bb4-9da5-8b2c62d0e763.png)


### Changes 
* The % Passing Math, % Passing Reading and % Overal Passing was chaned due to a change on the number students who were analized. The 9th grade students from a school were dropped and were not included on the passing percentages.

![image](https://user-images.githubusercontent.com/85810058/126104478-2fb39c76-ee1f-4b9e-94e8-5ac31aa69d23.png)

## Budget 
* Key metric: Budget based on spending ranges per student and school size
![image](https://user-images.githubusercontent.com/85810058/126104652-a9ce4339-cbb3-453d-81a5-02ee33e5f7ed.png)


