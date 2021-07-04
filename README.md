# **Stocky Analysis Visual Basic for Applications (VBA)**

 ## Overview of Project

This project has the objective of restructuring an existing code.

### Purpose
The purpose of this project is to improve the structure and design of a previous code to streamline its functionality. 

### Data Source Information
 The dataset source offers a variety of stocks for the years of 2017 and 2018. The information of this dataset is divided into opening stock prices, high and low prices within the day, closing price and the total volume negotiated. 
Previously, the dataset was manipulated to offer an information in stock price variation within a year. The code created, was refactored to improve its performance. Using the run time of the macro as measurement of success, the comparison of run time will demonstrate whether code efficiency was achieved. 

### Results 
The refactored code showed improvements in the run time of the code when compared with its previously version. There main factor of the improvement was the addition of an index. The index provided the code easy access to all of the arrays which allowed the code to run two loops without the need of a nested loop.
Organizing the code to run without a nested loop has streamlined it allowing more efficiency throughout the process. Below are the results achieved:


Original Code (Nested Loop) – In the picture below the loop J is inside loop I, meaning that an outcome will be generated after both loops finish their iterations. 
 





Refactored Code (Separated Loop) – The picture below shows two loops separated. The first loop will generate an outcome and then the code will continue to run triggering the second loop. The number of iterations will decrease based on the fact that the first code generates an outcome before the second loop starts.  
 
![Refactored code](https://user-images.githubusercontent.com/86136535/124400450-7ea5f800-dcf0-11eb-919e-bd5406d7bba4.png)


 Run Time Results:


2017 Before	2017 After
 	 
 
2018 Before	2018 After
 	 


### Summary
##Advantages
Although the improvements in run time presented an advantage when running large datasets, refactoring will also improve the design of the code which allows for easier readability and helps to identify bugs.
Another important aspect of refactoring is the support of code development. Dedicating time to enhance the code will bring new features and ideas for future projects developing a continuous learning process that is beneficial to all parts involved in a project.

##Disadivantages
Code refactoring may also present some disadvantages related to time and cost of refactoring. In large code sets, the time needed to complete the task can be unpredictable due to the its complexity and the cost involved in the refactoring will be proportional to the time needed to complete the task. Another aspect is that depending on the complexity of the code, it can lead to mistakes that will potentially increase the amount of time to refactor, to identify bugs and deploy a fix.


