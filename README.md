# Problem Statement
To predict the price of homes at sale for the Aimes Iowa Housing dataset using data from Ames Assessor’s Office for sales from 2006 to 2010. 

# Executive Summary

### Data Import and Cleaning
The columns of Alley, Pool QC and ID were dropped. Empty cells with missing data were filled. All numeric columns were changed to floats. Columns with ordinal discrete data were replaced with numbers. 

### Exploratory Data Analysis
Features measuring the same aspect of the property were combined. The top 25 factors with the highest correlation to Sale Price were selected. 

### Data Visualization
A heatmap and some scatterplots were used to investigate the data and correlations further. 

### Descriptive and Inferential Statistics
From the list of 25 features features, 13 features were chosen to proceed with predicting the Sale Price for the test set based on their P-value. A ridge regression was used. 

### Conclusions and Recommendations
Features such as the size of spaces of the property, the number of fireplaces and the quality of the living areas, basement and garage are the highest determinants of sale price. Increasing the the number of fireplaces in the property would attribute to an increase of $9,813 to the sale price. 

# Conclusions and Recommendations
#### Key Takeaways
The features that are deemed to be the highest importance to the property sale price are the overall quality, the basement and heating quality, the size of the living areas, garage and basement, the basment exposure, the type of sale, number of fireplaces and if it is situated in the neighborhood of Northridge Heights. 


#### Recommendations
Based on the data, it seems that other than maintaining the property in a good condition, every fireplace added to the property woulsd give it an increase of $9,813 to the sale price. 
