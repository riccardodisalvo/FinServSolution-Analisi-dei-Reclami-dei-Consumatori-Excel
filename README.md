# Project Overview

This project involves working with a dataset of user complaints submitted to financial management companies. The dataset contains various columns that provide insights into customer satisfaction and complaint management. Your task was to organize the data and create specific analytical sheets based on given requirements.

# The Dataset
 
 The Excel file contains a database of user complaints with the following columns:
 
 - **Date received:** The date when the complaint was received, formatted as YYYY-MM-DD.
 - **Product:** The product category related to the complaint.
 - **Sub-product:** The sub-category of the product.
 - **Issue:** A broad description of the problem.
 - **Sub-issue:** Detailed description of the problem.
 - **Consumer complaint narrative:** Description of the problem's context.
 - **Company public response:** The company’s response to the complaint.
 - **Company:** Name of the company.
 - **State:** The U.S. state abbreviation where the issue occurred.
 - **ZIP code:** Postal code.
 - **Tags:** Tag identifying the category of the complainant.
 - **Submitted via:** The method used to submit the complaint.
 - **Date sent to company:** The date when the complaint was sent to the company, formatted as YYYY-MM-DD.
 - **Company response to consumer:** The company’s response to the complaint.
 - **Timely response?:** A boolean variable indicating whether the response was timely.
 - **Complaint ID:** Unique identifier for the complaint on the platform.

 - 
 # What You Need to Do
 
 ## 1. **Consumer Complaints Sheet**
 
 **Name:** `Consumer complaints`
 
 **Style:**
 
 - The header row should use **Comics Sans MS**, **12pt**, **blue** color, and have a **double border** on all sides.
 - Each non-header cell should have a **black border** on all sides with a **thin border**.
 - No empty cells outside the table (they should be filled with white with no borders or lines).
 - Dates in columns **Date received** and **Date sent to company** should be in the format `dd/mm/yy`.
 - Add a column at the end showing the number of actual days between the date the complaint was sent and the date it was received.
 - Sort the rows in ascending order by **Complaint ID**.
 - Apply a filter on the **Date received** column to only show rows with dates before August 8, 2016.
 
 ## 2. **Geographical Insights Sheet**
 
 **Name:** `Geographical insights`
 
 **Style:**
 
 - The header row should use **Comics Sans MS**, **12pt**, **blue** color, and have a **double border** on all sides.
 - Each non-header cell should have a **black border** on all sides with a **thin border**.
 - No empty cells outside the table (they should be filled with white with no borders or lines).
 - The header row contains the following titles:
   - **Number of complaints per state**
   - **Percentage of complaints per state**
 - Column B shows the number of complaints per state from the `Consumer complaints` tab (Hint: use the `COUNTIF` function).
 - Column C shows the percentage of complaints per state, rounded to the nearest whole number. Cells should be **green** if the percentage is less than 2%, and **red** otherwise (Hint: use conditional formatting).
 
 ## 3. **Statistical Insights Sheet**
 
 **Name:** `Statistical insights`
 
 **Style:**
 
 - The header row should use **Comics Sans MS**, **12pt**, **blue** color, and have a **double border** on all sides.
 - Each non-header cell should have a **black border** on all sides with a **thin border**.
 - No empty cells outside the table (they should be filled with white with no borders or lines).
 - The header row contains the title:
   - **Distinct issues**
 - Column A lists all distinct issues from the **Issues** column in the `Consumer complaints` tab.
 - Cell B7 shows the **mode** (the most frequent issue) among all complaint categories (Hint: count occurrences of issues and find the mode).
