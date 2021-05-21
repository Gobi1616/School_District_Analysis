# School_District_Analysis

## Backround

This repository provides a python pandas method for analysing school district data in the education field. Both datasets were downloaded, combined, and the aggregate data was displayed in python pandas dataframes for these analyses. The project is run in Jupyter notebook, and the following connection was generated to highlight and communicate the research report: Viewer for Jupyter Notebooks. This initiative will assist the school board and mayor in making informed decisions about school budgets and goals in the future.

## Overview of the school district analysis:

According to the school summary findings, 7 of the 15 schools are located at the district level, while the remaining 8 are located at the charter level. There are 15 schools in the dataset, with a total of 39,170 students. The average reading score for all students is 81.87, which is higher than the average math score of 78.98. When we consider that reading (85.80%) has a higher passing rate than math (74.98%), the overall passing rate is 65.17 percent. According to these results, students do better in reading than in math.

## Results: Using bulleted lists and images of DataFrames as support, address the following questions.

### District summary:

When comparing average math scores and passing percentages across the district's 15 high schools, the average math score decreased. 1. The average reading score remained same, while the percentage passing math, reading, and overall passed percent all decreased by 1%.

An overview table that summarizes key metrics about district was created in the following metrics

      - Total Schools
      - Total Students
      - Total Budget
      - Average Math Score
      - Average Reading Score
      - % Passing Math (The percentage of students that passed math.)
      - % Passing Reading (The percentage of students that passed reading.)
      - % Overall Passing (The percentage of students that passed math and reading.)
    
   The district summery table looks as follows:

![image](https://user-images.githubusercontent.com/82549869/119054073-062fe580-b995-11eb-8480-9e6adfc0fbcf.png)
  
### School summary:
      
An overview table that summarizes key metrics about each school was created in the following metrics

      - School Name
      - School Type
      - Total Students
      - Total School Budget
      - Per Student Budget
      - Average Math Score
      - Average Reading Score
      - % Passing Math (The percentage of students that passed math.)
      - % Passing Reading (The percentage of students that passed reading.)
      - % Overall Passing (The percentage of students that passed math and reading.)
 
 ![image](https://user-images.githubusercontent.com/82549869/119054297-658df580-b995-11eb-8815-a821729313a7.png)
  
### Replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools:


### Rreplacing the ninth-grade scores affect the following:  
  
  -   Math Scores by Grade:
      - A table that lists the average Math Score for students of each grade level (9th, 10th, 11th, 12th) at each school was created.

        A table of Math Scores by Grade looks as follows:


  -   Reading Scores by Grade:
      - A table that lists the average Reading Score for students of each grade level (9th, 10th, 11th, 12th) at each school was created.

        A table of Reading Scores by Grade looks as follows:


  -   Scores by School Spending:
      - A table that breaks down school performances based on average Spending Ranges (Per Student), and 4 reasonable bins to group school spending was created.The       table includes each of the following:
          - Average Math Score
          - Average Reading Score
          - % Passing Math (The percentage of students that passed math.)
          - % Passing Reading (The percentage of students that passed reading.)
          - % Overall Passing (The percentage of students that passed math and reading.)

        A table of Scores by School Spending looks as follows:


  -   Scores by school size:
      - The following table created by grouping schools based on a reasonable approximation of school size (Small, Medium, Large).

        A table of Scores by School Size looks as follows:

  - Scores by school type:
      - Finally a solution that group schools based on school type (Charter vs. District) was created.

        A table of Scores by School Type looks as follows:

## Summary:

According to the results, average math scores, average reading scores, passing math, passing reading, and overall passing all decrease as the number of students in a classroom increases.For 461 student records, both math and reading scores were substituted with "NaN".   Even though it may appear to be a large amount, the score substitutions had little impact on data summaries overall.
