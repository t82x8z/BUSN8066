java c
BUSN8066
Task 3. Reimbursement calculation method
Part I: Ask the right questions
Overview
QuantumOps Inc. uses a unique “high-human-touch” sales and servicing model. That is, QuantumOps Inc. sells only within certain cities and hires numerous sales agents and information technology (IT) agents in each city where it operates. The company then has these employees visit the customers to provide face-to-face sales and support. The model has been successful so far and QuantumOps Inc. now operates in five cities in the Midwestern United States: Indianapolis, Kansas City, Louisville, Nashville and St. Louis. Each city has a physical office staffed by a manager and customer support representatives. The office manager is responsible for and oversees all work done in the office. The customer support representatives field customer calls and send sales agents and IT service representatives to visit customers. When a customer support representative receives a call, they assign the employee who has not performed the task for the longest time. That way, every employee has an equal opportunity to visit customers.
QuantumOps Inc. pays employees for the time they are traveling to and visiting with customers. The company also reimburses employees when they travel to a customer’s business because employees use their own vehicles for transportation. After the trip, the employee submits their distance travelled for reimbursement. The employee submits their home address, the customer address and their self-reported distance that they traveled to visit the customer. The company then reimburses the employee using the Internal Revenue Service (IRS) standard rate.
The process of reimbursing employees has caused the CFO, Patrick Wang, major headaches. The employees’ submissions suffer from numerous data quality issues, including incomplete and inaccurate information. Entering the information into the system is error prone and data entry errors are common. Entering the data and fixing errors is time-consuming and adds little value to the company. In addition, a recent internal audit discovered that some employees were overclaiming the distance they traveled. The company has even noticed that employees seem to be moving farther away from customers since they are paid by the mile and reimbursed for their travel time. This wastes company resources and can reduce customer satisfaction because they may not receive prompt attention.
In sum, Patrick is frustrated with this process and wants you to help prepare an analysis that examines switching to a fixed-rate reimbursement plan rather than reimbursing per mile. With a fixed-rate reimbursement plan, the company would reimburse employees a fixed rate for every trip, regardless of the travel distance, rather than reimbursements based on the actual distance traveled. He has asked you to prepare data analytics dashboards and a report to help inform. the decision-making process.
To help you prepare your report, the IT department has compiled a list of the trips for the previous year. In total, employees sought reimbursements for 4,468 trips. The IRS reimbursement rate for this previous year was $0.575 per mile. The file labeled BUSN8066_S2_2024 Assignment 02 dataset – Task 3.xlsx contains the data. The following is a data dictionary for the items contained in the Excel file:
► CustomerName: the name of the customer the employee visited.
► CustomerAddress: the address of the customer the employee visited.
► EmpFullName: the name of the employee seeking reimbursement.
► EmployeeAddress: the address of the employee seeking reimbursement.
► EmployeeRole: the role the employee performs at the company. The employee can be assigne代 写BUSN8066 Task 3. Reimbursement calculation methodR
代做程序编程语言d to Sales or IT.
► Office: the office to which the employee is assigned. The possible offices include Indianapolis, Kansas City, Louisville, Nashville and St. Louis.
► TimeOfTrip: the time of day the employee made their trip. Note that this field contains “dirty” data. That is, the only meaningful item of data is the time stamp. The system inappropriately added a date to the time that has no meaning and should be ignored.
► ValidatedDistance: the IT department created a bot using robotic process automation to scrape the distance from the reported locations using Google Maps. This field contains the results from the bot showing the distance between the two locations.
Required:
Fixed-rate reimbursement plans can be implemented in various ways. For example, plans can use a single rate for the entire company, or different rates based on different factors (e.g., employee position, office location, time of day). Prepare a report that addresses the following:
a) the different factors that would be valuable in evaluating the various fixed-rate reimbursement plans.  
b) the pros and cons of using different factors to determine the fixed-rate reimbursement plan in general.
c) the pros and cons of using each of the specific factors you noted.
d) the criteria and considerations that the company can use to decide whether to use a fixed-rate reimbursement plan or not?
e) if the company chooses to use a fixed-rate reimbursement plan, how should it decide what the rate should be?
Please make sure your answer includes references to reliable sources that help support your arguments. 
(GROUP TASK)  Write your answers in the assignment document and label them as Q3_0.
Part II: Apply appropriate data analytics techniques 
Load the prepared file into your data visualization software (i.e. Tableau). With the data loaded into the visualization software, you are now prepared to answer Mr. Wang’s request.
Required
Prepare a memo for Mr. Wang that contains a clear recommendation about what to do related to the travel expense reimbursement. Your recommendation should be supported with data from the following dashboards. 
a) Dashboard 1: this dashboard should report how the office location, employee role and time of day influenced reimbursement costs in the past. Use the current travel expense reimbursement data to analyze these factors.
b) Dashboard 2: this dashboard should examine how offices and employees would be influenced by changes in the reimbursement rate. This dashboard should be dynamic (i.e., use dynamic parameters) so if the CFO wants to, he can change the reimbursement rate and see how the analyses change. Include calculations that show the difference between expenses incurred using the current travel expense reimbursement plan and potential flat-rate reimbursements. This dashboard should show how the costs per each office are affected by different reimbursement rates and how each individual employee will be affected by the changes.
Screenshots showing what the dashboards should look like are provided below.
(GROUP TASK)  Write your answer in the assignment document and label it as Q3.
(GROUP TASK)  Take screenshots of the Tableau visualisations that you prepared to help you answer the requirement, include them in the assignment document within the answers provided and label them as S3_a, S3_b1 and S3_b2. In your answers, you can reference the screenshots by those labels. 
Dashboard 1

Dashboard 2

For the second dashboard, it should also show the following tooltip display when a user hovers over any of the bars in the Per Office Differences visualization.




         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
