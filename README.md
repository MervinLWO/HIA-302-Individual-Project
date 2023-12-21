# HIA302 Individual Project

Horse Colic Dataset - Data Collection and Preparation\

Overview:\
This repository contains code and instructions for handling the Horse Colic dataset. The dataset comprises medical characteristics of horses affected by colic, focusing on predicting whether the issue was surgical or not.

Files Included:
- horse-colic.txt: Raw dataset file.
- horsecolic.names: Description file detailing the dataset's columns and attributes.
- horse-colic.csv: Converted dataset file in CSV format.
- horse-colic-with-NaN.csv: Updated dataset with missing values represented as NaN.
- horse-colic-with-title.csv: Dataset with updated headers as per the description file.
- README.md: Instructions and overview of the repository.

Tasks Accomplished:
- Converting Raw Data
- Demonstrated multiple ways to convert horse-colic.txt to horse-colic.csv.
- Verified the integrity of the CSV data in Jupyter Notebook.
- Handling Missing Values
- Replaced missing values ("?") with NaN in the loaded dataset using Python.
- Saved the updated dataset as horse-colic-with-NaN.csv.
- Header Renaming based on the description file.
- Saved the modified dataset as horse-colic-with-title.csv.
- Loaded horse-colic-with-title.csv and displayed the total NaN values per column.
- Visualized the NaN counts per column using a bar chart via Matplotlib.
- Retrieved the datatypes for each column in the dataset.
- Considered the impact of dropping NaN rows in the dataset.
- Code Evaluation
- Assessed and justified the method used in a code snippet to reduce missing values.
- Code Annotation
- Provided inline comments in the code file to explain missing sections and steps.

Conclusion:\
The tasks performed include data conversion, handling missing values, data visualization, and code evaluation. The dataset is now prepared for further analysis and machine learning tasks.
