# **Problem Statement** : Develop a Price Prediction Model
**Data Overview** : 
There are two files `train.csv` and `test.csv`. Each row of the train.tsv file has the following attributes/features that lists details about a particular product.

*   `id`: the id of the listing
*   `name`: the title of the listing
*   `item_condition_id`: the condition of the items provided by the seller
*   `category_name`: category of the listing
*   `brand_name`: brand of the listing
*   `price`: the price (USD) that the item was sold for
*   `shipping`: 1 if shipping fee is paid by seller and 0 by buyer
*   `item_description`: the full description of the listing
*   `seller_id`: the seller ID of the listing

**Error metric**: RMSLE (Root Mean Square Logarithmic Error)

**Input Features** :  id, name, item_condition_id, category_name, brand_name, shipping, seller_id, item_description

**Target Variable** : price

- For a given item name, here the task is to suggest the price of that item by analysing its different features like category, name, brand name, item description etc. 
- The given problem is a **Regression problem** as it will return the price of an item which is a real-valued value.

