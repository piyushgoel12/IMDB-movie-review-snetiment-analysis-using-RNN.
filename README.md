# IMDB-movie-review-snetiment-analysis-using-RNN.

Here is a machine learning aaplication i.e. Sentiment analaysis of IMDB movie reviews using RNN algorithm. 

Firstly the IMDB data was loaded which is publicly available using the .laod_data() function which was imported from the Keras library. 
Then I padded the sequences to make them of equal length. 
Then I defined the RNN model and added an embedded layer, a LSTM lyer and a dense layer to improve the functioning of the model. 
Here the activation function used is "tanh" we could have used "sigmoid" function too for easy functioning but it would have resulted in the less accuracy of the model. 
Now the model was compiled and trained with certain number of epochs (10) with a specific batch size. 
Finally, we evaluate the model and print the test score and accuracy of the model. 

So, this was all about "IMDB movie review sentiment analysis using RNN algorithm"
