---
layout: default
comments: true
title: Data science projects
permalink: /datascienceprojects/
---
# Projects
## Predictive Modeling
### 1. Predict Cast Member of the show "Friends" - [Article, ](https://github.com/shamafarabi/Predicting-Cast-Member-of-the-TV-show-Friends-using-NLP/blob/master/Project%20Report.ipynb)[Repository](https://github.com/shamafarabi/Predicting-Cast-Member-of-the-TV-show-Friends-using-NLP) 
<p style='text-align: justify;'>
I was curious to know if  NLP can be used to identify movie/TV show characters from any line they have said in the show by using the transcripts of the show as the source of dataset. So I decided to build this project using the popular TV show 'Friends' as the test case. I webscraped text transcripts of 235 episodes of Friends and processed the data in a dataframe with 489,44 observations such that the lines said by different cast members can be used as input to train different ML models. I implemented interactive visualization to identify insights about the members and  explored different word embedding methods (count-vectorizer,tf-idf, word2vec etc.), resampling techniques, ML (multinomial naive bayes, logistic regression, support vector machines) and DL models for identifying the characters. 
</p>

### 2. Predict Users Ratings and Recommend New Books to Read - [Article,](https://nbviewer.jupyter.org/github/shamafarabi/Capstone_1_Book_Recommendation/blob/master/Milestone%20Report/Milestone%20Report.ipynb)[Repository](Book_Recommendation_Engine)
<p style='text-align: justify;'>
Book reading apps like Goodreads has personally helped me to find books I couldn’t put away and thus getting back to the habit of reading regularly again. In this project, I developed a collaborative filterning based book recommendation model using goodreads dataset that can suggest readers what books to read next.  Utilizing exploratory data analysis on  6,000,000 user ratings, 10,000 books and 34,252 book tags, I identified business insights  about goodreads users reading preferences (e.g. how they like to tag books, what ratings they usually provide etc.) and current trends in the book market (book categories that are in demand, successful authors in the market etc.). Then I utilized ML models (KNN, SVD and NMF) to predict user ratings to books they are yet to read and implemented personalized and non-personalized recommendation system.
 </p>
 
## ML Web Apps
 
### 1. A Web App for Image Classification using fastai -[Repository](https://github.com/shamafarabi/fastai-v3)
In this project, I made an image classification web app using fastai to identify different types of car. Image data was collected for different cars and labeled using Google Image Search for different body types(SUV,Sedan, Convertible and Trucks, Racing cars). A renet34 pretrained model was used for transfer learning with fastai and then deployed online. you can try it out [here.](https://car-make-detection.onrender.com/)

### 2. NLP with fastai: A Web App for Guessing the Friend in "Friends"
This web app demonstrated a deployment of a multiclass text classification web app I developled using fastai. A user can input any line he\she wants from the transcripts of the tv show "Friends" and let the ML model guess the character. You can play with it [here.](https://friends-2b3s.onrender.com/)

The data for this ML modeling was scraped from trasncripts available online. An RNN based AWD LSTM Model pretrained on WikiTxt dataset was used as a language model and then fine tuned with the current dataset for this project. The language model was then trained as a classification model to predict characters from a dialogue\lines they said in the show.

## Data Visualization with Tableau

### 1. Unemployment in the US during Covid-19, Visualized using Tableau

By scraping data from the reports published on the website of Bureau of Labor Statistics,  I developed an interactive dashboard to explore the unemployment situation in the US by taking a close look at the trends in different states and industry sectors. You can play with it [here](https://public.tableau.com/views/Book2_15969148443530/Dashboard1?:language=en&:display_count=y&:origin=viz_share_link). Be sure to hover with your cursor on the plots and click the buttons for pop up charts with more information. 



