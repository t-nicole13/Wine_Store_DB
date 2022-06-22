# Wine_Store_DB

## Objective
Create a database of wines that have a quality score of at least 7 for an online store. The manufacturer of the available wines will be hidden prior to checkout to prevent bias. The goal is to have customers choose wines based on the quality score, alcohol content, and wine color.  

- Quality: Graded from 0 (very bad) to 10 (very excellent)
- Alcohol: Percentage of alcohol content.
- Color: Red and white wines are available.  Heavy wines generally have a deeper color.

## Tasks
1. Import red and white wine csv files to Jupyter Notebook for analysis.
2. Create a Pandas DataFrame from the red and white wine csv files.
3. Clean DataFrames to remove any rows missing data.
4. Add a column for wine color to both DataFrames.
6. Concat the 2 DataFrames together.
7. Filter new DataFrame for a quality score that is at least 7.
8. Export the concated DataFrame to a new csv file and import into pgAdmin 4.
9. Create tables in pgAdmin 4 based on quality score, alcohol content, and wine color.

## Resources
### Tools
- jupyter notebook 6.4.5
- pgAdmin 4
- visual studio code 1.67.2 
- python 3.9
- pandas 1.3.4

### Data
- Wine Datasets (https://archive.ics.uci.edu/ml/datasets/Wine+Quality)


