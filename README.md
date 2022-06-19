# Wine_Store_DB

## Objective
Create a database of wines that have a quality score of at least 7 for an online store. The manufacturer of the available wines will be hidden prior to checkout to prevent bias. The goal is to have customers choose wines based on the quality score, alcohol content, and wine color.  

- Quality: Graded from 0 (very bad) to 10 (very excellent)
- Alcohol: Percentage of alcohol content.
- Color: Red and white wines are available.  Heavy wines generally have a deeper color.

## Tasks
1. Import red and white wine csvs to Jupyter Notebook for analysis.
2. Create a Pandas DataFrame from the red and white wine csvs.
3. Clean DataFrames to remove any rows missing data.
4. Add a column for wine type to both DataFrames.
5. Filter both DataFrames for a quality score that is at least 7.
6. Merge the 2 DataFrames together.
7. Export the merged DataFrame to pgAdmin 4.
8. Create tables in pgAdmin 4 based on alcohol content.

## Resources
### Tools
- jupyter notebook
- pgAdmin 4
- visual studio code
- python
- pandas

### Data
- Wine Datasets (https://archive.ics.uci.edu/ml/datasets/Wine+Quality)


