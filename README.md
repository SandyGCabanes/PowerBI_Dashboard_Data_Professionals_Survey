# PowerBI_Dashboard_Data_Professionals_Survey

As with all dashboards, my dashboard is also interactive.  You can click on any color in the Gender chart for a Gender sub-group, or in the Country chart for a country sub-group.

## [Here's the walk-through of the dashboard]  
[(https://github.com/SandyGCabanes/PowerBI_Dashboard_Data_Professionals_Survey/blob/main/powerbi_dataprofessionals_survey.gif)]

### Dataset Imported using PowerQuery and Transformations Done as follows:
-- Removed non-useful columns

-- Others: Specify truncated to Others by Split Column option, Custom delimiter = (
-- Second column after delimiter is deleted
-- Applied to columns: Titles, Industry work in, Favorite program, Country Live In

-- Salary ranges: Split Column by delimiter, two new columns created as lower and upper salary 
-- Character 'k' removed using Replace Values
-- New lower and upper range columns formatted as Whole Number
-- Highest bin 225+ will have both lower and upper range as 225 for the average
-- Custom Column Salary Average using (New Lower salary and New Upper salary) / 2

##### Link to the dataset here -> https://github.com/AlexTheAnalyst/Power-BI/blob/main/Power%20BI%20-%20Final%20Project.xlsx

##### Huge thanks to [@AlexTheAnalyst](https://www.youtube.com/watch?v=g0m5sEHPU-s) and his youtube channel for guiding this project.
