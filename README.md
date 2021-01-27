# Sentiment_analysis
This repo is about training a LSTM bidirectional model to classify the negative and harmless sentences using the Pytorch framework. Torchtext library is used for the preparation of training data and LSTM architecture is used from the Pytorch. The implementation is done step by step in the jupyter-notebook.

![sentiment](readme.jpg)

## Notebooks
- [**Sentiment_Preprocessing.ipynb**](Sentiment_Preprocessing.ipynb)
  This jupyter-notebook contains all the data preprocessing required.
  - Reading data into csv file.
  - Basic EDA
  - Data Cleaning.
- [**Sentiment_Training.ipynb**](Sentiment_Training.ipynb)
  This jupyter-notebook contains the training and evaluation of the model. After the training the model is saved. Later, prediction of some sentences is done.
  - Data preparation for training, validation and testing using the Torchtext.
  - Training and evaluating model.
  - Model evaluation on test data.
  - Saving the model.
  - Prediction of some sentences.
  
## How to run
- Clone the repo using `git clone https://github.com/mohdsaqibhbi/Sentiment_analysis.git`.
- Go to this directory using `cd Sentiment_analysis`
- Create virtual environment.
- Install dependencies using `pip install -r requirements.txt`.
- Run everything step by step.
