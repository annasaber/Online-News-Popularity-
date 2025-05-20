# Online-News-Popularity-
This project analyzes the Online News Popularity dataset, which includes 39,644 news articles with 61 features related to word, topic, and sentiment levels. The goal is to identify key factors that contribute to an article’s popularity and build predictive models to classify articles as popular or not. 

To define popularity, we used the median share count (1400 shares) as a threshold, instead of the mean, to reduce the influence of outliers. Articles with more than 1400 shares were labeled as popular.


Exploratory Analysis & Clustering:

Applied clustering techniques, including K-Means and Agglomerative Clustering, to uncover natural groupings within the data. Analysis revealed that:

•	Articles related to lifestyle, technology, and business topics are more likely to be popular.

•	Factors such as the presence of keywords, weekday publication, references to highly shared content, title subjectivity, and the number of videos embedded in an article all positively influence popularity.

These insights can help media companies tailor content strategies to boost article performance.


Classification Modeling:

We built multiple classification models using Scikit-learn, including: Logistic Regression, Linear Support Vector Classifier (LinearSVC), K-Nearest Neighbors (KNN), Decision Trees, Random Forest Classifier

Among these, the Random Forest Classifier consistently achieved the highest accuracy. 


We further analyzed how model performance is affected by reduced training set sizes and found that accuracy remains stable, indicating that the model generalizes well even with less data.

