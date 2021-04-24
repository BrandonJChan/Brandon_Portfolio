# Brandon Chan Projects Portfolio

## [Spotify Reccomendation Model](https://github.com/BrandonJChan/Spotify_Reccomendation_Model)
<p align="center">
  <img width="600" src="images/spotify%20logo%20white.png">
</p>

Softwares used: Python (scikit-learn, pandas, numpy), Jupyter Notebooks
- Developed a Spotify song reccomendation model using my personal Spotify listening history and integrating it with Spotify's audio features API
- The data used was every single song I listening to in a four-month period, the number of times I played each song, and each song's audio features (danceability, energy, loudness, etc.)
  - Predicted the number of plays for each song
- In search of the highest performing model, optimized K-Nearest Neighbors, Ridge, Random Forest, and various Ensemble Regressors for minimizing Mean Squared Error
- Used model to reccomend songs from my "Release Radar" playlist, a Spotify-generated playlist containing recently-released songs
- Based on my enjoyment of the reccomended songs, I would say that I succeeded!

<p align="center">
  <img width="900" src="images/spotify_pred.png">
</p>

<img src="images/the%20difference.png" width="194"/> <img src="images/denzel.png" width="194"/> <img src="images/sugar.png" width="194"/> <img src="images/something%20comforting.png" width="194"/> <img src="images/ventura.png" width="194"/> 

<div align="center">
  Songs with highest predicted plays
</div>

<br/><br/><br/><br/><br/>

## [Clustering With Principal Components Analysis and K-means](https://github.com/BrandonJChan/clustering_pca_kmeans/blob/master/Clustering%20With%20PCA%20and%20K-means%20Presentation%20Slides.pdf)

Softwares used: R (tidyverse)
- Performed clustering analysis on the Principal Componenets from NBA player tracking statistics and my personal Spotify listening history
- Clustered NBA players by playstyle and clustered my Spotify artists by sound profile
- Taught data science concepts and presented cluster analysis to all coworkers at my internship
- 
<br/><br/>

<div align="center">
  NBA Player Statistics PCA Biplot With Clusters
</div>

<p align="center">
  <img width="900" src="images/NBA%20Clustering.png">
</p>

## [Fake News Detection](https://htmlpreview.github.io/?https://github.com/BrandonJChan/Fake_Headline_Detection/blob/main/Fake%20News%20Final%20Report.html)
<p align="center">
  <img width="600" src="images/news%20outlets%20crop.jpg">
</p>

Softwares used: R (caret, tidyverse)

- Developed a classification model that categorizes news headlines as fake or real
- The data used was 44,689 news headlines from 2015 to 2018
- Derived training and testing datasets by calculating TF-IDF values for the top 1000 most frequent words among all headlines
- Evaluated the performance of nine different models ranging in complexity from Logistic Regression and Classification Trees all the way to Random Forest and Neural Networks.
- The best performing model was the Support Vector Machine, with a test accuracy of 87.75% and an area under the ROC curve of 95%.

<img src="images/word%20cloud%20crop.png" width="482"/> <img src="images/word%20cloud%20fake%20crop.png" width="490"/>

<div align="center">
  Most frequent words in real (left) and fake (right) headlines
</div>

## [Human Trafficking Victim Resource Web Application](https://github.com/BrandonJChan/Human_Traffic_Resource_App)
<img src="images/app_demo.gif"/>
Softwares used: R (Shiny, tidyverse)

- Developed an R Shiny web application to help local human trafficking victims and law enforcement locate and contact services that provide shelter, counseling, medical assistance, legal assistance, etc.
- Services are displayed on a map of the local San Luis Obispo area
- Available services can be filtered by location, type of service, and victim profile specialization
- Contact and descriptive information are shown in a table below the map and upon clicking on a service


