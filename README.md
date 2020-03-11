# Fake-News-Sentiment-Analysis

It was a challenging problem statement by ZS Associate for sentiment analysis with 13 features and 2 target variables. First I understood dataset background and then approach to the solution as the following steps:

Used Modules: **Keras, Pandas, Numpy**

Model: **LSTM**  

 - As a part of preprocessing the dataset used Tokenization from Keras library and Tokenized the given text.
 - Converted into sequences, then padded to ensure all are of the same length.
 - Used word embeddings which convert to capital laters into lower case, remove punctuation, URLs.
 - Convert all words into Vector and store it in a list.

Used 3 layers of neural network in which 512, 256 nodes are used in first and second layers. Trained with 4 epochs with 128 batch size. Using the LSTM model from deep learning. 

- **Adam** - optimizer
- **softmax** - activation function 
- **mean squared error** - loss function
 - **Maxpooling** - Average 2D
