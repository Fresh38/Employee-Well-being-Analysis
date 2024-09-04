I checked for missing values in the dataset
DAILY_STRESS column has a row with one missing value. • I dropped columns which I think are irrelevant for the analysis. 
Employee_ID and JOB_ROLE: Was likely irrelevant for predicting work-life balanceConvert string datatypes to numeric. 
I Performed data transformation of certain 
attributes (Hint: Age, Gender, etc.) 
I converted age and gender ranges from object data types to numerical values. 
Age was converted by categorizing the ranges as follows: 21 to 35 → 1, 36 to 50 →2, 51 
to 65 → 3, 65+ → 4 
GENDER was converted by setting 'Male' and 'Female' to 0 and 1, respectively. After converting there were missing values which were dropped. 
 
 
• Secondly, I plotted two distinct bar charts and showed the daily stress that employees 
experience, according to (1) gender
To determine also who dedicates more time to their hobbies: men or women? Finally, I built a heatmap to determine the attributes to which WLB score is 
highly correlated to.  
I performed a correlation analysis to see which variables are more correlated with the Work life balance (WLB) score
Negative correlations were from: 
DAILY_STRESS (-0.36) 
BMI_RANGE (-0.28) 
LOST_VACATION (-0.27) 
Positive correlations were observed with:  
ACHIEVED_BIG_PROJECTS (0.5) 
DAYS_ABSENT (0.5) 
WORK_TRAVELS (0.5) 
TODO_COMPLETED (0.5) 
TIME_FOR_HOBBY (0.5) 
TEAM_SIZE (0.5)
for Predictive wellbeing algorithm , usig the same dataset. I started by importing the relevant libraries for Machine learning 
I prepared and cleaned the data: Converted Age and gender range to numeric data types from 
string data type using mapping. For job role, I looked for the unique values in the column 
converted the roles by representing the range into numbers. I removed null values. 
To train the model I split the dataset in training 70% and testing sets 30% with the help of 
Linear regression function: 
Dropped WLB score column 
1) Predicted WLB score for a new employee is 608.16, whereas real WLB score is 
655.6
(2) model evaluation: printing the r2_score, 
by (3) presenting in a tabular form the difference between the real value found in the dataset 
and the predicted value by the trained model, 
few steps that the FAU Bank culd take to improve employees' score.  
1. By implementing Performance management scores by implementing regular 
feedbacks with surveys and follow-up steps to improve grey areas highlighted 
2. By paying competitive compensations and benefits rates 
3. Enabling employees to fairly distribute their work hours
# Employee-Well-being-Analysis
