# School_District_Analysis
## Overview of School District Analysis
For this analysis, I was asked to complete a range of tasks for a local school district. After the initial analysis, the school board notified me that the reading and math grades for Thomas High School ninth graders appear to have been altered. To account for the inaccurate data (and to uphold state testing standard), I was asked to remove the Thomas High School, nineth grade reading and math grades and rerun the analysis, focusing on the following tasks:

  * Develop a district summary
  * Develop a school summary
  * Determine the top 5 and bottom 5 performing schools, based on the overall passing rate
  * Determine the average math score for each grade level from each school
  * Determine the average reading score for each grade level from each school
  * Determine the scores by school spending per student, by school size, and by school type

## Results:
### District Summary
In both analyses, the percentage of students that passed math was 75%, students that passed reading was 86%, and the overall passing percentage was at 65%. When nineth graders in Thomas High School were removed from the analysis, percentages only shifted by .1 percentage points, leaving the overall district numbers the same. See below for the Initial analysis district summary, and the secondary analysis, respectively.

![Old_District_Summary.png](https://github.com/liviblocker/School_District_Analysis/blob/master/Resources/Old_District_Summary.png)
![New_District_Summary.png](https://github.com/liviblocker/School_District_Analysis/blob/master/Resources/New_District_Summary.png)


### School Summary
Dropping the Thomas High School nineth grade math and reading scores made a significant difference in the school summary. As you can see in the images below, the percentage of Thomas High School students that passed math shifted from 67% to 93%, the percentage of Thomas High School students that passed reading shifted from 70% to 97%, and the overall passing percentage shifted from 65% to  90%.

![Old_School_Summary.png](https://github.com/liviblocker/School_District_Analysis/blob/master/Resources/Old_District_Summary.png)
![New_School_Summary.png](https://github.com/liviblocker/School_District_Analysis/blob/master/Resources/New_District_Summary.png)

### Top 5 and Bottom 5 Performing Schools
With the removal of the nineth graders scores, Thomas High School jumped to the second highest performing school in the district. 

![Old_Top_5.png](https://github.com/liviblocker/School_District_Analysis/blob/master/Resources/Old_Top_5.png)
![New_Top_5.png](https://github.com/liviblocker/School_District_Analysis/blob/master/Resources/New_Top_5.png)

Because Thomas High School was not in the bottom 5 schools, the change did not affect the list of bottom 5 performing schools in the district:

![Bottom_5.png](https://github.com/liviblocker/School_District_Analysis/blob/master/Resources/Bottom_5.png)

### Average Math and Reading Score by Grade
As you might imagine, the average math and reading scores (by grade) were not affected by the data removal other than the obvious: that the nineth graders in Thomas High School did not have grades.

<p align="center">

#### Math Scores
Initial Analysis | Updated Analysis
:---:|:---:
![Old_Math_Scores.png](https://github.com/liviblocker/School_District_Analysis/blob/master/Resources/Old_Math_Scores.png)  |  ![New_Math_Scores.png](https://github.com/liviblocker/School_District_Analysis/blob/master/Resources/New_Math_Scores.png)

#### Reading Scores
 Initial Analysis | Updated Analysis
:---:|:---:
![Old_Reading_Scores.png](https://github.com/liviblocker/School_District_Analysis/blob/master/Resources/Old_Reading_Scores.png)  |  ![New_Reading_Scores.png](https://github.com/liviblocker/School_District_Analysis/blob/master/Resources/New_Reading_Scores.png)

</p>

### Scores by School Spending per Student, by School Size, and by School Type
There was no significant difference in the scores by school spending per student, by school size, or by school type. The following are the results of each:

<p align="center">
 
#### School Spending per Student
![New_Spending.png](https://github.com/liviblocker/School_District_Analysis/blob/master/Resources/New_Spending.png)

#### School Spending by School Size
![New_Size.png](https://github.com/liviblocker/School_District_Analysis/blob/master/Resources/New_Size.png)

#### School Spending by School Type
![New_Type.png](https://github.com/liviblocker/School_District_Analysis/blob/master/Resources/New_Type.png)

</p>

  ## Summary
The four major changes to the school district analysis after the reading and math scores had been replaced were:
1. The passing percentages for math and reading increased dramatically at Thomas High School, increasing by almost 30 percentage points. This tells us the nineth grade scores were dragging down the school average rather significantly.
2. As a result of dropping the nineth grade scores, Thomas High School is now shown to be the second most top performing high school in the district, which could impact funding the school recieves.
3. Because Thomas High Schools has shown to be performing quite well, 
4. While these differences are stark on a school by school scale, the adjustment made little difference on a district-wide scale. The small difference it did make, showed us that the adjustment actually lowered the overall performance of the district. This is likely due to the adjusted student numbers. This could potentially have a negative effect on district on a city-wide scale, though the difference is so minimal it likely won't affect the district's funding. 
