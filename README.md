# Midterm Lab Task 2 – Data Cleaning and Transformation Using Power Query Editor

## Task Description:
This task involves cleaning, transforming, and analyzing a dataset of job listings using Power Query in Excel. The process is structured to ensure the data is accurate, organized, and ready for meaningful insights.

## Dataset before doing Cleaning and Transformation
![Image](https://github.com/user-attachments/assets/466df955-d6c7-477e-ae53-7c2fe2c35d3f)

## Steps perform in Data Cleaning and Transformation

**1. Load Data into Excel**

- Go to Data → New Query → Open File → Select CSV → Load and Edit in Power Query Editor.

**2. Data Cleaning Steps**

- Duplicate Raw Data for backup.
  
- Salary Estimate Column: Extract text before (.
  
- Min Sal & Max Sal Columns: Use Column from Examples to extract salary ranges.
  
- Role Type Column: Create a custom column with conditions for common job roles.
  
- Location Correction Column: Add custom logic to standardize locations and split by , delimiter.
  
- Handle Outliers: Filter and correct values in relevant columns like competitors, revenues, and industry.
  
- Company Name Cleaning: Remove extra text (like ratings) from company names.
  
- Remove Descriptions Column for clarity.
  
**3. Data Transformation and Grouping**

Duplicate Data for Salary Analysis:

- Select Role Type, Min Sal, and Max Sal.
  
- Convert salaries to currency and multiply by 1000.
  
- Group by Role Type and calculate average salaries.
  
Reference Data for Salary by Company Size:

- Select Size, Min Sal, and Max Sal.
  
- Convert salaries to currency and multiply by 1000.
  
- Group by Size and calculate average salaries.
  
**4. Mapping State Data**

- Import State Mapping workbook.
  
- Merge state abbreviations with full names.
  
- Filter out null or blank values.

**5. Reference Data for Salary by State**

- Select State Full Name, Min Sal, and Max Sal.
  
- Convert salaries to currency and multiply by 1000.
  
- Group by State Full Name and calculate average salaries.

## Final Output
![Image](https://github.com/user-attachments/assets/ff7dd7a2-c895-470f-a6bc-34bf085c2bcc)
**Sal By Role Size Ref**
![Image](https://github.com/user-attachments/assets/8d159a0b-ce35-4a3c-8efa-863813676a68)
**Sal By Role Type Dup**
![Image](https://github.com/user-attachments/assets/b8a7a1dc-4120-4099-a532-a38f6a27f89b)
**Sal By Size Role Type Ref**
![Image](https://github.com/user-attachments/assets/e53f43c8-d438-402b-af73-2be6f96f0874)
**Sal By State Ref**
![Image](https://github.com/user-attachments/assets/9d0d38f6-7906-4e39-ac82-23b3f273199c)
**Data Query Structure**
![Image](https://github.com/user-attachments/assets/ec43673a-df24-4b57-8269-244a1119b468)
**Advance Editor**
![Image](https://github.com/user-attachments/assets/ce96b5a5-ce52-4fe7-9497-ea22108b318f)
