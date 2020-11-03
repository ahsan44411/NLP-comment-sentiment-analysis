# comment-sentiment-analysis

#welcome to my repo

# Architectures 
I have used three neural networks to solve a Natural Language Processing problem and compared their results at the end. You can also see the accuracy and the loss plots for each network in its respective jupyter notebook file.

The networks I have used are:
1. LSTM
2. CNN
3. Bi-directional LSTM

# Dataset

The data used was from Kaggle. It divided comments into six different classes
1. toxic
2. severe_toxic
3. obscene
4. threat
5. insult
6. identity_hate

# Dataset Pre-processing

For all networks the pre-processing of the dataset remain nearly the same.
1. Tokenization
2. Padding
3. Embedding

# Result
Following are the AUC scores for each networks

Bidirectional LSTM: 0.985

LSTM: 0.981

CNN: 0.975

All three gave good results but Bi-directional LSTM gives slightly better performance.

# Improvement

Improvements can be made by first removing all the stop words from all the comments using the NLTK library.
