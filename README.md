# School_District_Analysis

# Deliverable 1
# Corrected Data
## Removal of Thomas HS 9th Grade math and readng scores
The firsts tast was to replace all math and reading scores at Thomas High School (THS) with "NaN s these scores are removed from the previous analysis.
THe THS 9th grade math and reading scores were removed usiing the .loc function and the resulting data looks as follows:
These images show student level and overall data verifying that THS 9th Grade data has been removed.

![THS 9th Grade NaN replacement](https://user-images.githubusercontent.com/91839403/145744522-5581fb86-2d61-4892-9471-298ac4587621.png)

Math Scores 

![THS Math Scores NaN](https://user-images.githubusercontent.com/91839403/145748881-2ab46d9d-38b1-42a7-b656-0a822c5419d9.png)


Reading Scores

![THS Reading scores NaN](https://user-images.githubusercontent.com/91839403/145748886-66dc83e8-46db-4c62-897f-cc21f1554cf0.png)


# Deliverable 2
# School District Analysis
## The analysis of the testing results will present the following data:

1. The district summary
2. The school summary
3. The top 5 and bottom 5 performing schools, based on the overall passing rate
4. The average math score for each grade level from each school
5. The average reading score for each grade level from each school
6. The scores by school spending per student, by school size, and by school type
------------------------------------------------------------------------------------
1, District Summary
![image](https://user-images.githubusercontent.com/91839403/145746421-855a74ce-f2d0-48b0-a455-1da0aff4a69c.png)


2. School Summary
![Per School Summary POST THS REMOVAL](https://user-images.githubusercontent.com/91839403/145745522-82c00727-c184-4886-b358-263abca8f24a.png)

3a. The top 5 schools
![Top 5 Schools Analysis THS NaN](https://user-images.githubusercontent.com/91839403/145746023-75be4a9e-a7bc-4408-9ff9-a78af3a5fcdf.png)

3b. The Bottom 5 schools
![Bottom 5 Schools THS NaN](https://user-images.githubusercontent.com/91839403/145746031-0a41b611-84a8-49a7-a231-316202f379c4.png)


4. The Average Math Score by grade level for each school

![Math Scores by Grade THS NaN](https://user-images.githubusercontent.com/91839403/145747955-8847dcbf-1b8d-4a76-8ebe-66c50ec4be2f.png)

5. The average reading score for each grade level from each school

![Reading Scores by Grade THS NaN](https://user-images.githubusercontent.com/91839403/145747835-06effb37-e70f-4c61-bf12-c923117c1447.png)


6. The scores by school spending per student, by school size, and by school type
![Results by Spending THS NaN](https://user-images.githubusercontent.com/91839403/145747230-ea15d85a-e3f8-4ebd-b14d-e6fa0b0ed6b5.png)

![Results by Size THS NaN](https://user-images.githubusercontent.com/91839403/145747240-9d46ef5f-5dbe-46ca-ae02-2ba66793aa52.png)

![Results by type THS NaN](https://user-images.githubusercontent.com/91839403/145747247-962671c3-3e7b-4610-b15c-f31490e1c953.png)

## Summary
The top performing school was Cabrera, a mid sized charter school with low spending per student.  
The lowest performing school was Rodriguez, a large district school spending $630-$644 per student.
Looking at the results by type Charter Schools outperformed district schools significantly.
Reviewing results by spending the schools spending the least performed the best in all categories inclusing overall passing.
The results by size show small and mid-size schools performed the same while large schools underperfomed the other size schools significantly.






# Deliverable 3

## Background
The school board has notification that 9th grade testing mat be compromised and subject to dishonesty.  The specific issue impacts reading and math grades for Thomas High School.  The scores of ninth graders appear to have been altered.We have been notified that the school board does not know the full extent of the academic dishonesty.  Thier intention is to uphold state-testing standards and have requested our assistance in helping deal with the situation. Our client, Maria, asked that we replace the math and reading scores for Thomas High School with blanks scores (we will use NaNs in python coding language,) Maria has asked that all other data remain intact. Maria would like us  to repeat the school district analysis previously performed after we replace Thomas High School math and reading scores. Additionally, Maria would like us to compare the school district analysis before and after the changes to THS.  She has requested a written report describing how the changes affected the original analysis.

1. School District Impact:

Original

![Original District Summary](https://user-images.githubusercontent.com/91839403/145749676-92a3d840-8512-403c-a473-6795984f3297.png)

Corrected

![District Summary THS NaN](https://user-images.githubusercontent.com/91839403/145749724-0bcf3d94-7ddf-4f65-b883-1d91624363dd.png)

The removal of THS 9th grade scores had a minimal effect on overall district results.  
Average Math score was down 0.1%, 
Average reading score was unchanged
Passing math percent was down 0.2%
Passing Reading % was down 0.3%
overall passing percent was down 0.1%

2. School summary Impact:

2a. Top 5 Schools

Original

![Original Top 5 Schools](https://user-images.githubusercontent.com/91839403/145750238-f848b6f3-6248-4e03-930a-e64da4d21ca0.png)

Corrected

![Top 5 Schools Analysis THS NaN](https://user-images.githubusercontent.com/91839403/145750267-69c0d485-ac5a-4ef3-b1ce-00f864680524.png)

Thomas High School originally second in the top 5 school in the district dropped off the top 5 list allowing the 3rd, 4th and 5th place schools to move up and Wright High moved into the 5th position an the changed moved Thomas High School to 6th overall.  Thomas overall passing % dropped from 90.95% to 90.2%.  Showing how tight the scores are at the top of the school district.

2b. Bottom 5 Schools

Original 

![Original Bottom 5 schools](https://user-images.githubusercontent.com/91839403/145750904-85ad5266-c51c-4ba9-8d89-450cf1ea08b3.png)

Corrected

![Bottom 5 Schools THS NaN](https://user-images.githubusercontent.com/91839403/145750916-968b6fd3-6507-43bd-a444-48c34374747d.png)

There was no change to the bottom 5 schools as a result of the removal of THS 9th grade scores.

3. Math and reading scores by School and Grade.

Math (Original)

![Original Math Scores by Grade](https://user-images.githubusercontent.com/91839403/145751456-a2b84b01-0f64-4013-9056-1444fe7d9281.png)

Math (Corrected)

![Math Scores by Grade THS NaN](https://user-images.githubusercontent.com/91839403/145751486-6b610d2b-fe91-42bb-96ba-2ad6fa1e8e1f.png)

Reading (Original)

![Original Reading Scores by Grade](https://user-images.githubusercontent.com/91839403/145751464-cc44804c-a999-49c4-86e8-f9afe2d117c1.png)

Reading (Corrected)

![Reading Scores by Grade THS NaN](https://user-images.githubusercontent.com/91839403/145751473-e377fb47-02e5-452d-84d8-9f745aa34394.png)

Corrected




![Math Scores by Grade THS NaN](https://user-images.githubusercontent.com/91839403/145751486-6b610d2b-fe91-42bb-96ba-2ad6fa1e8e1f.png)

As we would expect the scores by grade are uneffected by the removal of the THS 9th Grade data.
The individual grades by subject are computed specifically for those schools and grades.  The overall Thomas results were impacted and the district reults were impacted due to the change in the total number of overall students.  That change would not impact individual grade results.

4. Scores by school spending

Original 

![Original Results by Spending](https://user-images.githubusercontent.com/91839403/145752255-547431da-87f5-4f10-a434-324b86c6c865.png)

Corrected

![Results by Spending THS NaN](https://user-images.githubusercontent.com/91839403/145752261-daf82b29-4efa-4d42-a623-9692448a93a9.png)


5. Scores by school size

Original 

![Original results by size](https://user-images.githubusercontent.com/91839403/145752866-b96b321f-08d5-4d96-aba6-11421778a595.png)


Corrected

![Results by Size THS NaN](https://user-images.githubusercontent.com/91839403/145752878-b639f435-b321-48ce-9393-d7b3833e536e.png)



6. Scores by school type

Original 

![Original Results by Type](https://user-images.githubusercontent.com/91839403/145753031-e4bcc4de-6d65-4ac0-9bac-c69d97b3d9fc.png)

Corrected

![Results by type THS NaN](https://user-images.githubusercontent.com/91839403/145752357-83ce60d2-1777-4973-9089-3b4da4fefd92.png)


There is no mesurable difference between the results by school type of size.  


# Summary
The results from removing the 9th Grade data as Thomas High School are
1) Thomas HS dropped from the top 5 schools.
2) & 3) The Math and reading average scores dropped at Thomas High School as did the overall passing percent as a result of removing the 9th grade scores
4) THe passing percenteges dropped in the analysis by spending in the range  where THS resided .

THere does appear to be a real impact to the high test scores in the 9th grade at Thomas High School.  More analysis could be done looking at the mean and stnadard deviation of the students in 9th grade at THS.
There are other interesting insights related to size and spending.  Smaller schools spend less per student and appear to dproduce high testing scores in the students.  The relationship beteween those variables might offer insights to deliver improved resutls in all schools.  There is also a distinct difference in SIze, more analysys would be interesting here, data like teacher to student ratios could offer some insights as well.

#Conclusion
This was a challenging assignment.  Staying orgnized and structured was get to keeping all the code straight and aligned.  I also had issues processing due to data types and learned some valuable lessons ther as well.  I know to check .dtypes and how to set the type when needed for calculations.




