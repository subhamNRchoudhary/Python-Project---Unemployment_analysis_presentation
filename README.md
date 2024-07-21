#Python-Project---Unemployment_analysis_presentation

import pandas as pd

# Load the dataset
file_path = r"C:\Users\sunny\OneDrive\Desktop\All the projects\17. Long-Term-Unemployment-Statistics\Long-Term-Unemployment-Statistics.xlsx"
df = pd.read_excel(file_path)

# Display the first few rows of the dataframe to understand its structure
df.head()
