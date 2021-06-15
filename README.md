# MSc Thesis - Predicting the popularity of songs using Random Forest regressions


This repository contains an R-notebook for the music popularity prediction performed as part of my MSc Thesis in Business Analytics and Management at the Rotterdam School of Management (EUR).

The aim of this thesis is to assess the performance of a Random Forest (RF) regression in accurately predicting the popularity score of 203,382 contemporary songs (2000-2021) as extracted through the Spotify-API.
To make more nuanced inferences, the performance of the RF is compared to that of a simpler Multiple Linear Regression (MLR). Additionally, a RF is created on a further subset containing only songs released in 2021 (5,142 observations). 

Ultimately, the RF using the tracks from 2000-2021 is also used to render a Variable Importance (VI) score for each independent variable.


Notes:
- the results displayed in the uploaded pdf- and HTML-file deviate from the results described and shown in the Thesis paper, as the code needed to be run again to knit the Rmd-document into the alternative format. This means that the random train-test splits and subsequent CV-folds were different from the original one, resulting in the deviation. Nevertheless, the screenshots of the initial R-output can be found in the folder "Tables and Graphs".
- considering that Github only allows the upload of files of up to 50MB, the initial csv-file containing the tracks and features cannot be uploaded. The original complete dataset "tracks.csv" can be found on https://www.kaggle.com/yamaerenay/spotify-dataset-19212020-160k-tracks.
