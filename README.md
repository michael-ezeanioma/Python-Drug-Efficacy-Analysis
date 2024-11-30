# Overview
This project analyzes clinical trial data from Pymaceuticals, Inc., a pharmaceutical company specializing in anti-cancer treatments. The study aims to evaluate the effectiveness of various drug regimens, including Pymaceuticals' key drug, Capomulin, in treating squamous cell carcinoma (SCC). The analysis focuses on comparing tumor growth metrics across treatments and generating comprehensive visual and statistical insights.

# Objectives

__1. Data Preparation:__
Clean and merge the provided datasets.
Ensure data integrity by identifying and removing duplicate entries.

__2. Summary Statistics:__
Compute statistical metrics (mean, median, variance, standard deviation, SEM) for tumor volume across drug regimens.

__3. Visualization:__
Generate bar charts for drug regimen frequency and pie charts for gender distribution of test subjects.
Develop box plots, line plots, and scatter plots to reveal trends and outliers.

__4. Statistical Analysis:__
Detect potential outliers using quartiles and interquartile ranges (IQR).
Analyze relationships between mouse weight and tumor volume using correlation and regression techniques.

__5. Key Deliverables:__
Tables, figures, and summaries for a comprehensive technical report.

# Files

- Mouse Metadata: Contains details about the test subjects.
- Study Results: Tracks tumor volume changes during the study.
- Project Notebook: The complete Jupyter Notebook used for the analysis.

# Methodology

__1. Prepare the Data:__
Merge the mouse_metadata and study_results datasets into a unified DataFrame.
Identify and remove duplicate data to ensure accuracy.
Verify the number of unique mice in the cleaned dataset.

__2. Generate Summary Statistics:__
Group data by drug regimens and calculate:
  - Mean and median tumor volumes.
  - Variance, standard deviation, and SEM of tumor volumes.

__3. Create Visualizations:__
Bar Charts:
- Show the number of timepoints per drug regimen.
- Created using both Pandas and Matplotlib.

Pie Charts:
- Illustrate the gender distribution of test subjects.
- Created using both Pandas and Matplotlib.

Box Plot:
- Display the distribution of final tumor volumes for Capomulin, Ramicane, Infubinol, and Ceftamin.
- Highlight outliers for further analysis.
  
__4. Quartile Analysis and Outlier Detection:__
Calculate quartiles and IQR for the most promising drug regimens.
Identify potential outliers and interpret their significance.

__5. Line Plot and Scatter Plot:__
Generate a line plot for tumor volume changes over time for a selected mouse treated with Capomulin.
Create a scatter plot showing the relationship between mouse weight and tumor volume for all mice on Capomulin.

__6. Correlation and Regression:__
Calculate the correlation coefficient between mouse weight and tumor volume for Capomulin.
Fit and visualize a linear regression model over the scatter plot.

# Tools and Libraries
Pandas: Data manipulation and cleaning.

Matplotlib: Data visualization.

NumPy: Numerical computations.

SciPy Stats: Statistical analysis.

# Results

Summary Statistics: Capomulin and Ramicane emerged as top-performing treatments.
Outlier Analysis: Identified potential anomalies in tumor growth under different treatments.
Visual Insights:
Gender distribution balanced across study subjects.
Strong correlation between mouse weight and tumor size for Capomulin.
Regression Model: Demonstrated a clear relationship between weight and tumor volume, supporting Capomulin’s efficacy.

# How to Use
1. Clone this repository to your local machine.
2. Open the Jupyter Notebook in your preferred environment.
3. Run the cells sequentially to reproduce the analysis.
4. Review the tables and visualizations for insights into drug efficacy.

<!--Mod 4-->
