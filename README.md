# Diabetes-Data-Analysis
# Part 1: Install necessary packages and configure the environment
Installs the PySpark library.

A Python package to interact with Google Drive, useful for Google Colab.

Installs Java Development Kit, required for running Spark.

Sets the Java environment variable.
# Part 2: Import Python libraries for data analysis and visualization
These imports are for handling data ('pandas', 'numpy') and creating visualizations ('seaborn', 'matplotlib').
# Part 3: Import PySpark libraries:
PySpark libraries imports are necessary to work with Spark dataframes and perform various transformations and analyses using PySpark.
# Part 4: Import PySpark ML libraries
KMeans For clustering.

VectorAssembler For combining multiple columns into a single vector column.

StandardScaler For standardizing features.
# Part 5: Initialize Spark Session
Creates or retrieves an existing Spark session.
# Part 6: Load the diabetes dataset and display its schema
Loads the dataset diabetes-2.csv into a Spark DataFrame.

Displays the first 8 rows and the schema of the DataFrame.
# Part 7: Convert columns to the correct data types:
Converts the specified columns to FloatType for consistency and ease of analysis.
# Part 8: Create a box plot
Visualizes the distribution of the 'DiabetesPedigreeFunction' based on 'Insulin' levels using a box plot.
![image](https://github.com/user-attachments/assets/d71f5bda-6810-4fae-b718-e427be063e2e)
# Part 9: Create a correlation heatmap
Computes and visualizes the correlation matrix of the entire dataset using a heatmap.
![image](https://github.com/user-attachments/assets/9ac31824-b857-47ef-a5f9-8331912bf6a7)
# Part 10: KMeans clustering with selected features
Selects relevant features, standardizes them, and applies KMeans clustering to categorize the data into 3 clusters.
# Part 11: Visualize KMeans clusters with a pairplot:
Visualizes the clustering results using Seaborn’s pairplot, highlighting the different clusters.
![image](https://github.com/user-attachments/assets/70034274-d2e7-47d8-9be7-2a4b34b0bb34)
