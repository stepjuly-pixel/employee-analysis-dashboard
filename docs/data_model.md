# Data Model Notes

The Power BI model uses two source datasets from the [Employee/HR Dataset (All in One)](https://www.kaggle.com/datasets/ravindrasinghrana/employeedataset) on Kaggle:

- `employee_data`
- `employee_engagement_survey_data`

An additional table was created inside Power BI:

- `Calendar`

The Kaggle dataset is synthetic and fictional, designed for HR analytics and employee management practice. The `Calendar` table supports customized date logic and dynamic monthly trend visuals. Data cleaning and shaping were performed directly in Power BI, mainly through Power Query, without a separate SQL preparation step.

Main fields used in report visuals include:

- `employee_data.DepartmentType`
- `employee_data.EmployeeStatus`
- `employee_data.Performance Score`
- `employee_data.Terminated CNT`
- `employee_engagement_survey_data.EmpID`
- `employee_engagement_survey_data.Engagement`
- `employee_engagement_survey_data.Satisfaction`
- `employee_engagement_survey_data.Work-Life Balance`
- `employee_engagement_survey_data.% AverageEngagement`
- `employee_engagement_survey_data.% AverageSatisfaction`
- `employee_engagement_survey_data.% Average WL Balance`
- `Calendar.MonthYear`
