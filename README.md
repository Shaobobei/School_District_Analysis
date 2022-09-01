# School_District_Analysis

Maria and her supervisor has been tasked by the school borad to find out find if there are any evidence of academic dishonesty; specifically, reading and math grades for Thomas High School for the ninth graders, the grades appear to have been altered. We want to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once math and reading scores has been replaced, we will repeat the school district analysis that we did before and write up a report to describe how these changes affected the overall analysis.

## Resources used 
Data Source: schools_complete.csv, students_complete.csv

Software: Anaconda, Jupyter Notebook, Python, Pandas

## Results:

### How is the district summary affected?
**Before**
![district_summary_before](https://user-images.githubusercontent.com/107021649/187833285-ca0e1de3-de63-4302-8735-024e5af9fde2.png)
**After**
![district_summary_after](https://user-images.githubusercontent.com/107021649/187833283-a61199a1-2344-4322-8e16-8cd4e6b2cb8f.png)
•	Overall, reading and math percentage dropped a few decimal points.

### How is the school summary affected?
**Before**
![school_summary_before](https://user-images.githubusercontent.com/107021649/187833214-67e7d9a3-559a-4216-b10d-684fe53b86c0.png)
**Ater**
![school_summary_after](https://user-images.githubusercontent.com/107021649/187833160-a58f2fa7-f173-4615-8139-918205c206eb.png)

•	Math dropped from 93.27 %to 66.9%

•	Reading dropped from 97.3% to 69.6%

•	Overall pass dropped from 90.9% to 65%


### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
**Before**
![top_and_bottom_before](https://user-images.githubusercontent.com/107021649/187843342-f0d2aa7c-d8bf-4233-84eb-bf6c7d2aaf7c.png)
**After**
![top_and_bottom_after](https://user-images.githubusercontent.com/107021649/187843341-8b8ea3fc-4631-4313-a1ca-36e76bfa7bb6.png)

•	The percentage only dropped by a few decimal points, no significant change 


### How does replacing the ninth-grade scores affect the following:

•	**Math and reading scores by grade**

 ![reading_math_after](https://user-images.githubusercontent.com/107021649/187871890-bc290e71-0423-4461-a7de-7678d883006b.png)
  
   Now the 9th graders dont have a score, it has been replaced by "NAN"

•	**Scores by school spending**

 no significant change 
 
•	**Scores by school size**

   no significant change 
  
• **Scores by school type**

   no significant change 
 

## Summary
After replacing the math and reading scores for ninth graders at Thomas High School with NaNs , seems like the only noticeable different was on the individual school level. The percentage of overall, reading and the math scores dropped significantly. Went from all in the 90 percentiles to the 60 percentiles, that is about a 40 percent different! But when it came to the district level and the overall ranking of the schools, surprisingly there was not much difference, both only slightly dropped by a few decimal points. So overall, I dont know if this is "evidences" of academic dishonesty on Thomas High School's part or an oversight; because the slight difference didn't changed the overall analysis
