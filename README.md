# CharRNN
This a model based on gated recurrent neural networks. Predict the next character given a sentence peice. Trained using poems from shakespear

#Warning:
To run the model uncomment: #ch_rnn.fit(0.98)
The model takes a numerous hours to train, therefore some functions in this code have not yet been tested. If you train and test the model & functions do not work open an issue. The functions are predict & build_text. This model uses one hot encodings to represent the characters for the model to train on. Word embeddings would be better. Before passing the GRU layer to the model, an EmbeddingLayer can be added to improve the word representations & speed up model training.
