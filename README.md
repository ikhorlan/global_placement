# global_placement
The dataset is from Kaggle https://www.kaggle.com/datasets/rakesh630/global-student-placement-2025-dataset
The dataset contains around 10000 entries and 13 columns, including Cumulative GPA, college tier, university ranking, internship count and quality score, aptitude score and communications scores, placement status and salary. 
The goal of the dataset analysis was to look at what factors impact placement status and salary levels. 
Using the crosstab method, I looked if variables such as CGPA, agility, communication score, university ranking or college tier impact salary and placement status.
Linear regression: the non-numerical variables such as college tier, university ranking, aptitude and communication were transferred to numerical. I used sklearn libraries to run linear regression. Two variables of salary and placement were the study variable. The variable with the highest association with the salary increase are CGPA, internship count and internship quality score. 
