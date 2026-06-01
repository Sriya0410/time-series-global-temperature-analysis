# Time-Series Analysis of Global Temperature Data

## Project Overview

This project is completed as part of the **IDEAS Summer Internship Program 2026**. The main objective of this project is to analyze global temperature data using Python time-series techniques and to perform K-Means clustering on digit data.

The project is implemented in a Jupyter Notebook and includes data loading, preprocessing, date-time conversion, moving average calculation, grouping, pivot table creation, clustering, and evaluation using Macro F1 Score.

## Project Title

**Time-Series Analysis of Global Temperature Data**

## Dataset Used

### 1. Global Temperature Dataset

The dataset used for temperature analysis is:

`monthly_csv.csv`

This dataset contains global temperature records with the following main columns:

* `Source`
* `Date`
* `Mean`

This dataset is used for Questions 1 to 10.

### 2. Digits Dataset

The digits dataset is loaded directly from Scikit-learn using:

```python
from sklearn.datasets import load_digits
```

This dataset is used for K-Means clustering in Questions 11 to 13.

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* SciPy
* Jupyter Notebook

## Tasks Performed

The following tasks are completed in this project:

1. Imported required libraries.
2. Loaded the global temperature dataset.
3. Converted the `Date` column into datetime format.
4. Sorted the dataset based on the `Date` column.
5. Checked the dataset shape and missing values.
6. Extracted `Year` and `Month` from the `Date` column.
7. Calculated 12-month moving average temperature for each source.
8. Filtered the dataset for the last 20 years.
9. Grouped the data by `Source` and calculated average temperature.
10. Calculated yearly average temperature.
11. Found the hottest month on average.
12. Created a pivot table for year-wise and month-wise temperature analysis.
13. Loaded the digits dataset from Scikit-learn.
14. Applied K-Means clustering with 10 clusters.
15. Evaluated clustering performance using Macro F1 Score.

## Results

* The dataset contains **3288 rows and 3 original columns**.
* No missing values were found in the dataset.
* The dataset was successfully sorted by date from the year 1880.
* A 12-month moving average was calculated for temperature trend analysis.
* The last 20 years of temperature data were filtered successfully.
* The hottest month on average was found to be **October**.
* K-Means clustering was applied successfully on the digits dataset.
* The Macro F1 Score obtained for clustering was:

```text
0.7894620863890832
```

## Files in this Repository

* `07_Time_Series_Analysis_of_Global_Temperature_Data_Spring_2026.ipynb`
* `monthly_csv.csv`
* `README.md`

## How to Run the Project

1. Open the notebook file:

```text
07_Time_Series_Analysis_of_Global_Temperature_Data_Spring_2026.ipynb
```

2. Make sure `monthly_csv.csv` is present in the same folder as the notebook.

3. Run all cells in the notebook.

4. Verify that all outputs are generated without errors.

## Internship Program

**IDEAS - Institute of Data Engineering, Analytics and Science Foundation**
**Summer Internship Program 2026**
