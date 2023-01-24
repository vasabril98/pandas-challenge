# pandas-challenge

## Background

You are the new Chief Data Scientist for your city's school district. In this capacity, you'll be helping the school board and mayor make strategic decisions regarding future school budgets and priorities.

As a first task, you've been asked to analyze the district-wide standardized test results. You'll be given access to every student's math and reading scores, as well as various information on the schools they attend. Your task is to aggregate the data to showcase obvious trends in school performance.

This project used two datasets in csv format, one is [schools_complete.csv](Resources/schools_complete.csv) file wich includes the following informations in columns `Student ID`,`school_name`,`type`,`size`,`budget` the other dataset is [students_complete.csv](/Resources/students_complete.csv) file which includes the followling information in columns `Student ID`,`student_name`,`gender`,`grade`,`school_name`,`reading_score`and `math_score`. For these analysis both datasets imported, merged, and the aggregate data diplayed in to python pandas dataframes. The project is conducted in Jupyter notebook to showcase, and communicate the analysis report.


## Instructions
Using Pandas and Jupyter Notebook, create a report that includes the following data. Your report must include a written description of at least two observable trends based on the data.

### District Summary
* A high level analysis on the district's created on the following key metrics
  * Total Schools
  * Total Students
  * Total Budget
  * Average Math Score
  * Average Reading Score
  * % Passing Math (The percentage of students that passed math.)
  * % Passing Reading (The percentage of students that passed reading.)
  * % Overall Passing (The percentage of students that passed math **and** reading.)

### School Summary
* An overview table that summarizes key metrics about each school was created in the following metrics
  * School Name
  * School Type
  * Total Students
  * Total School Budget
  * Per Student Budget
  * Average Math Score
  * Average Reading Score
  * % Passing Math (The percentage of students that passed math.)
  * % Passing Reading (The percentage of students that passed reading.)
  * % Overall Passing (The percentage of students that passed math **and** reading.)

### Highest-Performing Schools (By % Overall Passing)
* A table that highlights the top 5 performing schools based on % Overall Passing was created and it includes the following metrics.
  * School Name
  * School Type
  * Total Students
  * Total School Budget
  * Per Student Budget
  * Average Math Score
  * Average Reading Score
  * % Passing Math (The percentage of students that passed math.)
  * % Passing Reading (The percentage of students that passed reading.)
  * % Overall Passing (The percentage of students that passed math **and** reading.)

### Lowest-Performing Schools (By % Overall Passing)
* A table that highlights the bottom 5 performing schools based on % Overall Passing was created Include all of the same metrics as above.

### Math Scores by Grade
* A table that lists the average Math Score for students of each grade level (9th, 10th, 11th, 12th) at each school.

### Reading Scores by Grade
* A table that lists the average Reading Score for students of each grade level (9th, 10th, 11th, 12th) at each school.

### Scores by School Spending
* A table that breaks down school performances based on average Spending Ranges (Per Student), and 4 reasonable bins to group school spending was created.The table includes each of the following:
  * Average Math Score
  * Average Reading Score
  * % Passing Math (The percentage of students that passed math.)
  * % Passing Reading (The percentage of students that passed reading.)
  * % Overall Passing (The percentage of students that passed math **and** reading.)

### Scores by School Size
* The following table created by grouping schools based on a reasonable approximation of school size (Small, Medium, Large).

### Scores by School Type
*  Finally a solution that group schools based on school type (Charter vs. District) was created.
