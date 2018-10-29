# World Wide Products Inc.

Time series forecasting
=======================

Shipping and delivering to a place near you
1. Set up a data science project structure in a new git repository in your GitHub account
2. Download the product demand data set from
https://www.kaggle.com/felixzhao/productdemandforecasting 
3. Load the data set into panda data frames
4. Formulate one or two ideas on how feature engineering would help the data set to establish additional value using exploratory data analysis
5. Build one or more forecasting models to determine the demand for a particular product using the other columns as features
6. Document your process and results
7. Commit your notebook, source code, visualizations and other supporting files to the git repository in GitHub

==================

About the dataset
==================
The dataset is called Historical Product Deman-  CSV data file containing product demand for encoded product id's - It can be found in a zip file called - Historical_Product_Demand.csv.zip

The dataset contains historical product demand for a manufacturing company with footprints globally. The company provides thousands of products within dozens of product categories. There are four central warehouses to ship products within the region it is responsible for. Since the products are manufactured in different locations all over the world, it normally takes more than one month to ship products via ocean to different central warehouses. If forecasts for each product in different central with reasonable accuracy for the monthly demand for month after next can be achieved, it would be beneficial to the company in multiple ways.

--------------------------------------------------------------------------------------------------------------------------

Code for the project
====================
The notebook for this project can be found in the 1.0-eecs731-HW5.ipynb Jupyter notebook. 


Regression models
===================
Used fbprophet to predict time series forecasts for the demand of a particular product from the dataset.  


-------------------------------------------------------------------------------------------------------------------------
