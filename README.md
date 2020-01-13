README
# udacity-project-1

In this repository it is saved data and code used to prepare project for Udacity Data Science Course. 

# 1. Installations
For word cloud installed italian, french, english stopwords from nltk package. 

Packages and libraries used:

Data visualization: pandas, matplotlib.pyplot, seaborn

Data wrangling: numpy

Plot map: folium 

Missing values plot: missingno

Calculate distance between coordinates: geopy.distance

Upload file: PIL

Wordcloud: wordcloud creation

Linear regression and evaluation: sklearn

Additional parameter to show all columns: 
pd.set_option('display.max_columns', 500)

# 2. Project Motivation
Analysis made to identify and understand Airbnb trends in Venice:

What is the busiest period to visit Venice?

How to find the best lodging with good reviews?

What determines the price of your stay?

What could you expect during your stay?

Data preprocessing and understanding:
Identified missing values and filled; 

Identified outliers: 1.5 IQR;

Plot map with provided coordinates;

Word Cloud analysis plotted in mask;  


# 3. Files Descriptions

There are 5 files used for analysis:

listings.csv - general information about hosts;

detailed_listings.csv - detailed information about listings; 

calendar_all.csv - 365 data of available properties; 

detailed_reviews.csv - listings reviews by visitors;

reviews.csv - listings and reviewers id;

neighbourhoods.csv - neighbourhoods information.

downloaded from http://insideairbnb.com/get-the-data.html

Additionaly added files: 
venice_mask.png - picture used as mask in word cloud. 



# 4. Publication

Blog post could be found: https://medium.com/@ieva.d/this-analysis-will-make-you-think-about-how-to-save-money-while-travelling-to-venice-49af74868c1b

