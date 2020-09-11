
# Tanzanian Water Wells Classification

![Water Wells](https://github.com/edwardcheng22/Tanzania-Water-Wells-Project/blob/master/Images/Mission_Water.jpg)


## Business Case

Clean water, basic toilets and good hygiene practices are essential for the survival and development of children. For children under five, water- and sanitation-related diseases are one of the leading causes of death. Every day, over 800 children die from preventable diseases caused by poor water, and a lack of sanitation and hygiene. UNICEF’s water, sanitation and hygiene (WASH) team works in over 100 countries worldwide to improve water and sanitation services, as well as basic hygiene practices. Last year, UNICEF’s efforts provided nearly 14 million people with clean water and over 11 million with basic toilets. Our current mission is to predict the condition of water wells in Tanzania, as they are facing a massive water crisis. 


## Objective of the project
*Build a multi-classifier to predict the condition of water wells using various machine learning algorithms*

#### Technologies Used:
* Pandas for Data Cleaning
* Matplotlib and Seaborn for Data Visualization
* Numpy for Basic Calculations
* Scikit Learn for Logistic Regression, Decision Trees, Random Forests, AdaBoost, and Gradient Boost

### Process Overview

![Process](https://github.com/edwardcheng22/Tanzania-Water-Wells-Project/blob/master/Images/process.PNG)

* Cast columns to the appropriate data types
   * Convert data types of 'object' to appropriate numerical data type

* Identify and deal with null values appropriately

* Filter data set
   * Convert all columns to contain only the top 5 most frequently seen values
   * Use Boruta algorithm in later stages to determine which features I wanted to keep for my model 

* Deal with categorical variables using dummy variables for modelling purposes

 ## Exploratory Data Analysis
 
 ### Distribution of Well Conditions
 
 ![well_condition](https://github.com/edwardcheng22/Tanzania-Water-Wells-Project/blob/master/Images/pie_chart.png)
 
 
 ### Date Recorded of Wells
 
 ![date](https://github.com/edwardcheng22/Tanzania-Water-Wells-Project/blob/master/Images/date_recorded.png)
 
 
 ### Construction Years of Wells
 
 ![constr_map](https://github.com/edwardcheng22/Tanzania-Water-Wells-Project/blob/master/Images/construction_year.png)
 
 ![constr_bar](https://github.com/edwardcheng22/Tanzania-Water-Wells-Project/blob/master/Images/construction_yr_bar.png)
 
 
 ### Distribution of the Altitude of Wells
 
 ![alt](https://github.com/edwardcheng22/Tanzania-Water-Wells-Project/blob/master/Images/gps_height.png)
 
 
 ### Distribution of the region codes of Wells
 
 ![region](https://github.com/edwardcheng22/Tanzania-Water-Wells-Project/blob/master/Images/region_code.png)
 
 
 ### Best Water Sources
 
 ![src_dist](https://github.com/edwardcheng22/Tanzania-Water-Wells-Project/blob/master/Images/water_source_dist.png)
 
 ![src_bar](https://github.com/edwardcheng22/Tanzania-Water-Wells-Project/blob/master/Images/water_sources.png)
 
 
 ### Best Water Quantity
 
 ![water_dist](https://github.com/edwardcheng22/Tanzania-Water-Wells-Project/blob/master/Images/water_quality_dist.png)
 
 ![water_bar](https://github.com/edwardcheng22/Tanzania-Water-Wells-Project/blob/master/Images/water_quantity.png)
 
 
 ### Best Water Quality
 
 ![water_qual](https://github.com/edwardcheng22/Tanzania-Water-Wells-Project/blob/master/Images/water_quality.png)
 
 
 ### Check for multicollinearity
 
 ![multi](https://github.com/edwardcheng22/Tanzania-Water-Wells-Project/blob/master/Images/multicoll_1.png)
 
 
 ## Modelling
 
 **Final Model Selected: Random Forest**; **Final Accuracy Score: 70.2%**
 ![final_model](https://github.com/edwardcheng22/Tanzania-Water-Wells-Project/blob/master/Images/final_model.png)
 
 # Conclusion
 
 ### Top 10 Features
 
 ![features](https://github.com/edwardcheng22/Tanzania-Water-Wells-Project/blob/master/Images/features.png)
 
 **Next Steps**
 
  * Trying different data cleaning methods
  * Having more time to play around with combining unused features together
  * Collect more data to train the model
  * Transforming more categorical variables into numerical ones for modelling purposes
  * Making predictions with another modelling algorithm such as XGBoost

 
 
  
