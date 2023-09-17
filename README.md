# Life-Expectancy-Analysis
An in-depth analysis of life expectancy factors and trends. This project was conducted as part of the DCS 424 course in Advanced Data Analysis 

Project Overview:
This project delves into an extensive dataset containing 22 columns and 2938 rows, comprising 19 continuous and 3 categorical variables. The primary objective is to identify the contributing factors to lower life expectancy values. The insights gained from this analysis can assist countries in targeting specific sectors to enhance their population's life expectancy effectively.

Key Highlights:

Data Exploration: The dataset, consisting of 2938 observations and 22 variables, underwent rigorous examination to address missing data, identify valuable information in each variable, and handle data gaps by substituting missing values with means.

Outlier Detection and Skewness Mitigation: The project utilized log transformation and the Interquartile Range (IQR) method to tackle data skewness and outliers, ensuring the data's robustness.

Correlation Analysis: A heatmap revealed correlations among variables, with a focus on identifying potential multicollinearity issues.

Analysis Techniques: The project employed linear discriminant analysis, principal component analysis, and multidimensional scaling and clustering analysis to understand the dependent variable better. It also used regularized regression and principal component analysis to assess numeric performance on independent variables.

Principal Component Analysis (PCA): PCA was employed for variable selection, with a thorough scaling process and scree plots to determine the optimal number of factors to extract.

Linear Discriminant Analysis (LDA): LDA was applied to binary variables (STATUS), providing insights into the separation between Developing and Developed countries.

Multidimensional Scaling and Clustering: This section explored clustering using non-metric MDS, dimension selection based on stress and dimension, and various clustering algorithms. Although clustering was challenging, the analysis shed light on life expectancy differences.
