Data Analysis in Power BI

The process include:
-- ETL in Power-Query
-- Data Modeling (if needed)
-- Writing DAXs
-- Designing the visuals

**Analysing the dataset on crop yield in India from 1997 till the begining of 2020** 

-- Downloaded the dataset from Kaggle
-- Extracted in Power-Query for cleaning and EDA
-- Established data model with the calender table
-- Wrote DAXs to claculate the Metrices like: Total land area analysed, Total production, Yield (production per unit area), Fertilizers and Pesticides Used (total and per unit area), YoY% growth rate
-- Designed the visuals
-- Added a drill-through to acess the Resource-Consumption page as per the specific crop

Observation:
-- The rate of Fertilizers and pesticides are growing with time though there was a drop observed in 2010 and 2012
-- Rice farming has the highest covered area
-- Coconut and sugarcane have the highest production quantity
-- Tamil-Nadu and Kerala are the most efficient states considering the consumption of fertilizers and overall production

**Analysing the dataset of the "All Products" section of KIWI Kisan Window**

-- Scrapped the data from the All Products page of the KIWI Kisan Window website
-- Product Name, Cost, Rating and source were included in the dataset
-- Generalized the cost of products as Low, Medium and High
-- Wrote DAXs to calculate Average product cost, Average Rating, Total methods used and Value for Money Score [( Rating divided by Cost of the product) * 100]
-- Designed the Visuals

Observation:
-- Handpicked, Freeze Dried and Silbatta are the most popular methods
-- The average rating of the store is 3.49
-- INR 405 is the average product price
-- Amarnath seed noodles, Foctail Millet noodles and Quinoa Millet Noodles have the highest Value for Money Score
-- 10 products aren't rated in the website as of now.
