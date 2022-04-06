

### Table of Contents.

1. [Libraries](#Libraries)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Libraries used <a name="librairies"></a>

- Numpy 
- Pandas
- Matplotlib
- Seaborn
- Sklearn

## Project Motivation<a name="motivation"></a>


I choose this project in order to analyze the Airbnb Data and build a model for AiBNB price precdiction.

In this analysis we will focus on the following points:
- The evolution of pricing during the seasons in Seattle
- Correlation beetween the price and the rating
- Built a simple prediction model of pricing


## File Descriptions <a name="files"></a>

There are 3 main datasets for Seattle that has been provided by AirBNB :

- listings.csv: summary information on listing in Seattle such as: location, host information, cleaning and guest fees, amenities etc.
- calendar.csv: calendar data for the listings: availability dates, price for each date.
- reviews.csv: summary review data for the listings. 

## Results<a name="results"></a>

- June through August are the peak months
- The prices are not affected by rating
- We were able to built a linear regression with an R2 score of 57% on test data set.
The features that have the most impact on price are the type of room, bathrooms, state_wa, bedrooms and review_scores_value

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Must give credit to Stack Overflow for the data.  You can find the Licensing for the data and other descriptive information at the Kaggle link available [here](https://www.kaggle.com/stackoverflow/so-survey-2017/data).  Otherwise, feel free to use the code here as you would like! 

# Projectudacity
