This repository contains the code and data for the project on keyword network analysis and word frequency analysis. The project is divided into two tasks. The first task involves the keyword network analysis and the second task involves the word frequency analysis.

Requirements:
The code is written in Python and requires the following libraries:
NetworkX
Matplotlib
Numpy
Pandas
Seaborn
Nltk

Task 1: Keyword Network Analysis

The keyword network analysis involves the following steps:
Download the dataset zip
The Python code (keyword_network_analysis.py) extracts the keyword data from the dataset and converts it into a weighted adjacency matrix.
The adjacency matrix is then read and converted into a weighted network.
The node degree and strength are computed.
The top 10 nodes by degree and top 10 nodes by strength are displayed.
The top 10 node pairs by weight are displayed.
A plot of average strength on y-axis and degree on x-axis is displayed.

Task 2: Word Frequency Analysis

The word frequency analysis involves the following steps:
The Twitter data of Elon Musk from 2017-2022 is considered. Each year is assumed to be a document.
The word frequencies for each year are computed and the stop words are excluded.
The top 10 words (for each year) by the highest value of word frequency are displayed.
The histogram of word frequencies for each year is displayed.
Zipf’s law is used and log-log plots of word frequencies and rank for each year are displayed.
Bigram network graphs for each year are displayed.

Usage
To run the code, simply execute the following command in your terminal:


Results
The results of the analysis will be displayed in the form of plots and tables.
