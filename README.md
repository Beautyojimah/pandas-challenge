# pandas-challenge

This repository contains a Pandas projects for data analysis called PyCitySchools. Within the PyCitySchools folder, there is a pandas script that shows the analysis of a city's schools. A comprehensive report of the analysis and the  csv files (schools_complete and students_complete) used for the analysis are also contained within the folder.

## Pandas Challenge Description

This repository contains a Python script that analyses the district-wide standardised test results for students' math and reading scores to show trends in school performance. 
- This analysis shows a summary of the schools including the school name, school type, total students, total school budget, per student budget, average math score, average reading score, % passing math (the percentage of students who passed math), % passing reading (the percentage of students who passed reading) and % overall passing (the percentage of students who passed math AND reading).

- The analysis shows the highest-performing Schools by percentage overall passing. 

- It shows th lowest-performing schools by overall passing.

- The analysis categorises the math scores by grade level (9th, 10th, 11th, 12th) at each school. 

- It categorises the reading scores by grade level (9th, 10th, 11th, 12th) at each school.

- It shows the school performance based on average spending ranges (per student).

- It shows the break down of the school performance based on school size (small, medium, or large). 

- The analysis shows the school performance based on the "School Type".


## Installations 

    Python 3.9
    pandas as pd
    path

### How to run the script 
#### clone this repo below 
```bash
git clone https://github.com/Beautyojimah/pandas-challenge.git
```
To run the PyCitySchools to view the script
cd into PyCitySchools

Run to view script
```bash
PyCitySchools_script.ipynb
```
## Summary result of Analysis

The analysis shows that students in a Charter type school significantly outperforms those in District type school, despite District type school having higher school budget. As well, it shows that students with a spending range less than $585 have higher overall performance when compared to students with  spending ranges above $585. Finally, there is an inverse correlation between school size and students' performance, as students in small and medium sized schools (within the range of less than 2000) show better performance than student's in large schools(above 2000). I have attached snapshots to show some of the tables.

<img width="550" alt="image" src="https://github.com/Beautyojimah/pandas-challenge/assets/110996458/25c43262-7db6-4727-a672-f4735228bb18">

<img width="510" alt="image" src="https://github.com/Beautyojimah/pandas-challenge/assets/110996458/fd9e7964-74fb-4b34-a25f-1ac1d5422d5b">

<img width="485" alt="image" src="https://github.com/Beautyojimah/pandas-challenge/assets/110996458/a6ffa0e8-4c5f-43d3-a8f9-dd04aa96c517">


