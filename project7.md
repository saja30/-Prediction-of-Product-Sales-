# Best_model to predict outlet_sales
# describing the analysis
Since our Data contains Continous & categorical varibles. However,my target(Predict_outlet_sales) was continoues .Liner regression mpdel 
was adapted ,After appling Different types of tuning models on the data we decided to adapted Rndome Forest model.
## Author: Saja ali
# Business problem:
stakeholder want to predict which features play key role in increasing his outlets
# Data:


# Methods
After I read Data it was cleaned from duplicated but it has missing values , according preprocessing steps I fill missing values in continoues
variables with  strategy=(mean) , and made appropriate Encoding for categorical features , Column Transformer aggregated all preprocessing
steps and Iprepered Data for modeling.
# Results 
-  Visual 1 outlet_supermarket type  vs sales_outlet_price
-  ![item_outlet_sales vs supermarket type](https://github.com/user-attachments/assets/7104e8e1-83c3-4f0a-be2d-8931ee4bf163)
  We observe that supermarket type3 has the highest sales_avarage where as grocery store has the lowest one
 Visual 2 Item_MPR vs sales_outlet_price
![Item_MPR  vs  item_outlet_sales](https://github.com/user-attachments/assets/969f7086-1c90-445a-9627-774ec39db7bf)
As seen the Item_MPR playes crusial role affecting on outlet_sales generaly , since when MPR increased the outlet_sales
 increased positivly




   







