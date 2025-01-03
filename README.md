# Meals_forecasting_project

client is having difficulty in predicting number of orders per different meals in different centers. 
developing an effective forecast model to predict orders of meal, so that client can manage invenory efficiency for future orders.
Applied Risk pooling - inventory pooling to reduce stock and safety stock levels.
 (this is related to logistics and warehouse analytics subject -term project )


**Weekly Demand data (train.csv):**
Variable	Definition :
id	Unique ID
week	Week No
center_id	Unique ID for fulfillment center
meal_id	Unique ID for Meal
checkout_price	Final price including discount, taxes & delivery charges
base_price	Base price of the meal
emailer_for_promotion	Emailer sent for promotion of meal
homepage_featured	Meal featured at homepage
num_orders	(Target) Orders Count





**fulfilment_center_info.csv:**
Variable	Definition :
center_id	Unique ID for fulfillment center
city_code	Unique code for city
region_code	Unique code for region
center_type	Anonymized center type
op_area	Area of operation (in km^2)


**meal_info.csv**:
Variable	Definition :
meal_id	Unique ID for the meal
category	Type of meal (beverages/snacks/soups….)
cuisine	Meal cuisine (Indian/Italian/…)
