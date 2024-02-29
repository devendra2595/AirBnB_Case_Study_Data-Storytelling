# AirBnB_Case_Study_Data-Storytelling

# Problem background
Suppose that you are working as a data analyst at Airbnb. For the past few months, Airbnb has seen a major decline in revenue. Now that the restrictions have started lifting and people have started to travel more, Airbnb wants to make sure that it is fully prepared for this change.

The different leaders at Airbnb want to understand some important insights based on various attributes in the dataset so as to increase the revenue such as -

- Which type of hosts to acquire more and where?
- The categorisation of customers based on their preferences.
    - What are the neighbourhoods they need to target?
    - What is the pricing ranges preferred by customers?
    - The various kinds of properties that exist w.r.t. customer preferences.
    - Adjustments in the existing properties to make it more customer-oriented.
- What are the most popular localities and properties in New York currently?
- How to get unpopular properties more traction? and so on...

# End Objective
To prepare for the next best steps that Airbnb needs to take as a business, you have been asked to analyse a dataset consisting of various Airbnb listings in New York. Based on this analysis, you need to give two presentations to the following groups.

- Presentation - I
    - Data Analysis Managers: These people manage the data analysts directly for processes and their technical expertise is basic.
    - Lead Data Analyst: The lead data analyst looks after the entire team of data and business analysts and is technically sound.
- Presentation - II
    - Head of Acquisitions and Operations, NYC: This head looks after all the property and host acquisitions and operations. Acquisition of the best properties, price negotiation, and negotiating the services the properties offer falls under the purview of this role.
    - Head of User Experience, NYC: The head of user experience looks after the customer preferences and also handles the properties listed on the website and the Airbnb app. Basically, the head of user experience tries to optimise the order of property listing in certain neighbourhoods and cities in order to get every property the optimal amount of traction.
 
# Data Dictionary

![image](https://github.com/devendra2595/AirBnB_Case_Study_Data-Storytelling/assets/116253033/bcf06a8f-29a6-4b82-8e53-e6cfdaf5378d)


# Data Sources : 
1) Here is a snapshot of the data dictionary
    - Orders information like unique order_id, order_item_id, order purchase-approval-delivery timestamp. etc
    - Customer’s information like unique customer_id, zipcode, city and state
    - Payment information like payment_value, payment_type etc.
    - Product dimension and specification information like category, weight, length etc.
    - Customer preference information like number of reviews and number of reviews per month
2) The provided data is captured from the CRM tool used by ‘OList’. (till 17-10-2018 17:30).

# Data Methodology :
- Checked the data for any duplicate, null, insignificant values and cleaned using python.
- Checked for outliers, as outliers were actual values, the values were kept as it is, instead used median as a measure of central tendency.
- Merged the datasets for further analysis and performed EDA.
- Created new dataset with only order_id and product_category for Market Basket Analysis.
- Exported the cleaned datasets in Excel format to upload in Tableau.
- Used Tableau for visualization of data and created appropriate calculated fields to get the insights.

