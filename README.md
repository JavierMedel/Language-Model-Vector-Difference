# Neural Statistical Language model using Recurrent Neural Network Models and Word Vector Difference Representations

Word embedding representation shows a positive impact in the results generated by Natural Language Models. For instance, the use of Pretrained word vectors as Glove as embeddings helped to improve the task of predict words. The pretrained word vectors have as the primary characteristic the ability to representing semantic and syntactical relationships between words in a high dimensional space.
We propose to use the distance between word vectors as the difference vector in a language model and concatenate the difference vector with the vectors of each word vector representation. This allows us to feed additional structural information to different Neural Networks models (RNN, LSTM, GRU). We create three different model that manipulate this structural information differently to compare with baseline implementations to evaluate the perplexity chance in the word predictions.
We perform the hyper-parameter search that helps us to find the best model for each neural network. According to our results, the use of the differentiation vector in two of our models improves the perplexity of LSTM and GRU compared to the baseline model. Although the difference vectors lead to consistent improvements, these are not significant on the current, small number of experimental results.
