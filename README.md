# Udacity Capstone Project: Arvato Machine Learning Analysis

In this project, demographics data was analyzed for customers of a mail-order sales company in Germany, comparing it against demographics information for the general population. Unsupervised learning techniques were utilized to perform customer segmentation, identifying the parts of the population that best describe the core customer base of the company. Then, what was learned was applied on a third dataset with demographics information for targets of a marketing campaign for the company, and a model was developed to predict which individuals are most likely to convert into becoming customers for the company. The data was provided by Bertelsmann Arvato Analytics, and represents a real-life data science task. The raw data for this project is considered sensitive, so will not be contained in this repository. 

# Table of Contents

- **Project Jupiter Notebook**
	- Location for bulk of the analysis

- **Report**
	- PDF report walking through the full process and analysis

- **Metadata**
	- Further information about the fields in the datasets

# Requirements

The Jupyter Notebook is written in Python. To run the Jupyter Notebook, the user will need to have access to the AZDIAS, customers, and mailout datasets provided by Arvato and have them stored locally on their system. Additionally, the following Python packages were the packages used in the analysis. The user will need to be install from these packages.

- numpy: scientific computing package
- pandas: data analysis and manipulation tool
- matplotlib: data visualization
- sklearn: machine learning tools
- scipy: collection of mathematical algorithms

# Conclusion

In this project, we were provided customers and population data from a marketing firm to analyze with the goal of understanding what customer segments for the marketing firm to target and predict what customers would have a positive response. We cleaned the data using a variety of cleaning techniques to standardize the data, account for nans, and scale the data. We used PCA and k-means as unsupervised learning models to identify principal components and segment the population. Finally, we used GridSearch to identify the best machine learning model to use for predictions. The Gradient Boosting Classifier gave us the best results, so we applied it to the test data and identified 10.1% of the population that would be most likely to respond from a marketing campaign. While the Gradient Boosting Classifier had a strong AUC score of 0.95, the final testing score was withheld due to data sensitivity.

# Acknowledgements

Special thanks to Arvato and the entire Udacity team involved in the development of this project and all of the training content for this program. I learned so much throughout the whole program and would recommend it to anyone pursuing a career in Data Science.

# Author
- Andrew Wrist
- [linkedIn] (https://www.linkedin.com/in/awrist/) }
