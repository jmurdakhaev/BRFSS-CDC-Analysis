# BRFSS Data Analysis Dashboards
Public health data collected by the CDC (https://www.cdc.gov/brfss/annual_data/annual_2023.html) was used to create an interactive Power BI dashboard with 3 pages - Physical Health, Mental Health, and Chronic Diseases. 
First the raw data was imported in Google Colab, where Python was then used to keep only the columns which would be used in the dashboard. 

![image](https://github.com/user-attachments/assets/e2eea707-0b83-4aac-b04f-c9e732b0ebb2)

The data was then exported into Excel and cleaned in order to connect it to Power BI. An important step here was to add an ordering column for the categorical variables such as Life Satisfaction, so that the visuals produced would order the variables correctly. Any emtpy or no-response entrys were deleted, and the file was ready to be imported. (See the cleaned Excel file in repo)

Next the dashboards were made in Power BI (see link in repo). Multiple new measures were made in order to create KPI percantage cards. An example is Percent Dissatisfied With Life:

![image](https://github.com/user-attachments/assets/a4eefc0b-d786-4458-b200-765db030b98a)

Similar DAX code was used for other new measures. 
Bellow are screenshots of the resulting dashboards. 

![image](https://github.com/user-attachments/assets/23b41f96-917f-47bd-9a5b-3dc89d35a06a)

![image](https://github.com/user-attachments/assets/b6f11b4d-4f0d-4a01-8f66-ae12930fc350)

![image](https://github.com/user-attachments/assets/f69506e9-0c94-4713-a4ae-a46ff320f241)

Some of the findings from these visuals include the link between General Health and Income, as well as General Health with Life Satisfaction. Variables such as Race and Education has significantly less of an affect on overal health and chronic diseases as did their Mental Health or Physical Health. 


