README
This file includes step by step instructions about how to run the code and how to select the different functions, algorithms and/or other options to run the ranking scores.
This code has to be downloaded and imported in any python-supported platform (this was created using jupyter notebook (Anaconda), as a reference) together with the file to be analysed “dataset_tweets_WHO.txt”.


Important: 


The attached file y_true.csv is a file that contains the ground truth for each document  and query in a binary way. 
The code in the beggining creates and benchmarks the indexes corresponding to the given dataset. If a search in the index is wanted, only numbers, letters and characters # and @ are allowed.
The rank_tweets function classifies documents in a tf-idf way and returns a ranked list.
The functions query_output and display_tweets display the main information of the retrieved tweets.
The next cells can be modified in case tests want to be made.
Then, a dataset is created and an evaluation on the search engine is done. Methods used and details of them are specified in the report.
Finally, the last 3 cells complete a vector representation of the tweets using the t-sne algorithm. Parameters in Word2Vec function can be changed in order to experiment with it.