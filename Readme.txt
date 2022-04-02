What i have done is that i have extracted out the feature vector by using tf.idf for a partucular page and trained a neural network on all the links that we have collected. The I am using neural network to predict the labels and for the article ordering algorithm i have run bfs for level 2 and listed all the aricles according to the difficulty.

Steps to run the program

1-First runt he Train the neural network using Training_Data.ipny and from that i have obtained my model Neural Network Saved Model
2-Then Run Wikipedia_Graph_Analysis.ipny file to to first get the 10000 links by running bfs on them and saving the networkx graph in a pickle file called test.gpickle. Then run the remaning program to get the lables on the data we have scrapped and article ordering algorithm