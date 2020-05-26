# Seq2Seq-Chatbot

## Introduction
This Chatbot is a TensorFlow implementation of Seq2Seq Mode. It make use of a seq2seq model RNN for sentence predictions. The chatbot is trained on Cornell Movie Dialogs Corpus on Conversation of lenghth between 5 to 2 words

## Installation
To run this chabtot you will need:
* Python 3.5 
* Tensorflow (1.14.0)
* Numpy
* Flask
* Matplotlib
* [Dataset](http://www.cs.cornell.edu/~cristian/data/cornell_movie_dialogs_corpus.zip)

## Running
### To chat with the trained model from Web Chat:
1. First install the required depedencies and run 
`pip install -r requirment.txt`
2. From the BOT_UI directory run run.py
`python run.py`
3. Open a browser to the URL indicated by the server console, This is typically: http://localhost:5000/

### To chat with the trained model from Python Console:
1. First install the required depedencies from root directory and run 
`pip install -r requirment.txt`
2. From the root directory run 
`python chat.py`

## List of Hyperparameters
<img src="https://github.com/Abonia1/Seq2Seq-Chatbot/blob/master/Images/Config.jpg" alt="alt text" width="700" height="500">



## For Training Model 
To Train Model from Python Console:
1. Configure the `config.py` file for desired training hyperparameters
2. Run train.py
`python train.py`
3. Make sure the datasets should be present in the `datasets` folder

## Results
Config1:Model was able to train to `Accuracy of 62%` and `Loss of 19%` and after that it was overfitting
Config2:Model was able to train to `Accuracy of 63%` and `Loss of 18%` and after that it was overfitting

### Accuracy
Config1
<img src="https://github.com/Abonia1/Seq2Seq-Chatbot/blob/master/Images/Accuracy1.jpg" alt="alt text" width="500" height="300">

### Loss
<img src="https://github.com/Abonia1/Seq2Seq-Chatbot/blob/master/Images/Loss1.jpg" alt="alt text" width="500" height="300">

Config2
### Accuracy
<img src="https://github.com/Abonia1/Seq2Seq-Chatbot/blob/master/Images/Accuracy2.jpg" alt="alt text" width="500" height="300">

### Loss
<img src="https://github.com/Abonia1/Seq2Seq-Chatbot/blob/master/Images/Loss2.jpg" alt="alt text" width="500" height="300">

### Chat Results
```
Human :hey
Bot :hi
Human :what doing
Bot :sleep
Human :when will you be okay
Bot :just few days 
Human :where are you from
Bot :southern california
Human :who am i
Bot :doctor livingston
Human :really well
Bot :goodbye
```
Some Funny Result in web app
<img src="https://github.com/Abonia1/Seq2Seq-Chatbot/blob/master/Images/Result.jpg" alt="alt text" width="850" height="500">



