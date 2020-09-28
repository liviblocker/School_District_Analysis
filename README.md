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

![Old_Top_5.png](https://github.com/liviblocker/School_District_Analysis/blob/master/Resources/Old_District_Summary.png)
![New_Top_5.png](https://github.com/liviblocker/School_District_Analysis/blob/master/Resources/New_District_Summary.png)

Because Thomas High School was not in the bottom 5 schools, the change did not affect the list of bottom 5 performing schools in the district:

![Bottom_5.png](https://github.com/liviblocker/School_District_Analysis/blob/master/Resources/New_District_Summary.png)

### Average Math and Reading Score by Grade
As you might imagine, the average math and reading scores (by grade) were not affected by the data removal other than the obvious: that the nineth graders in Thomas High School did not have grades.

#### Math Scores
<p align="center">
Initial Analysis | Updated Analysis
:---:|:---:
![Old_Math_Scores.png](https://github.com/liviblocker/School_District_Analysis/blob/master/Resources/Old_Math_Scores.png)  |  ![New_Math_Scores.png](https://github.com/liviblocker/School_District_Analysis/blob/master/Resources/New_Math_Scores.png)
</p>

#### Reading Scores
<p align="center">
 Initial Analysis | Updated Analysis
:---:|:---:
![Old_Reading_Scores.png](https://github.com/liviblocker/School_District_Analysis/blob/master/Resources/Old_Reading_Scores.png)  |  ![New_Reading_Scores.png](https://github.com/liviblocker/School_District_Analysis/blob/master/Resources/New_Reading_Scores.png)
</p>

### Scores by School Spending per Student, by School Size, and by School Type
There was no significant difference in the scores by school spending per student, by school size, or by school type. The following are the results of each:

#### School Spending per Student
<p align="center">
![Old_Spending.png](https://github.com/liviblocker/School_District_Analysis/blob/master/Resources/Old_Spending.png)
![New_Spending.png](https://github.com/liviblocker/School_District_Analysis/blob/master/Resources/New_Spending.png)
</p>

#### School Spending by School Size
<p align="center">
![Old_Size.png](https://github.com/liviblocker/School_District_Analysis/blob/master/Resources/Old_Size.png)
![New_Size.png](https://github.com/liviblocker/School_District_Analysis/blob/master/Resources/New_Size.png)
</p>

#### School Spending by School Type
<p align="center">
![Old_Type.png](https://github.com/liviblocker/School_District_Analysis/blob/master/Resources/Old_Type.png)
![New_Type.png](https://github.com/liviblocker/School_District_Analysis/blob/master/Resources/New_Type.png)
</p>

  ## Summary
There is a statement summarizing four major changes to the school district analysis after reading and math scores have been replaced (5 pt).

The above analysis was completed by writing a code to output the winner of the congressional election in Colorado and the county with the highest turnout. The script also outputs a full candidate and county list and the number of votes associated with each. With some modifications this script can be utilized to output those same results in any given election, including national elections or smaller city races. The same logic applies, though the variable names may need to be updated for clarity. As you can see in the code below, I've associated different variable names to different columns in the election data that was provided:
  
  ![Election_Analysis_Picture1.png](https://github.com/liviblocker/Election_Analysis/blob/master/Resources/Election_Analysis_Picture1.png)
  
  By adding candidates or counties, or the number of ballots more generally, then with the click of a button a new analysis can be run.
  
  Additionally, the same code can be adapted for a number of uses. If we received any demographic information from the ballots, then the script can be adapted to determine the most popular candidate among women or African American voters, for example. This script, therefore, is not only helpful for determining election results, but can also be helpful in better understanding the constituency of various candidates that could determine policy considerations that impact specific demographic groups. These data would also be helpful for re-election purposes: to better understand what demographics were not reached by a particular candidate.
  
  With more robust voter demographic data we could also better determine what demographic populations voted in which counties. The racial demographics of voters by county - when compared to the general racial demographics of the county - could also be used to determine if there is poor turnout by a particular racial demographic group. This can, in turn, be used to determine if there are particular effects of voter suppression laws or other accessiblity issues to voting on a hyperlocal level.
  
  This is all to say, this script and my ability to adapt the code for further analysis could be helpful beyond this election. If given the opportunity to continue working with the election commission further, I can provide analysis that can be used in a wide variety of ways.
