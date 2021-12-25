# School District Analysis

## Overview
This project was focused on analyzing the High Schools in a specific district to assess how well students were doing. We were given raw data which we cleaned and queried using Jupyter Notebook. In our assessment we looked at how the amount of funding per student impacted grades, as well as how student performance varied in charter and public schools. After our initial analysis it was discovered that the 9th graders at Thomas High School had been cheating on their tests. In order to not bias the data all 9th Grades from THS had their grades withdraw from grading. A new analysis was conducted at this point and the results can be seen below.

## Results and Analysis
We initially begain by viewing top line data by schools in a district summary. Below you can see the initial summary and the updated one.

Original Summary (Figure 1)
![image](https://user-images.githubusercontent.com/91395269/147374468-f53be17b-233f-40e9-9887-a74b6dadfba0.png)


Updated Summary (Figure 2)
![image](https://user-images.githubusercontent.com/91395269/147374474-5aca2bcf-8b37-4006-ba3b-2f18eb63658b.png)


The initial summary had a higher overall passing rate since one subset of students had better scores due to the cheating scandal.

When comparing all schools together in summary there are no major changes between the two data frames other than for Thomas High School. Due to the scandal we had to withdraw the ninth graders grades from the assessment and the 9th grades themselves from the calculations to find out the true passing percentages from math and reading. When we initially replaced the 9th grade scores while keeping the 9th graders in the average it lowered THS's scores when compared to the other schools. Once the 9th graders were completely withdrawn from the grade summaries THS went back to the top of the list for school performance. In figure 3 you can see the initial summary and then the accurate summary in figure 4.

![image](https://user-images.githubusercontent.com/91395269/147374775-2568c08b-6149-4ab7-850c-47665094c68d.png)
Figure 3


![image](https://user-images.githubusercontent.com/91395269/147374762-bd8e64c3-ebe5-41a2-8b4e-b1da8e62704e.png)
Figure 4

Below is a breakdown of the effects of replacing the 9th grade reading and math grades:

- Math and reading scores by grade went down slightly
- Scores by school spending was unchanged
- Scores by school size was unchanged
- Scores by school type was unchanged

Since such a small subset of the population was withdrawn between the two analysis there were no major shifts when correcting the data. Had 9th graders across all schools cheated this would have produced a much more noticeable change.

## Summary
In order to ensure the best analysis we had to make several changes to our initial report. We had to replace all the THS 9th grade reading and math scores, we had to update the reading and math scores by withdrawing the 9th graders from consideration, we then had to do the same update to the math and reading percentages, and the overall school percentage for passing students. Based on the results of our work we can conclude that the Charter Schools have much better student performance than the District schools (see fig 5). We can also see that Mid sized schools (1000-200 students-fig 6) perform the best. When looking at spending per student the schools that spent less per student tended to have better results. This supports the idea that money alone can not create a more equitable playing field for students but that better classs settings and teachers are the key to imrpoving schools.


##Appendix
![image](https://user-images.githubusercontent.com/91395269/147374976-06a6251c-853e-4b9b-92b7-96e0842fce2a.png)
Figure 5

![image](https://user-images.githubusercontent.com/91395269/147374984-783fff6f-6804-40d4-8498-74f4ac84bad2.png)
Figure 6
