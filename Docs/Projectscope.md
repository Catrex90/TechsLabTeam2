# Project Scope - Team 2
# Hotel Booking Exploratory Data Analysis

#  Introduction:
This project is part of the TECHSLABS Düsseldorf Winter Term Digital Shaper Project 2024 for the Data Science Track.
  
The project is based on the Kaggle project from NITESH YADAV https://www.kaggle.com/code/niteshyadav3103/hotel-booking-prediction-99-5-acc, who did a exploratory data analysis and some module building on a dataset about **hotel bookings**. The project's data has been taken from the following article: https://www.sciencedirect.com/science/article/pii/S2352340918315191#bib4.  

The dataset has data from two different hotels in Portugal: one city hotel located in Lisbon and another resort hotel situated in the Algarve. The collected data dates from the 1st of July 2015 and the 31st of August 2017. As data collection began in mid-2015 and ended in mid-2017, only 2016 is available as a complete year.
   
The dataset is an excellent way to compare the different hotel types with each other. We also want to carry out an exploratory data analysis and add some further questions, which are explained in the following sections.  Additional we want to correlate the data with the following dataset: **World Happiness** Report Dataset(s): https://www.kaggle.com/datasets/unsdsn/world-happiness/data and see, for example, whether or not there is a correlation between guests from countries with a high happiness score and repeated travels to a specific hotel.

### The following explorative data analysis has been made in the Kaggle project:

* From where are most guests coming? (country)  
Map of the world with different colours
  
* How much do guests pay for a room per night?  
comparison between Resort and City Hotel and the room type

* How does the price vary per night over the year?  
Two tables, one for each hotel, with the mean of each month
Graph with two lines (one for each hotel) showing the development of the price over the year
		
* Which are the most busy months?  
The survey is based on the number of visitors
The graph shows a comparison of the two hotels

* How long do people stay at the hotel?  
The graph compares the two hotels. It shows how many guests stayed for how many nights.

# Additional Data Analysis Ideas    
Several questions might be exciting and provide a deeper insight into the hotel dataset. We yet do not know how many of these additional questions we can add, but this is our list of suggestions:

## Cancellation-Behaviour:

Cancellation is a big problem for hotels that they would wish to avoid. Understanding the factors that might lead to cancellation is interesting, as it might help the hotel prevent such factors in the future or better calculate when cancellation is more likely. The dataset offers no reasons for a booking being cancelled, but we can compare some data to understand the cancellation process better.  
Questions we could answer with the dataset are:
* Are there certain months in the year when cancellations happen more often? 
* Is there a connection between the booking period and the cancellation, e.g. do travellers cancel their trip more frequently if they have booked well in advance?
* Are guests that come more often less likely to cancel?
* Do guests with a deposit made in advance cancel less?
* Has the booking way (direct or via an agency) influenced the cancellation rate?

## What is a regular customer at the City and the Resort Hotel?

Another insight that would be interesting for the two different hotels to know is what their regular guest looks like. Not many personal dates are given, but we can investigate several points that we could combine to make a kind of set card for one typical guest for each hotel. Categories of relevance regarding this topic could be: 

* Do the guest have children or not:  
How many Baby and Children guests does each hotel have in 2016 per month? Are there months when travelling with children is more common?
How many guests travel with children? Is there a big difference between the hotel types?  
Do people with children require car parking more often or have a special request?  
Do families choose a special meal-time, e.g. all-inclusive, more often than guests without children?  

* What Nationality do the guests have:  
The data project has already looked at the nationalities of the guests. However, these are not spit up by the hotel. So, a first analysis could look at the nationalities within the two hotels.
Additionally, it can be analyzed whether there is a connection between guests from countries with a high Happiness value or not. 


## Additional questions that can be connected with both topics above:
* What does a repeated guest look like
* We could make an additional comparison if we have newer data from the source, where the Kaggle dataset stems from. Getting this data might be complex, so our focus is on the other questions so far. 


## What we cannot find out with the given data set:  
The room types are decoded with letters from A to D. There is no key to what each letter could mean (if it is a single or double bed, etc.) Therefore, this information is not valuable to us. 
We cannot say which travel agency is responsible for bookings, as this data information is decoded for private reasons. They have no value for us.

The Kaggle project also does some machine-learning modules
The following are used in the programme:  
* Logistic Regression
* KNN
* Decision Tree Classifier
* Random Forest Classifier
* Add Boost Classifier
* Gradient Boosting Classifier
* XgBoost Classifier
* Cat Boost Classifier
* Extra Trees Classifier
* LGBM Classifier
* Voting Classifier
* ANN

How and if we refer to these methods is yet uncertain. 




