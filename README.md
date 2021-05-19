# Employee_Compensation_prediction

In this Regression problem statement we have to predict Total Compensation of Employees. This Dataset contains 25k datapoints with 14 Independent variables and 1 Dependent variables. The description of all the 14 features are:

OGC: Organization Group Code - Org Group is a group of Departments. For example, the Public Protection Org Group includes departments such as the Police, Fire, Adult Probation, District Attorney, and Sheriff.

OG: Organization Group names

DC: Department Code - Departments are the primary organizational unit used by the City and County of San Francisco. Examples include Recreation and Parks, Public Works, and the Police Department.

Dept: Department name

UC: Union Code - Unions represent employees in collective bargaining agreements. A job belongs to one union, although some jobs are unrepresented (usually temporarily).

Union: Union names

JF: Job Family - Job Family combines similar Jobs into meaningful groups.

Job: Job name

EI: Employee Identifier

Salaries: Salary of the employee

Overtime: Amounts paid to City employees working in excess of 40 hours per week. 

H/D: Health/Dental - City-paid premiums to health and dental insurance plans covering City employees. To protect confidentiality as legally required, pro-rated citywide averages are presented in lieu of employee-specific health and dental benefits. 

YT: Year Type - Fiscal (July through June) or Calendar (January through December)

Total_Compensation: The final compensation i.e. the sum of all salaries and benefits paid to City employees.

Some techniques used are:

a)Continuous Variable

1. EDA
  i.Distplot

2. Outlier Detection:
  i. Box Plot 

3. Feature Transformation:
  i. Cube root transformation
  ii. Log transformation
  iii. Interquantile range Method


b)Categorical Variable

1. EDA:
  i. Countplot

2. Feature Transformation:
  i. Mean Encoding
  ii. One Hot Encoding with many categorical
  iii. Label Encoding 

3. Feature Selection:
  i. Correlation

c)Model Fitting:
  i.Linear Regression
  ii.K Nearest Regressor
  iii.Decision Tree Regressor
  iv.Random Forest Regressor
  v.Xgboost Regressor
  vi.Lightgbm Regressor

d)Metrics:
  i.Mean_Absolute_Error
