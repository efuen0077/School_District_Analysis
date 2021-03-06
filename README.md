# School_District_Analysis
Week 4 of the Data Analytics Bootcamp.


## Challenge

### Background
The grades of the ninth graders at Thomas High School have been changed. While administrators do not know the full extent of this academic dishonesty, they want to uphold the standards of state testing and have turned to you for help.

After assessing the situation with the school superintendent and Maria, you decide the best approach is to:

Replace the ninth-grade math and reading scores from Thomas High School.
Keep all other data associated with the ninth-grade students and Thomas High School intact.

### Objectives

The goals of this challenge are for you to:

Filter DataFrames using logical operators.
Replace the incorrect values with NaN.
Explain how your PyCitySchools analysis changes after you handle the incorrect data. 

### Instructions

1. Create a duplicate of PyCitySchools.ipynb and rename it PyCitySchools_Challenge.ipynb.
2. Correct the students' names so there are no professional prefixes or suffixes.


3. Replace the reading and math scores for ninth graders at Thomas High School with NaN.


4. Merge the clean student data with the school dataset. The column order for all the DataFrames and number formatting should  
   be the same as what was covered in this module.
5. After replacing the reading and math scores, complete the following steps and answer the questions for each step.

#### Final Code

[PyCitySchools_Challenge.ipynb.zip](https://github.com/efuen0077/School_District_Analysis/files/4654560/PyCitySchools_Challenge.ipynb.zip)

### Analysis

##### Before NaN

<img width="727" alt="T  Summary before NaN" src="https://user-images.githubusercontent.com/62089134/82404104-402e7a80-9a15-11ea-97aa-756a3923d8c1.png">

##### After NaN
<img width="743" alt="Type Summary" src="https://user-images.githubusercontent.com/62089134/82404027-0eb5af00-9a15-11ea-85a0-51688818cfeb.png">


If one were to go ahead and replace all 9th grade math and reading scores at Thomas High School with NaN, all of the mathematical calculations in this code will lead to a smaller number. For instance, instead of accounting for ALL scores within Thomas High School, we are only looking at grades 10, 11, and 12. This would lower Thomas High School's overall passing percentage. In other words, Thomas High School's performance (relative to other schools) will appear to decrease. Math and reading scores for 9th graders would be insignificant as NaN doesn't relay any valuable information.

The district summary would be affected in that passing scores for math and reading under the "Charter" category would slightly decrease. Passing Math and Reading scores are 94% and 97% respectively BEFORE the 9th grade math and reading scores at Thomas High School are replaced with NaN. Passing Math and Reading scores are 94% and 97% respectively AFTER the 9th grade math and reading scores at Thomas High School are replaced with NaN. Overall passing percentage goes from 90% to 87% once these scores are replaced.



The removal of ninth grade scores affected the Charter schools' information rather than that of the District.
