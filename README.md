# LSTM-Based-Malicious-Traffic-Detection
project focuses on leveraging Long Short-Term Memory (LSTM) neural networks for the identification of malicious network traffic.

## Prerequisites
-   Sklearn
-   Pandas
-   Numpy
-   scikit-learn
-   tensorflow

## Running the Notebook
The notebook can be run on
-   Google Colaboratory
-   Jupyter Notebook
  
## Instructions
-   To run the code, user must have the required Dataset on their system or programming environment.
-   Upload the notebook and dataset on Jupyter Notebook or Google Colaboratory.
-   Click on the file with .ipynb extension to open the notebook. To run complete code at once press Ctrl + F9
-   To run any specific segment of code, select that code cell and press Shift+Enter or Ctrl+Shift+Enter

> **Caution - The code should be executed in the given order for best results without encountering any errors.**


## Datasets
- **dataset_APT.csv** - Original Dataset 


## Machine Learning Models
- LSTM (Long Short-Term Memory) 


## Data Preprocessing
- Dataset had **80 attributes** and **86676 rows**.
- ### Data Normalization
	- **32 Numeric Columns** of DataFrame is scaled using  **MinMax Scaler**.


## Splitting Dataset
- Randomly Splitting the **bin_data** in **80% for training** and **20% for testing**

## Decision LSTM
- ### Binary Classification
    - Accuracy - **0.98552**
    - Mean Absolute Error - **0.03058**
    - Mean Squared Error - **0.07143**
    - Root Mean Squared Error - **0.26726**
    - R2 Score - **0.93691**
