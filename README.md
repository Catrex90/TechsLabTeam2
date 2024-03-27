# Project Scope - Techlabs Team 2
# HappyStay - Exploring Hotel Data for a Smile

This project is part of the Data Science Track from Techslab Düsseldorf Winterterm 2023/24

Team Members:
Cara-Linn Reusch (Data Science Track)
Julia Krebbers (Data Science Track)
Selinay Cengiz (Data Science Track)


# Abstract:
Our project analysed guest data from two distinct hotels in Portugal: A city hotel in Lisbon and a resort hotel in the Algarve. During our analysis, we not only focussed on the data from the two hotels but also explored correlations between happiness ratings from diverse nations and travel preferences, focusing on visits to Portugal by combining a second dataset. This approach revealed valuable insights into guest behaviour and choices, aiding informed decision-making in the hospitality industry. Our findings emphasise notable disparities in guest origin and booking behaviour, especially regarding family stays. By grasping these differences, hotels can adjust their services to meet the needs of diverse clientele, optimising operations during peak booking periods.

# Introduction:
Understanding guest demographics and preferences is paramount for operational success in the dynamic hospitality industry landscape. The different nature of the two observed hotels in Portugal, which also suit different types of holidays or trips (relaxing holidays vs city breaks), led us to assume that the guest behaviour between the two hotels must also be different. With a meticulous focus on guest origins, family compositions, and national affiliations, we compared the hotel data. We focused on unveiling nuanced insights into the divergent guest profiles, shedding light on their preferences, behaviour and general dynamics shaping the hospitality experience. Furthermore, we explored the potential correlation between happiness ratings from diverse nations and their travel preferences, particularly on visits to Portugal. To achieve this, we merged two datasets: One containing hotel booking information and another encompassing happiness scores from various countries.

# Methods:
The project was based on the following Kaggle project (1); however, we conducted an expanded analysis and extended the evaluation to include another dataset (2). The data for the two hotels was originally obtained from external sources (3) and spanned approximately two years, from the middle of 2015 until the middle of 2017. It comprised various parameters, including the number of guests, booking period, day of arrival, and the countries from which the guests came. We have focused exclusively on bookings that were not cancelled and where at least one guest visited the hotel (some bookings did not contain any guests, as we considered this to be an error in the data and removed them in our data cleaning process). We used Python as the programming language and Jupyyter Notebook as a programming environment. The Pandas and Numpy libraries were used to analyse the data, and Matplotlib, Plotly, Seaborn, and Geopandas (4, 5) were used for the subsequent graphical presentation of our results. 

# References:
Hotel project based on kaggle project from Nitesh Yadav, Title: Hotel Booking Prediction (99.5% acc): https://www.kaggle.com/code/niteshyadav3103/hotel-booking-prediction-99-5-acc, Licence: Apache License 2.0
Happiness Dataset provided on kaggle by Sustainable Development Solutions Network (Owner) and Abigail Larion (Admin), Title: World Happiness Report - Happiness scored according to economic production, social support, etc.: https://www.kaggle.com/datasets/unsdsn/world-happiness/data, Licence: CC0: Public Domain
Hotel dataset provided on kaggle by Jesse Mostipak, Title: Hotel booking demand:
https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand, Licence: Attribution 4.0 International (CC BY 4.0)
Originating from the paper: Hotel Booking Demand Datasets: Nuno Antonio, Ana Almeida, Luis Nunes, Data in Brief, 2019. Downloaded from  https://www.sciencedirect.com/science/article/pii/S2352340918315191  and cleaned by Thomas Mock and Antoine Bichat as part of #TidyTuesday: https://github.com/rfordatascience/tidytuesday/blob/master/data/2020/2020-02-11/readme.md
Geopandas diagram based on Quisl, April 14, 2021, https://quisl.de/b/wie-du-weltkarten-mit-python-erstellst-geopandas-in-vier-schritten/
Map made with Natural Earth. Free vector and raster map data @ naturalearthdata.com.

# How to use our Code:
All datasets used can be found in the folder 'Data'. Within the folder 'Code' you find all the necessary Jupyter Notebooks to understand our individual methodological analyses of the data. We have created a Jupyter Notebook for each individual question. This makes it possible to look at all the individual research focal points one after the other or just one specific aspect. Each notebook contains a list of all the relevant Python libraries needed to follow our analisis and visualisation of each problem. In addition, all plotted graphs and merged datasets can be found in the folders figure 'Code/Output/Figures' and 'Data/Edited'.  
