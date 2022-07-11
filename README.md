# mechacar_statistical_analysis

Deliverable 1: Linear Regression to Predict MPG

1. Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
Vehicle length and ground clearance. 

2. Is the slope of the linear model considered to be zero? Why or why not?
The slope of the linear model is not zero because the R-squared is not zero. 

3. Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
This linear model predicts mpg of MechaCar prototypes effectively because the r value is greater than .5. 

Deliverable 2: Summary Statistics on Suspension Coils

The design specifications for the mechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually?

In total, all three lots meet the design specifications, with a variance of 62. Individually, Lots 1 and 2, meet this design specification. Lot 3 does not, with a variance of approximately 170. 

<img width="337" alt="Screen Shot 2022-07-11 at 2 21 33 AM" src="https://user-images.githubusercontent.com/79942792/178210252-a0fbfede-0499-4656-b5b8-549ba92114bc.png">

<img width="496" alt="Screen Shot 2022-07-11 at 2 26 57 AM" src="https://user-images.githubusercontent.com/79942792/178210979-f5261fa4-65b0-418a-a935-40ccc59e76f7.png">



Deliverable 3: T-tests on Suspension Coils

<img width="462" alt="Screen Shot 2022-07-11 at 2 35 39 AM" src="https://user-images.githubusercontent.com/79942792/178212489-753a0dc0-d792-45b9-8042-46efea97d707.png">

Lot 1: 

<img width="695" alt="Screen Shot 2022-07-11 at 2 37 18 AM" src="https://user-images.githubusercontent.com/79942792/178212701-94cf8ffc-c0e8-482f-af8f-db3beb68bbc7.png">

Lot 2: 

<img width="689" alt="Screen Shot 2022-07-11 at 2 39 44 AM" src="https://user-images.githubusercontent.com/79942792/178213136-36b25366-4c42-4d21-9545-093925f391d7.png">

Lot 3:

<img width="696" alt="Screen Shot 2022-07-11 at 2 40 43 AM" src="https://user-images.githubusercontent.com/79942792/178213352-5779f97e-ebc4-4fcc-9d3c-a6b706cff425.png">



#Deliverable 4: Study Design: MechaCar vs Competition

1. What metric or metrics are you going to test?

Vehicle weight and mpg

2. What is the null hypothesis or alternative hypothesis?

Null hypothesis: There is no significant difference in mpg based on vehicle weight.  

Alternative hypothesis: There is a significant difference in mpg based on vehicle weight. 

3. What statistical test would you use to test the hypothesis? And why?
I would use the linear regression because I am looking to assess if the vehicle's mpg is affected by the vehicle weight. 

4. What data is needed to run the statistical test?
The mpg and the vehicle weight. 
