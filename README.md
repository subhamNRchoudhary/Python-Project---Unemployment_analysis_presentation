#Python-Project---Unemployment_analysis_presentation

import pandas as pd

# Load the dataset
file_path = r"C:\Users\sunny\OneDrive\Desktop\All the projects\17. Long-Term-Unemployment-Statistics\Long-Term-Unemployment-Statistics.xlsx"
df = pd.read_excel(file_path)

# Display the first few rows of the data frame to understand its structure
df.head()

import matplotlib.pyplot as plt

# Line Plot
plt.figure(figsize=(10, 6))
plt.plot(df['Age'], df['Unemployed'], marker='o', linestyle='--', color='r')
plt.title('Unemployment by Age')
plt.xlabel('Age')
plt.ylabel('Number of Unemployed')
plt.grid(True)
plt.show()
