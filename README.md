## School_District_Analysis
School District Analysis Project

### Overview of the District Analysis

The purpose of the school district analysis is to provide a high-level snapshot of the district's key metrics and an overview of key metrics for each school in the districts. The following are some of the key metrics that the analysis is expected to highlight;

  1. Top 5 and bottom 5 performing schools, based on the overall passing rate
  2. The average math score received by students in each grade level at each school
  3. The average reading score received by students in each grade level at each school
  4. School performance based on the budget per student
  5. School performance based on the school size
  6. School performance based on the type of school

To generate these information, I utilized the following resources;

  - Data Source: schools_complete.csv, students_complete.csv
  - Softwares: Anaconda 4.8.3, Jupyter Notebook, Python 3.7.6 
  
### Results  

The following are some of the key insights / responses to some salient questions from the analysis of the schools_complete.csv and students_complete.csv data files for the school district analysis;

- __How is the district summary affected?__ The district summary analysis snapshot showed a total of 15 schools and 39,170 students in the district. The average math and reading scores of students in the district were well above the pass avaerage (>=70) at 79 and 81.9 respectively. In thesame vein, the percentages of the total student pouplation that passed math and reading respectively were 75% and 86% respectively. However, the overall percentage of student population that passed both subjects (math & reading) dipped to 65%. The screen shot below shows a view of the district summary.
<img src="Images/District%20Analysis.png">

- __How is the school summary affected?__ The school summary analysis snapshot showed that the "Charter" school types occupied the top 5 performing schools with Carbrera, Thomas, Griffin, Wilson and Pena High Schools occupying the top 5 positions in terms of overall percentage of students that passed both math and reading (performance hovered between 90.5% and 91.3% for these top 5 schools). In thesame vein, these top schools also had a comparative better average math and reading scores over other schools (scores hovered between 83 to 83.8 in math and 83.8 to 84 in reading). 
On the contrary, the "District" school types occupied the bottom 5 performing schools with Rodriguez, Figuerora, Huang, Hernandez and Johnson occupying the bottom 5 positions in terms of overall percentage of students that passed both math and reading (performance hovered between 52.9% and 53.5% for these bottom 5 schools). In thesame vein, these bottom schools had a comparative worse average math and reading scores over other schools (scores hovered between 76.6 to 77.2 in math and 80.7 to 81.2 in reading). 


- __How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?__ Prior to the replacement of the 9th graders math and reading scores for Thomas High School (THS), the percentage of THS students who passed math, reading and both courses were 93.3%, 97.3% and 90.9% respectively. When the 9th grader scores were replaced, there was a slight dip (about 0.2 - 0.3 percentage reduction) in these percentages to 93.1%, 97.0% and 90.6% in math, reading and both courses respectively. However when compared to the performances of other schools, Thomas High School retained its second position (based on percentage overall passing) among the 15 schools analyzed even after the 9th grader scores were replaced. This effectively means that 9th graders score replacement had very minimal impact on THS overall perfomance in the school analysis. 


- __How does replacing the ninth-grade scores affect the following;__

1. _Math and Reading Scores By Grade:_ The replacement of the 9th grader scores only impacted the math and reading scores of the 9th graders of Thomas High School. Before the replacement, average math and reading scores for Thomas High School 9th graders were 83.59 and 83.73 respectively. However, NaN was recorded for 9th grade Thomas High School students after the replacement. It is however important to highlight that the average math and reading scores of 10th - 12th graders of Thomas High School and the 9th - 12th graders of the other schools were not affected by these replacements. 

2. _Scores by School Spending:_ The replacement of the 9th grader scores had no impact on absolute average spending per student in Thomas High School. This remained at $638 per student for Thomas High School. From the data provided, average spending per student is only affected by the size (number of students) of the school. Even though there was a slight drop in the percentages in math, reading, and overall (both courses) to 93.1%, 97.0% and 90.6% respectively from 93.3%, 97.3% and 90.9%, this slight dip is not as a result of the impact of spending per student. It should also be noted that the scores of other scools were unaffected.  

3. _Scores by School Size:_ The replacement of the 9th grader scores had no impact on the size of the schools or on their respectiive scores. Despite the replacements of the 9th grader scores, Thomas High School still remained classed as a medium type school in the 1000-2000 size bracket.

4. _Scores by School Type:_ The replacement of the 9th grader scores had no impact on scores by school type. The average math and reading scores were thesame before and after the replacement.


### Summary  

The following are a summarized view of the major changes in the school district analysis following the chages in the 9th grader scores of Thomas High School;

1. _Percentage of Students Passing Math in THS -_ Prior to the adjustment in scores of the 9th graders in Thomas High School,the percentage of students who passed math were 93.3%. However this figure dropped to 93.1% after the adjustment which reflects a 0.2 percentage dip.

2. _Percentage of Students Passing Reading in THS -_ Prior to the adjustment in scores of the 9th graders in Thomas High School,the percentage of students who passed reading were 97.3%. However this figure dropped to 97.0% after the adjustment which reflects a 0.3 percentage dip.

3. _Percentage of Students who passed both Math & Reading -_ Prior to the adjustment in scores of the 9th graders in Thomas High School,the percentage of students who passed both math & reading (overall) were 90.9%. However this figure dropped to 90.6% after the adjustment which reflects a 0.3 percentage dip.

4. _Math and Reading Scores By Grade -_ Prior to the adjustment in scores of the 9th graders in Thomas High School, average math and reading scores for Thomas High School 9th grade were 83.59 and 83.73 respectively. However, no score was recorded for the 9th grade students in THS after the adjustment.  

