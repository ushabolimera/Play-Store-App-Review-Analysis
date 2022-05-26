# Play-Store-App-Review-Analysis
![image](https://user-images.githubusercontent.com/98172465/170450765-8699f1ea-7ee6-494b-b455-0c3d97b4e5b9.png)

Over the years, Google Play Store has evolved into a one-stop platform for downloading apps from different categories. It is the central hub for millions of apps for your smartphone. In this project, we will do a comprehensive analysis of the Play Store App by comparing over ten thousand apps and reviews across different categories. We'll look for insights in the data to devise strategies to drive growth and retention.

# Problem Statement
We must examine and evaluate the data in both datasets in order to identify the important characteristics that influence app engagement and success.

# Data Description
We are provided with two datasets:

Play_store_data: It contains the basic details of the app like number of user reviews, ratings, etc.

• App: It contains the name of the app with a short description (optional).

• Category: This section gives the category to which an app belongs. In this dataset, the apps are divided among 33 categories.

• Size: The disk space required to install the respective app.

• Rating: The average rating given by the users for the respective app. It can be in between 1 and 5.

• Reviews: The number of users that have dropped a review for the respective app.

• Installs: The approximate number of times the respective app was installed.

• Type: It states whether an app is free to use or paid.

• Price: It gives the price payable to install the app. For free type apps, the price is zero.

• Content rating: It states which age group is suitable to consume the content of the respective app.

• Genres: It gives the genre(s) to which the respective app belongs.

User reviews: It contains the user reviews and its sentiment score for the respective app.

• App: It contains the name of the app with a short description (optional).

• Translated Review: It contains the English translation of the review dropped by the user of the app.

• Sentiment: It gives the attitude/emotion of the writer. It can be ‘Positive’, ‘Negative’, or ‘Neutral’.

• Sentiment Polarity: It gives the polarity of the review. Its range is [-1,1], where 1 means ‘Positive statement’ and -1 means a ‘Negative statement’.

• Sentiment Subjectivity: This value gives how close a reviewer’s opinion is to the opinion of the general public. Its range is [0,1]. Higher the subjectivity, closer is the reviewer’s opinion to the opinion of the general public, and lower subjectivity indicates the review is more of a factual information.

# Data Cleaning
• Android Ver: The 3 rows containing NaN values were dropped from the dataset.

• Current Ver: The 8 rows containing NaN values were dropped from the dataset.

• Type: One row containing NaN value was replaced with a relevant entry.

• Rating: The 1470 NaN values were imputed with its median value.

Apart from this the data present in different columns was manipulated to make them easier to analyse. Also, the datatype of the entries was changed in some cases to make the data relevant. The resultant number of rows post cleaning the data: 9649

# Data Visualization:
It deals with the graphical representation of data, from which we can draw conclusions and take different business decisions.

# Conclusion
These are some of the aspects that the developer should research before proceeding with the app development. By conducting a simple exploratory data analysis (EDA) on the play store dataset, we not only eliminate avoidable risks of failure, but we may also be able to provide better ideas for building the app.

• Percentage of free apps = ~92%

• Percentage of apps with no age restrictions = ~82%

• Most competitive category: Family

• Category with the highest number of installs: Game

• Category with the highest average app installs: Communication

• Percentage of apps that are top rated = ~80%

• There are 20 free apps that have been installed over a billion times

• Minecraft is the only app in the paid category with over 10M installs. This app has also produced the most revenue only from the installation fee.

• Category in which the paid apps have the highest average installation fee: Finance

• Most popular app in the Play Store based on the number of reviews: Facebook

• The median size of all apps in the play store is 12 MB.

• The apps whose size varies with device has the highest number average app installs.

• The apps whose size is greater than 90 MB has the highest number of average user reviews, i.e., they are more popular than the rest.
