# SENTIMENT-ANALYSIS-MICRO-SERVICE-AVID-DEVS

In this project we have done sentiment analysis along with offensive review detection, detection of suggestions in the text, overall sentiment percentage.

#### Sentiment Analysis:
For doing sentiment analysis we have used Convolutional Neural Networks for training the models.
Our sentiment analyzer categorizes reviews into five groups: Negative, Semi-Negative, Neutral, Semi-Positive, and Positive.
The files required to acheive this task are:
1. https://github.com/subahan22/224G5A3312/blob/aed318106e98722110903a68446afa826cd918b5/finalmodel.ipynb     --- contains the code for training the model
2. https://github.com/204G1A0555/Project/blob/master/dsadd.csv            --- dataset which we used to train our model
3. models we got from this finalmodel.ipynb 
   1. https://github.com/204G1A0555/Project/blob/master/model.h5
   2. https://github.com/204G1A0555/Project/blob/master/label_encoder.pkl
   3. https://github.com/204G1A0555/Project/blob/master/tokenizer.pkl


#### detection of suggestions in the text:
for doing this we have used Convolutional Neural Networks for training the models. The files required to do this are:
1. https://github.com/204G1A0555/Project/blob/master/suggestionfinalmodel.ipynb      --- contains the code for training the model
2. https://github.com/204G1A0555/Project/blob/master/suggestiondataset.csv           --- dataset which we used to train our model
3. models we got from this finalmodel.ipynb
   1. https://github.com/204G1A0555/Project/blob/master/suggestionmodel.h5
   2. https://github.com/204G1A0555/Project/blob/master/suggestion_label_encoder.pkl
   3. https://github.com/204G1A0555/Project/blob/master/suggestiontokenizer.pkl


#### offensive review detection:
the file contains the code, for doing this task is:  https://github.com/204G1A0555/Project/blob/master/offensive%20content.ipynb


#### overall sentiment percentage:
the file contains the code, for completing this task is: https://github.com/204G1A0555/Project/blob/master/sentiment%20percentage.ipynb  






Since we have deployed our project prototype as web application, we have used flask framework for doing so.
And we have written code for doing that in the file: https://github.com/204G1A0555/Project/blob/master/Sentiment%20AnalysisApp.ipynb.
In this code we have used files we got while training the models(https://github.com/204G1A0555/Project/blob/master/finalmodel.ipynb  ,  https://github.com/204G1A0555/Project/blob/master/suggestionfinalmodel.ipynb ).
The html files which we have used for rendering the webpages are:

1. https://github.com/204G1A0555/Project/blob/master/home.html               ---- home page
2. https://github.com/204G1A0555/Project/blob/master/sentimentindex.html     ---- sentiment analysis
3. https://github.com/204G1A0555/Project/blob/master/fakereviewindex.html    ---- offensice review detection
4. https://github.com/204G1A0555/Project/blob/master/suggestionindex.html    ---- detection of suggestions in the tezt
5. https://github.com/204G1A0555/Project/blob/master/index.html              ---- overall sentiment percentage

### Note: Make sure to have all your .html files in templates folder which should be located in the same folder as your flask app presents (https://github.com/204G1A0555/Project/blob/master/Sentiment%20AnalysisApp.ipynb).
