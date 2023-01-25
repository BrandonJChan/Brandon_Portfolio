# Brandon Chan Projects Portfolio

<p align="center">
  <img width="200" src="images/project portfolio headshot.png">
</p>

###Welcome
What's up, I'm Brandon and welcome to my page.

On this page, I've laid out for you my favorite data science and analytics projects. 



Hey there! I'm Brandon and these are my all-time favorite projects that I've worked on in during my time as a data science/analytics intern and statistics/data science undergraduate student. I love these projects because they represent my passion for data science combined with my passions outside of data science. Some of the key concepts covered in these projects include regression, clustering, classification, feature engineering, hyperparameter optimization, natural language processing, web application development, and much more. I apply these concepts to the passions in my life like my personal music listening data and sports player-tracking statistics. I had a lot of fun working on these projects, so I hope you have fun browsing through them! 

## [Spotify Reccomendation Model](https://github.com/BrandonJChan/Spotify_Reccomendation_Model)
<p align="center">
  <img width="600" src="images/spotify%20logo%20white.png">
</p>

Softwares used: Python (scikit-learn, pandas, numpy), Jupyter Notebooks

I developed a personalized Spotify song reccomendation model using the [Spotify Web API](https://developer.spotify.com/documentation/web-api/)

- **The Data** - 5,094 unique songs I listened to in a four-month period
- **The Features** - each song's popularity and Spotify audio feature values (danceability, energy, loudness, etc.)
- **The Goal** - Predicting the the number of times I would play a new song 

- I optimized the hyperparameters for K-Nearest Neighbors, Ridge, Random Forest, and various Ensemble Regressors, and assessed all of their performance on predicting plays
- I evaluated real-world performance of my reccomendation model by calculating predicted plays from my "Release Radar" playlist, a Spotify-generated playlist   containing recently-released songs
- Based on how much I love these songs (go bless your ears and listen to The Differnce RIGHT NOW), I would say I've succeeded :)

<p align="center">
  <img width="900" src="images/spotify_pred.png">
</p>

<img src="images/the%20difference.png" width="160"/> <img src="images/denzel.png" width="160"/> <img src="images/sugar.png" width="160"/> <img src="images/something%20comforting.png" width="160"/> <img src="images/ventura.png" width="160"/> 

<div align="center">
  Songs with highest predicted plays. I LOVE these songs.
</div>

---
<br/><br/><br/>

## [Clustering With Principal Components Analysis and K-means](https://github.com/BrandonJChan/clustering_pca_kmeans/blob/master/Clustering%20With%20PCA%20and%20K-means%20Presentation%20Slides.pdf)

Softwares used: R (tidyverse)
- Performed clustering analysis on the Principal Componenets from NBA player tracking statistics and my personal Spotify listening history
- Clustered NBA players by playstyle and clustered my Spotify artists by sound profile
- Taught data science concepts and presented cluster analysis to all coworkers at summer internship
<br/>

<div align="center">
  NBA Player Statistics PCA Biplot With Clusters
</div>

<p align="center">
  <img width="900" src="images/NBA%20Clustering.png">
</p>

---
<br/><br/><br/>

## [Human Trafficking Victim Resource Web Application](https://github.com/BrandonJChan/Human_Traffic_Resource_App)
<br/>
<img src="images/app_demo.gif"/>
Softwares used: R (Shiny, tidyverse)

- Developed an R Shiny web application to help local human trafficking victims and law enforcement locate and contact services that provide shelter, counseling, medical assistance, legal assistance, etc.
- Services are displayed on a map of the local San Luis Obispo area
- Available services can be filtered by location, type of service, and victim profile specialization
- Contact and descriptive information are shown in a table below the map and upon clicking on a service

<br/><br/><br/>

## [Fake News Detection](https://htmlpreview.github.io/?https://github.com/BrandonJChan/Fake_Headline_Detection/blob/main/Fake%20News%20Final%20Report.html)
<br/>
<p align="center">
  <img width="600" src="images/news%20outlets%20crop.jpg">
</p>

Softwares used: R (caret, tidyverse)

- Developed a classification model that categorizes news headlines as fake or real
- The data used was 44,689 news headlines from 2015 to 2018
- Derived training and testing datasets by calculating TF-IDF values for the top 1000 most frequent words among all headlines
- Evaluated the performance of nine different models ranging in complexity from Logistic Regression and Classification Trees all the way to Random Forest and Neural Networks.
- The best performing model was the Support Vector Machine, with a test accuracy of 87.75% and an area under the ROC curve of 95%.

<br/>

<p align="center">
  <img width="900" src="images/word%20cloud%20combined.png">
</p>

<div align="center">
  Most frequent words in real (left) and fake (right) headlines
</div>
