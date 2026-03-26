## Wrangling Process 

# Climate Data NL Jan 2016-2026
There are many pages within this excel sheet, making it a legthy task to clean. Using tableau prep, the pages were joined together to create one dataset. Cleaning and Unioning 11 pages of data led to some repetiviness in some columns which then hasd to be deleated. Using the legened from the Government of Canada website, the acronyms for each column title were changed to more understandable title names (Ex. Tm = Mean Temperature). 

# Electric Power Generation by Type 
Firstly, Dates were edited in Excel using the "replace" function to add the year to the date rows. Once this was done, each date was formated as "mm/dd/yyyy". The data was provided in horozontal format which was not compatable with Tableau Prep, so this miust be changed so the values will show when creating visualizations. To fix this, the data was pivoted so information headers (such as "Date" and "Types of Electricity Generation") would apear as column titles. After this, multiple columns were deleated as they contained null values as certain forms of electric power generation are not present in Newfoundland and Labrador (Ex. Solar Power). 

# Newfoundland Hydro Financial and operational data
This data was primarily sorted by hand, as all the information came from separate pdf documents. All missing null values from the data were removed. This tactic was chosen because there were minimal null values in the sheet.

# Energy Usage Newfoundland 

