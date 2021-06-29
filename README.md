Analysis of the project
Data Cleaning
Importing necessary packages
reading the data
shape of the data is 1200*28 that is 1200 rows and 28 columns
the data has no null values
describing the data
Visualization
age of all the employees where 35-45 has more number of people in the company
male has more count than female in this company
the main part "perfomance rating" here 3 rating is very high and 2 and 4 rating is low percantage
barplot of BusinessTravelFrequency, DistanceFromHome, MaritalStatus, EducationBackground, TotalWorkExperienceInYears, ExperienceYearsInCurrentRole
clean analysis of employee department where sales and finance is low and here aged members are high compared to youngsters so in this department like finance and sales
remaining labels are in countplot of visualiztion can see indetail in visualization.ipynb
full analysis of job role where finance manager, senior manager r&d and sales perfomance is less
years since last promotion has very low grade
Modelling
drop unwanted columns that is employee number
do the labelencoding
x has remaining all features
y has perfomance rating
logistic regression accuracy score has 79% after pca it increased to 83%
Random Forest Classifier accuracy score has 82% and gridsearchcv implemented and taken best parameters
Support Vector Machine accuracy score has 73%
xgboost accuracy score has 86%
artifical neural network accuracy score has 82%
Requirement
The following insights are expected from this project.

Department wise performances
Top 3 Important Factors effecting employee performance
A trained model which can predict the employee performance based on factors as inputs. This will be used to hire employees
Recommendations to improve the employee performance based on insights from analysis.
1. Department wise performances
I have analysed this department wise perfomance and it has 6 sub departments the analysis is:

sales:- in this sales the perfomance is low when comapred to other departments and i think age factor affecting more
human resources:- in this department however perfomance is average and still to imporve it
Development:- here the perfomance is high and should keep in that way
Data Science:- here they are performing well and should keep the perfomance in that way only
research and development:-in this also perfomance is average
finance:- in this finance department perfomace is very low
2. Top three Important Factors effecting employee performance
Top factors which effcting employee perfomance

Years Since the last Promotion
Employee Salary Hike Percentage
training times last year
employee job level
Distance from home
3. A trained model which can predict the employee performance based on factors as inputs.This will be used to hire employees
logistic regression accuracy score is 83%
xgboost accuracy score is 87%
4. Recommendations to improve the employee performance based on insights from analysis.
The main part is years since last promotion many of the employee didnt get promoted,this will effect more on employee perfomance
In employee job role of all the sales department, finance and delivery department should boost their perfomance
experience years at current company is less so more number of years should stay in same company and that they will understand and get involved more in work
The experience years in current role need to be revised while offering the employment to the new employees.
here hike should be given more where employees perfomance can be increased
employees still should increase enviorment satisfcation, job satifaction , training times since last year
distance from home is more it will affect employee perfomance so if possible provide cabs to them
