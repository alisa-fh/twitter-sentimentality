# twitter-sentimentality
Final Year coursework submission for the Computational Modelling in the Humanities and Social Sciences module.

See [here](./cmhss_code.ipynb) my Python notebook submission for my the L3 Computational Modelling in the Humanities and Social Sciences module. I have developed an application which compares the CoreNLP library and a linear regression model for the analysis of sentiment in tweets about the weather in London each day over a week period. Refer to the [report](./report.pdf) for an explanation and evaluation of conclusions reached. Discussed also are interesting trends between sentiment in tweets and actual weather data from each day.

## Running the code

In order to run the code, upload the .ipynb file into a site that runs iPython notebooks such as Google Colaboratory. Before running the code, you can replace the expired Twitter Consumer and API secret and keys with your own. In addition, change the path of the dataset to where you have stored it. 

The dataset has been included in the submission. Alternatively, download the dataset here: http://thinknook.com/twitter-sentiment-analysis-training-corpus-dataset-2012-09-22/

If using Google Colaboratory, click "Runtime" and "Run All" to execute the code.

Note: When analysing the performance of the CoreNLP model on the corpus, an error may be outputted because the request is taking too long to process all the data. If this is the case, send the data in smaller batches. I recommend 5000 tweets at a time. (See the first code box under the 'Tweet Statistics' header.)

## References:
For inspiration and guidance, I consulted the following website which discusses the use of Convolutional Neural Networks and Pytorch to analyse sentiment in Tweets: https://www.kaggle.com/youben/twitter-sentiment-analysis-using-cnn

The following Python Notebook was used to help with CoreNLP setup: https://colab.research.google.com/github/stanfordnlp/stanza/blob/master/demo/Stanza_CoreNLP_Interface.ipynb

CoreNLP can be found: https://stanfordnlp.github.io/CoreNLP/

For further references specifying packages used, refer to the written report. The word count was calculated as 2996 excluding references, figures and tables.
