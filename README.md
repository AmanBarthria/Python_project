# Python Data Cleaning & Analysis

## Project Overview
This project demonstrates data cleaning and analysis using Python, Pandas, and NumPy. The notebook covers CSV data loading, dataset exploration, missing-value handling, table merging, average calculations, and data export.

## Project Notebook
[**Python Data Cleaning & Analysis – Jupyter Notebook**](https://github.com/AmanBarthria/Python_project/blob/main/Python_Data_Cleaning_Analysis.ipynb)

## Tools and Libraries
- Python
- Pandas
- NumPy
- Jupyter Notebook

## Key Tasks Performed
- Loaded and explored CSV data.
- Handled selected values during data cleaning.
- Merged tables using `pandas.merge()` and a common key.
- Calculated averages for selected columns.
- Prepared and exported the processed dataset.

## Input Data
The project uses CSV data as its input. The required source CSV file or files are not currently listed in this repository. To reproduce the analysis, provide the original input data and ensure the file paths in the notebook point to the correct locations.

## Data Cleaning Rule
The notebook includes a zero-replacement step for selected columns. Zero should only be replaced where the project’s data-cleaning logic considers it appropriate; zero is not automatically an invalid value in every column. The affected columns and replacement value should follow the corresponding code cell in the notebook.

## How to Run the Notebook
1. Install Python and Jupyter Notebook, or open the notebook in Google Colab.
2. Install the required libraries:

   `pip install pandas numpy`

3. Open `Python_Data_Cleaning_Analysis.ipynb`.
4. Make the required CSV input files available and verify their file paths.
5. Run the notebook cells in order from a fresh kernel.
6. Review the cleaning, merging, average-calculation, and output cells.

## Output
The notebook processes the input data and performs the cleaning and analysis steps described above. The final output depends on the source data and the operations executed in the notebook.

## Learning Outcomes
This project demonstrates practical experience with Python-based data preprocessing, CSV handling, missing-value treatment, table merging, numerical calculations, and preparing data for further analysis.
