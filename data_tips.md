# Data Collection and Management

Data collection and management is the most important part of the research process. 
Below is a minimum set of rules you should follow:

## Tidy data
Your dataset should look **[tidy]([url](https://openscapes.org/blog/2020-10-12-tidy-data/))**

![tidy-data](https://github.com/user-attachments/assets/081ba1fc-e5df-48e5-a095-6182167ae316)

**Why?**
Tidy data allows you to be more efficient by using existing tools deliberately built to do the things you need to do,
![tidydata_2](https://github.com/user-attachments/assets/15952ab1-7a94-4420-b743-a81c49993358)
Tidy data makes it easier to collaborate
![tidydata_3](https://github.com/user-attachments/assets/28c9d820-8356-4774-b2cc-35845744b929)
Tidy data also makes it easier to reproduce analyses because they are easier to understand, update, and reuse.
![tidydata_5](https://github.com/user-attachments/assets/6e04ca30-9ab7-474f-866f-c6fe2935576f)


## Basics of Research Data Management: Tabular Data (Spreadsheets)

1. **Separate the data entry phase from the data analysis phase**  
   - **Wrong**: Enter the data in Excel and use Excel for analysis.  
   - **Right**:  
     - Create a form, such as Google Forms, for data entry.  
     - Export the data for analysis using tools like:
       - [JASP](https://jasp-stats.org/) or [JAMOVI](https://www.jamovi.org/) for basic data analysis.  
       - [R](https://www.r-project.org/) for advanced analysis or creating visualizations.

1. **Original Data**  
   - Ensure the original data is preserved and stored separately from processed data.
   - DO NOT TOUCH THE ORIGINAL DATA!

1. **Rows and Columns**  
   - Rows are for observations.  
   - Columns are for variables.  
   - Keep the **data type** the same within a column:  
     - Numbers: Distinguish between integers and decimals.  
     - Text: Ensure uniform formatting.  
   - Avoid having more than one table per spreadsheet.  

1. **Be Consistent**  
   - Use consistent codes for categorical variables.  
   - Use a fixed, consistent code for missing values.  
   - Use consistent subject identifiers.  
   - Use consistent date formatting.  

1. **No Empty Cells**  
   - If data is missing, explicitly encode it as missing (e.g., use `NA` or another agreed-upon value).  
   - Avoid headers with more than one row.
   - BAD:
   -  ![Screenshot from 2025-01-10 10-29-10](https://github.com/user-attachments/assets/72ce7750-3827-4293-95c1-0473ac26fae7)
   - GOOD:
   - ![Screenshot from 2025-01-10 10-30-13](https://github.com/user-attachments/assets/a45bfe4c-e234-4b17-aa4a-fb6161510564)

1. **Choose Good Names for Things**  
   - **Variable Names**:  
     - Avoid spaces and avoid starting with numbers.  
     - **Do**: Use numbers and letters.  
     - **Avoid**Special characters and symbols.  
     - **Do**: Use underscores (`_`) instead of spaces.  
   - Use both an **internal column name** and a **displayed name**:  
     - Example: Internal column name `max_temp`, displayed name `Maximum Temp (°C)`.
      ![Screenshot from 2025-01-10 10-33-10](https://github.com/user-attachments/assets/b242a3ec-4c87-4e9b-abad-998e798d84e5)

1. **Put Just One Thing in a Cell**  
   - Avoid combining multiple columns into a single column.  
   - Avoid placing multiple bits of information in a single cell.
  
![Screenshot from 2025-01-10 10-34-01](https://github.com/user-attachments/assets/9e97dd12-50bd-4bfb-a443-845fd5178b21)



1. **Write Dates as YYYY-MM-DD**  
    - Avoid formats like DD-MM-YYYY, which can lead to inconsistencies.
    - Convert `YYYY-MM-DD` to text to preserve formatting when loading data.  
    - Alternatively, store dates as an integer in the format `YYYYMMDD`.
  
## Readings

- **Data Organization in Spreadsheets**  
  [Link to article](https://www.tandfonline.com/doi/full/10.1080/00031305.2017.1375989#abstract)

- **Grolemund, G. & Wickham, H. (2016). *R for Data Science: Chapter 12 (Tidy Data)***  
  [Link to book](https://r4ds.had.co.nz)

- **How to Share Data for Collaboration**  
  [Link to article](https://peerj.com/preprints/3139/)

- **Eleven Quick Tips for Properly Handling Tabular Data**  
  [Link to article](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1012604)


## Tools

- **OpenRefine for Data Cleaning**  
  [Watch a 5-minute tutorial](https://www.youtube.com/watch?v=nORS7STbLyk)



      
