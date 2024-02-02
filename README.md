# 2023 Earthquakes

EDA and visualization of earthquakes in 2023 using pandas, matplotlib and seaborn.
This project shows 2023 earthquake data. I answered the following questions after the data was cleaned:

1. How common are high magnitude earthquakes?
2. What are the most common magnitudes?
3. How many unique countries had earthquakes? 
4. Which countries had the most earthquakes?
5. Where were the major earthquakes?

The 'places' column was used to extract country information. That column was not properly formatted:
some rows had city names;
most rows only had a US state name;
some rows contained two country names;
some didn't have a country name.

I removed earthquakes that took place on uninhabited islands, under sea/ocean beds, on borders, and other ambiguous areas. My final dataset was not complete but I wanted to clean, explore and visualize data in pandas without using Excel. 

Original dataset obtained from kaggle at https://www.kaggle.com/datasets/mustafakeser4/earthquakes-2023-global by user mustafakeser4.

