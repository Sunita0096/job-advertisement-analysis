# job-advertisement-analysis

This project involves parsing, cleaning, and integrating job advertisement data from multiple sources. It includes the following tasks:

- **Task 1**: Parsing job advertisement data from XML format into a pandas DataFrame.
- **Task 2**: Cleaning the parsed data to ensure data quality and consistency.
- **Task 3**: Integrating the cleaned data with another dataset and resolving any conflicts.

## Project Structure

```plaintext
job-advertisement-analysis/
│
├── data/
│   ├── dataset1.xml                      # Initial dataset in XML format
│   └── dataset2.csv                      # Second dataset in CSV format
│
├── notebooks/
│   ├── task1_2.ipynb                     # Jupyter notebook for Task 1 and Task 2
│   └── task3.ipynb                       # Jupyter notebook for Task 3
│
├── dataset1_solution.csv                 # Cleaned dataset after Task 2
├── dataset_integrated.csv                # Integrated dataset after Task 3
├── errorlist.csv                         # Error list file 
└── README.md                             # Project readme file
