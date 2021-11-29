README
This file includes step by step instructions about how to run the code and how to select the different functions, algorithms and/or other options to run the ranking scores.
This code has to be downloaded and imported in any python-supported platform (this was created using jupyter notebook (Anaconda), as a reference) together with the file to be analysed “dataset_tweets_WHO.txt”.


Important: 


The attached file “y_true.csv” is a file that contains the ground truth for each document and query in a binary way. 
The code in the beggining creates and benchmarks the indexes corresponding to the given dataset. If a search in the index is wanted, only numbers, letters and characters # and @ are allowed.
The “rank_tweets” function classifies documents in a tf-idf way and returns a ranked list.
The “rank_tweets_ours” function classifies the documents by also taking into account popularity aspects such as number of likes or followers.
The “rank_tweets_word2vec” function classifies the documents using the word2vec model.
The functions “query_output” and “display_tweets” display the main information of the retrieved tweets.
The cell after the definition of functions “query_output” and “display_tweets” displays the results for the main queries chosen beforehand (by default). After that, you can find an interactive way of testing the search engine, by inserting any query and any of the allowed modes of ranking and getting as an output the top ranked tweets.


Any other functions and/or displays are commented and explained in the code itself