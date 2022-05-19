# playstore-app-analysis
Analyzing the reviews of apps on play store
# Abstract

Google play store is a collection of Thousands of android applications which are varied based on their category, usability and various other parameters. Most of the applications are regularly updated and supported by a large pool of developers and designers. It's a huge marketplace where everyday people from around the world download, update, use and give feedback on the applications. Though most of the applications are free the revenue is generated with the help of in-app purchases, advertisements inside apps and other sources.In order to get success in the play store marketplace there is some inside analysis required. Users can give ratings and also write reviews based on their experience of a particular application. This study aims to predict the success of Google Play Store apps based on various factors and user sentiments with the help of exploratory data analysis. The play store dataset is given with the project objective by the team. Using numerous data cleaning, data wrangling and data visualization by python (google colaboratory notebooks), I have tried to discover the relationships among various attributes present in the dataset such as which application is free or paid, about the user reviews, rating of the application etc.

# 1.	Introduction
As E-commerce, review sites and app marketplaces are growing exponentially, these  brimming untapped dataset can be utilized by converting those to actionable meaningful insights that can help with robust decision making. Here one such avenue, Google Play store data is analysed using data science exploratory data analysis.
# 2.	Dataset details
The Play Store apps data has enormous potential to drive app-making businesses to success. Actionable insights can be drawn for developers to work on and capture the Android market. Firstly let's get to know data. While I was analyzing the data, I used the Pandas library.

info(): It informs about data columns and data types.
head(): It returns the first five data.
tail(): It returns the last five data.
columns : It returns data columns
shape : It gives the number of rows and columns in a table.

The columns of the dataset are as follows:
●	App 
●	Category
●	Rating
●	Reviews
●	Size 
●	Installs
●	Type
●	Price
●	Content Rating (Everyone/Teenager/Adult)
●	Genres (Detailed Category)
●	Last Updated 
●	Current Version
●	Android Version 

# 3.	Data preprocessing
At first glance after observing the data it is clear that there are several empty fields present and there are some inconsistencies also for example App Size is somewhere given KB and somewhere it is given in MB. If the analysis is being made based on the numbers then a possible wrong outcome will be there.
Dataset can contain missing data, numerical string value, various cues.By finding all unique values of each row the inappropriate values can be identified. Different methods can then be used for removing them or to change those values accordingly to use them to make predictions better. So cleaning the dataset is necessary as a first step to make it “more accurate”.
Another perspective of cleaning the data is to only focus on the portion of the dataset from which valuable insights can be drawn.
i.	Data cleaning
ii.	Reducing Data inconsistency
# 4.	Exploratory Data analysis
Data visualization can be used to get a glimpse of the distribution of the app market. This can help businesses in several ways. Apps could be targeted to a particular market. A business could analyze its approach to entering a market with more/moderate/fewer competitors. If the app holds a feature that may change the future usage of users, a data-driven business venture could launch the app in the market of more competitors to get a better hold of the market relying on that key feature and making further development.
i.	Questioning the objective
ii.	Data visualization
# 5.	Experimental results
# 6.	Conclusion
The target of this Play store Data analysis is to know how different parameters can affect the app ratings and reviews and understand how these can affect the Play store app industry as a whole. So we can conclude that:

●	Users mostly prefer the free apps. App size does not affect the decision of using the paid or free apps much.
●	The apps which have the higher rating above 4 are actually targeting all the people not a certain age group.
●	Number of Installs and number of reviews are the Most popular category of apps.
●	Family, Game, Communication, Social, Tools, Medical, Events category Apps have the highest earning.
●	Also at the same time Medical, Family, Tools, Game category apps are the most expensive apps which actually is clear also because these categories of the application market have the most invested money and indeed these are the right categories to make best profits.
●	Customer ratings actually affect the category to release an app on that category.
●	We can see that most positive sentiment reviews are from the most popular categories.
●	Positive reviews are higher than negative and neutral sentiment reviews.


