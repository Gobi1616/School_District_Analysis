# School_District_Analysis

## Backround

This repository provides a python pandas method for analysing school district data in the education field. Both datasets were downloaded, combined, and the aggregate data was displayed in python pandas dataframes for these analyses. The project is run in Jupyter notebook, and the following connection was generated to highlight and communicate the research report: Viewer for Jupyter Notebooks. This initiative will assist the school board and mayor in making informed decisions about school budgets and goals in the future.

## Overview of the school district analysis:

According to the school summary findings, 7 of the 15 schools are located at the district level, while the remaining 8 are located at the charter level. There are 15 schools in the dataset, with a total of 39,170 students. The average reading score for all students is 81.9, which is higher than the average math score of 78.9. When we consider that reading (84.7%) has a higher passing rate than math (73.9%), the overall passing rate is 64.1%. According to these results, students do better in reading than in math.

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

The score substitutions had an impact on the ranking of the top five performing schools when evaluating school summaries and performance schools. Thomas High School was removed from the top five category after replacing both math and reading results, as they now have a 65% overall passing rate. On the plus side, Thomas High School did not fall into the bottom five performing schools as a result of these modifications.

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

Additional advantage of this data substitution would be that the math and reading scores by grade were not affected. Furthermore, the average highlights of math and reading scores were stratified by school and grade level. The summary tables for ninth grade at Thomas High School exhibit "NaN" as shown below in the next heading, although the rest of the data is still intact.

### Rreplacing the ninth-grade scores affect the following:  
  
  -   Math Scores by Grade:
      A table that lists the average Math Score for students of each grade level (9th, 10th, 11th, 12th) at each school was created.

      A table of Math Scores by Grade looks as follows:

      ![image](https://user-images.githubusercontent.com/82549869/119224120-f5818b80-baca-11eb-9c02-0e91a400366b.png)

  -   Reading Scores by Grade:
      A table that lists the average Reading Score for students of each grade level (9th, 10th, 11th, 12th) at each school was created.

      A table of Reading Scores by Grade looks as follows:
        
      ![image](https://user-images.githubusercontent.com/82549869/119224180-34afdc80-bacb-11eb-8777-2d60a70080ea.png)

  -   Scores by School Spending:

   A table that breaks down school performances based on average Spending Ranges (Per Student), and 4 reasonable bins to group school spending was created.The table includes each of the following:
          - Average Math Score
          - Average Reading Score
          - % Passing Math (The percentage of students that passed math.)
          - % Passing Reading (The percentage of students that passed reading.)
          - % Overall Passing (The percentage of students that passed math and reading.)

        A table of Scores by School Spending looks as follows:

   ![image](https://user-images.githubusercontent.com/82549869/119229096-43ef5400-bae4-11eb-9449-f4b53658ca7e.png)

  -   Scores by school size:
      - The following table created by grouping schools based on a reasonable approximation of school size (Small, Medium, Large).

   When reviewing the School Size summary, removing the ninth grade scores did not affect the average math and reading scores, but it did affect the passing percentages for medium-sized schools (1,000-2,000). In this category, % passing math, % passing reading, and % overall passing dropped 6% each. Before the data change, the School Size summary showed that medium-sized school had a high performance (91% overall passing) compared to small (90% overall passing) and large schools (58% overall passing). Given the data change, medium size school are the second in performance (85% overall passing).
      
        A table of Scores by School Size looks as follows:
        
   ![image](https://user-images.githubusercontent.com/82549869/119229120-6a14f400-bae4-11eb-89aa-c92c39d0e566.png)

  - Scores by school type:
      - Finally a solution that group schools based on school type (Charter vs. District) was created.
 
   In reviewing the last summary on School Types, this data change also affected the passing percentages that compared charter and district schools. Fortunately, it did not affect the average scores for these two school types. Removing the scores resulted in a reduction in charter school's passing percentages. Before the data change, charter schools had very high passing percentages: 94% passing math, 97% passing reading, 90% overall passing. After the data change, charter schools now have a 90% passing math, 93% passing reading, 87% overall passing. On the plus side, these rates are still far superior when compared to district schools.  
    
       A table of Scores by School Type looks as follows:
        
   ![image](https://user-images.githubusercontent.com/82549869/119229135-78631000-bae4-11eb-810f-c298f8bf8b70.png)


## Summary:

According to the results, average math scores, average reading scores, passing math, passing reading, and overall passing all decrease as the number of students in a classroom increases.For 461 student records, both math and reading scores were substituted with "NaN".   Even though it may appear to be a large amount, the score substitutions had little impact on data summaries overall.

