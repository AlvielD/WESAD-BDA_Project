# WESAD-BDA_Project

## Data
The data used for this project can be downloade from the UCI Machine Learning repository [here](https://archive.ics.uci.edu/dataset/465/wesad+wearable+stress+and+affect+detection).

## Usage
The `/src` folder contains two python notebooks.
1. data_to_parquet.ipynb - Used to convert the original pickle data to parquet, which is better supported for PySpark
2. WESAD.ipynb - Initiates HDFS, YARN and solves the classification task using different Machine Leaning algorithms contained on Spark's MLlib

## Documents
The repository contains a report (`/docs/WESAD_report.pdf`). It is highly suggested to read it in order to get a full view of the project.
