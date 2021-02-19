# Unsupervised Learning - Identify-Customer-Segments
This project is part of Udacity Machine Learning Nanodegree projects.

# Project Overview

In this project, I worked with real-life data provided to us by Bertelsmann partners AZ Direct and Arvato Finance Solution. The data here concerns a company that performs mail-order sales in Germany. Their main question of interest is to identify facets of the population that are most likely to be purchasers of their products for a mailout campaign. Unsupervised learning techniques were used to identify segments of the population that form the core customer and organize them into clusters. Prior to applying the machine learning methods, Before applying machine learning methods, I also evaluated and cleaned the data in order to turn the data into a usable form.
These segments can then be used to direct marketing campaigns towards audiences that will have the highest expected rate of returns.

# Data
Here are four data files associated with this project:

- Udacity_AZDIAS_Subset.csv: Demographic data for the general population of Germany; 891211 persons (rows) x 85 features (columns).
- Udacity_CUSTOMERS_Subset.csv: Demographic data for customers of a mail-order company; 191652 persons (rows) x 85 features (columns).
- Data_Dictionary.md: Information file about the features in the provided datasets.
- AZDIAS_Feature_Summary.csv: Summary of feature attributes for demographic data.

> Each row of the demographics files represents a single person, but also includes information outside of individuals, including information about their household, building, and neighborhood. We use this information to cluster the general population into groups with similar demographic properties. Then, we see how the people in the customers dataset fit into those created clusters. The hope here is that certain clusters are over-represented in the customers data, as compared to the general population; those over-represented clusters will be assumed to be part of the core userbase. This information can then be used for further applications, such as targeting for a marketing campaign.


# Installation

This project uses the following software and Python libraries:
- [Python 3.0 ](https://www.python.org/download/releases/3.0/)
- [NumPy](https://numpy.org/)
- [Pandas](https://pandas.pydata.org/)
- [scikit-learn](https://scikit-learn.org/stable/)
- [matplotlib](https://matplotlib.org/)


# Licensing, Acknowledgements
Feel free to use the code and 
Credits must be given to Udacity for providing starting code for this project.
