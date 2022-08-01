# Wine_Store_DB

## Objective
Create a database of wines that have a quality score of at least 7 for an online store.  The goal is to keep track of the available wines based on the quality score, alcohol content, and wine color.  

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

## Samples of the Database Tables
### Quality Score 7
![Getting Started](images/quality_7.png)

### Quality Score 8
![Getting Started](images/quality_8.png)

### Quality Score 9
![Getting Started](images/quality_9.png)

### Alcohol Content Between 10 and 10.9
![Getting Started](images/alc_ten.png)

### Alcohol Content Between 12 and 12.9
![Getting Started](images/alc_12.png)

### Alcohol Content Between 14 and 14.9
![Getting Started](images/alc_14.png)

### Color Red
![Getting Started](images/red.png)

### Color White
![Getting Started](images/white.png)


## Row Count of Database Tables
### Quality Score 7 Count
![Getting Started](images/q7_count.png)

### Quality Score 8 Count
![Getting Started](images/q8_count.png)

### Quality Score 9 Count
![Getting Started](images/q9_count.png)

### Alcohol Content Between 8 and 8.9 Count
![Getting Started](images/a8_count.png)

### Alcohol Content Between 9 and 9.9 Count
![Getting Started](images/a9_count.png)

### Alcohol Content Between 10 and 10.9 Count
![Getting Started](images/a10_count.png)

### Alcohol Content Between 11 and 11.9 Count
![Getting Started](images/a11_count.png)

### Alcohol Content Between 12 and 12.9 Count
![Getting Started](images/a12_count.png)

### Alcohol Content Between 13 and 13.9 Count
![Getting Started](images/a13_count.png)

### Alcohol Content Between 14 and 14.9 Count
![Getting Started](images/a14_count.png)

### Color Red Count
![Getting Started](images/rd_count.png)

### Color White Count
![Getting Started](images/wh_count.png)
