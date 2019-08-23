# text-summarization
this is abstractive text summarization buil using seq2seq model. The objective of this project is to build a model that can create relevant summaries for reviews written about fine foods sold on Amazon. This dataset contains above 500,000 reviews, and is hosted on [Kaggle.](https://www.kaggle.com/snap/amazon-fine-food-reviews)
To build the model we used a two-layered bidirectional RNN with LSTMs on the input data and two layers, each with an LSTM using bahdanau attention on the target data.
The sections of this project are:
- Inspecting the Data
- Preparing the Data
- Building the Model
- Training the Model
- Making your Own Summaries

Embedding used is [Conceptnet Numberbatch's (CN)](https://github.com/commonsense/conceptnet-numberbatch) embeddings, similar to GloVe, but probably better 
