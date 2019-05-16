# Credit Card Fraud Detection
Throughout the financial sector, machine learning algorithms are being developed to detect fraudulent transactions. In this project, that is exactly what we are going to be doing as well. Using a dataset of of nearly 28,500 credit card transactions and MLP(Multi Layer Perceptron) Algorithms, we are going to identify transactions with a high probability of being credit card fraud. In this project, we will build and deploy using the single hidden layer algorithm .


1. PreRequisites :
    1. Install Julia either using Anaconda or separate executable .
	2. Install the necessary dependency files as mentioned in step 2


2. Importing Necessary Libraries
To start, let's print out the version numbers of all the libraries we will be using in this project. This serves two purposes - it ensures we have installed the libraries correctly and ensures that this tutorial will be reproducible.

using DataFrames, CSV;
using Flux;

3.Output :
There could be two possibilities for the output :It could either be fraudulent or non-fraudulent.

4.Reading DataSet :
Our data set is the csv file which has 28,500 records .

# Reading our dataset from creditcard.csv file
dataset = CSV.read("creditcard.csv");

5.Machine learning Algorithm:

We used MultiLayer Perceptron machine learning algorithm.
We are using 1 hidden layer .
