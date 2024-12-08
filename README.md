# SENTIMENT-ANALYSIS-MICRO-SERVICE-AVID-DEVS

In this project we have done sentiment analysis along with offensive review detection, detection of suggestions in the text, overall sentiment percentage.

#### Sentiment Analysis:
For doing sentiment analysis we have used Convolutional Neural Networks for training the models.
Our sentiment analyzer categorizes reviews into five groups: Negative, Semi-Negative, Neutral, Semi-Positive, and Positive.
The files required to acheive this task are:
1. https://github.com/subahan22/224G5A3312/blob/81827e5f547d71b1d20fa1008ae88651a00efd6e/finalmodel.ipynb     --- contains the code for training the model
2. https://github.com/subahan22/224G5A3312/blob/81827e5f547d71b1d20fa1008ae88651a00efd6e/dsadd.csv           --- dataset which we used to train our model
3. Models we got from this finalmodel.ipynb 
   1. https://github.com/subahan22/224G5A3312/blob/81827e5f547d71b1d20fa1008ae88651a00efd6e/model.h5
   2. https://github.com/subahan22/224G5A3312/blob/81827e5f547d71b1d20fa1008ae88651a00efd6e/label_encoder.pkl
   3. https://github.com/subahan22/224G5A3312/blob/acc7654627b1dbc7eb9ed5d4d36e69caf6933fd9/tokenizer.pkl

#### detection of suggestions in the text:
For doing this we have used Convolutional Neural Networks for training the models. The files required to do this are:
1. https://github.com/subahan22/224G5A3312/blob/acc7654627b1dbc7eb9ed5d4d36e69caf6933fd9/suggestionfinalmodel.ipynb      --- contains the code for training the model
2. https://github.com/subahan22/224G5A3312/blob/acc7654627b1dbc7eb9ed5d4d36e69caf6933fd9/suggestiondataset.csv           --- dataset which we used to train our model
3. Models we got from this finalmodel.ipynb
   1. https://github.com/subahan22/224G5A3312/blob/acc7654627b1dbc7eb9ed5d4d36e69caf6933fd9/suggestionmodel.h5
   2. https://github.com/subahan22/224G5A3312/blob/acc7654627b1dbc7eb9ed5d4d36e69caf6933fd9/suggestion_label_encoder.pkl
   3. https://github.com/subahan22/224G5A3312/blob/acc7654627b1dbc7eb9ed5d4d36e69caf6933fd9/suggestiontokenizer.pkl

#### offensive review detection:
the file contains the code, for doing this task is:  https://github.com/subahan22/224G5A3312/blob/acc7654627b1dbc7eb9ed5d4d36e69caf6933fd9/offensive%20content.ipynb

#### overall sentiment percentage:
the file contains the code, for completing this task is: https://github.com/subahan22/224G5A3312/blob/acc7654627b1dbc7eb9ed5d4d36e69caf6933fd9/sentiment%20percentage.ipynb

Since we have deployed our project prototype as web application, we have used flask framework for doing so.
And we have written code for doing that in the file https://github.com/subahan22/224G5A3312/blob/acc7654627b1dbc7eb9ed5d4d36e69caf6933fd9/Sentiment%20AnalysisApp.ipynb
In this code we have used files we got while training the models(https://github.com/subahan22/224G5A3312/blob/acc7654627b1dbc7eb9ed5d4d36e69caf6933fd9/finalmodel.ipynb  ,  https://github.com/subahan22/224G5A3312/blob/acc7654627b1dbc7eb9ed5d4d36e69caf6933fd9/suggestionfinalmodel.ipynb).
The html files which we have used for rendering the webpages are:

1. https://github.com/subahan22/224G5A3312/blob/acc7654627b1dbc7eb9ed5d4d36e69caf6933fd9/home.html                ---- home page
2. https://github.com/subahan22/224G5A3312/blob/acc7654627b1dbc7eb9ed5d4d36e69caf6933fd9/sentimentindex.html     ---- sentiment analysis
3. https://github.com/subahan22/224G5A3312/blob/acc7654627b1dbc7eb9ed5d4d36e69caf6933fd9/fakereviewindex.html    ---- offensice review detection
4. https://github.com/subahan22/224G5A3312/blob/acc7654627b1dbc7eb9ed5d4d36e69caf6933fd9/suggestionindex.html    ---- detection of suggestions in the text
5. https://github.com/subahan22/224G5A3312/blob/acc7654627b1dbc7eb9ed5d4d36e69caf6933fd9/index.html              ---- overall sentiment percentage

### Note: Make sure to have all your .html files in templates folder which should be located in the same folder as your flask app presents (https://github.com/subahan22/224G5A3312/blob/acc7654627b1dbc7eb9ed5d4d36e69caf6933fd9/Sentiment%20AnalysisApp.ipynb).

