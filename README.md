# Character-name-extraction-from-movies-screenplays-nltk

In this code, we develop an algorithm to read the screenplays and automatically extract the character names from the screenplay as follow:

1- We propose a solution to create training data

2. We design two algorithm and compare between them.
3. 
4. We propose an evaluation metric and evaluate the result of your algorithm with the proposed metric.

This repository includes:

1- Final.ipynb includes the code and explanation of each step of the two algorithms proposed using nltk.

2- Movie Scripts folder: includes 10 movies scripts that we will test our algorithm on.

3- True label character names file: includes a dataset with the true character names for movies

4- Results of each movie folder: includec each movie results as a csv file with three columns:
   a) Method 1 extracted character names results 
   b) Method 2 extracted character names results
   c) True label of the character names
   
5- Prformance evaluation folder: includes the performance evaluation for method 1 and method d:
   a) Performance_Evaluation-Method1.csv includes method 1 performance evaluation for all 10 movies (TP, TN, and Accuracy)
   b) Performance_Evaluation-Method2.csv includes method 2 performance evaluation for all 10 movies (TP, TN, and Accuracy)
   c) Also it includes some plots of the TP, TN, Accuracy of each movie, mean and std dev of the total 10 movies accuracy.
