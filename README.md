# California-Housing-Data-Analysis
This Python project revolves around an extensive analysis of a dataset pertaining to housing in California. The primary dataset, available online, encompasses a range of features related to housing attributes in California.
Key features of the dataset include median income, housing median age, median house values, total bedrooms, and ocean proximity. These features are categorized as follows:

Nominal: Ocean Proximity
Ordinal: Housing Median Age
Discrete: Total Bedrooms
Continuous: Median Income, Median House Values
Throughout the project, Python libraries such as Pandas, Matplotlib, and Seaborn are employed for data manipulation and visualization. The project emphasizes the importance of commenting code for clarity, providing detailed explanations of results, and ensuring the data is handled appropriately for missing values or specific conditions.

Purpose
The project aims to address several analytical questions, providing insights into the housing landscape of California. These questions are:

Average Median Income Analysis: Calculation of the average median income of the dataset, accompanied by distribution analysis using appropriate plots, with an explanation of the observed distribution.

Housing Median Age Distribution: Visualization of housing median age distribution and its interpretation.

Income-House Value Relationship: Exploring the relationship between median income and median house values through visualization.

Data Cleaning (Total Bedrooms): Creating a dataset variant by removing records with missing total bedrooms.

Missing Data Imputation: Another dataset variant is created by filling missing total bedrooms with the mean value from the original dataset.

User-Defined Function for Median Calculation: Developing a function to calculate the median value for any given dataset part.

Geographical Plotting: Plotting latitude against longitude to analyze geographical trends and patterns.

Focused Dataset Creation: Generating a dataset specifically for areas with 'Near Ocean' ocean proximity.

Statistical Analysis of Focused Dataset: Calculating mean and median of the median income for the 'Near Ocean' dataset.

Feature Engineering (Total Bedroom Size): Introduction of a new column categorizing total bedrooms into 'small', 'medium', or 'large', based on specified criteria.
