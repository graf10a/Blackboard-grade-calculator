# Blackboard-grade-calculator
*Computing course percentages and grades with a Blackboard grade book file*

The purpose of the Jupyter notebook included in this repository is to compute the current grades of the students listed in a gradebook file downloaded from Blackboard in the coma-separated format. The output is generated in the form of a new CSV file which is obtained by ammending the original gradebook file with Grades and Percentage columns.

This notebook was created in the fall semester of 2017 when Blackboard experienced problems with the Weighted Total gradebook column -- the percentages displayed in the column were not computed correctly making it impossible to quickly check the current academic standing of students in my classes. The problem was fixed by the end of the semester but it motivated me to write this code just in case if something similar ever happens again.

The repository contains the following files:

1. 'Blackboard_grade_calculator.ipynb' -- the notebook file.
2. 'README.md' -- this file.
3. 'gradebook_file.csv' -- a sample of Blackboard gradebook file included for demonstration purposes. The file contains some fake grades data and it can be run smoothly with the notebook file.
