# Analysis of Mental Health in the Tech Related Companies

## Getting Started

A cookie cutter project folder structure was installed in advance for better organization of the project. 

### Jupyter Notebook Structure:
- **Notebooks:** This directory contains all Jupyter notebooks.
  - **Data_preparation.ipynb:** Conducts exploratory data analysis (EDA) and data preparation steps.
  - **Clustering.ipynb:** Focuses on clustering the prepared dataset using the Density-Based Spatial Clustering of Applications with Noise (DBSCAN) algorithm.
  - **Analysis.ipynb:** Analyzes the clusters obtained from the previous step.

### Data Structure:
The processed data is divided into the following directories according to cookie cutters guidelines:
- **raw:** Contains the original data.
- **interim:** Contains all data from EDA and clustering.
- **processed:** Contains the data prepared for analysis.

This organized structure aids in creating reproducible data science projects and adds transparency in communication of the results.

## Project Overview:
This project aims to analyze the mental health conditions and working conditions of employees in the tech sector, with the goal of developing strategies to improve employee well-being and address mental health issues within tech companies. The analysis is based on data from the OSMI Mental Health in Tech Survey 2016.

## Project Structure:
- **Data_preparation:** Conducts exploratory data analysis (EDA) and data preparation steps, including data cleaning, feature engineering, and restructuring the dataset for further analysis.
- **Clustering:** Focuses on clustering the prepared dataset using the Density-Based Spatial Clustering of Applications with Noise (DBSCAN) algorithm. Both Gower Distance and Principal Component Analysis (PCA) approaches are utilized for clustering.
- **Analysis:** Analyzes the clusters obtained from the previous step. Explores the differences and characteristics of the clusters, focusing on mental health conditions, working conditions, and demographic information.

## Key Findings:
- Significant differences in mental health conditions, working conditions, and demographic information are observed across different clusters.
- Clusters with higher rates of diagnosed mental health conditions tend to have different responses regarding seeking professional help and discussing mental health issues with employers.
- Variations in working conditions, such as remote work and fear of negative consequences when discussing mental health, are identified among clusters.
- Notable distinctions in demographic factors, including gender and continent of residence, are observed among clusters.

## Conclusion:
The analysis provides valuable insights for addressing mental health issues in the tech sector. By understanding the patterns and differences in mental health conditions and working conditions, companies can develop targeted strategies to improve employee well-being. These findings serve as a foundation for HR departments to implement measures aimed at enhancing mental health support.

