# Keyword_network_and_Word_frequency_analysis_using_R

Project 2
The objective of project 2 is to perform keyword network analysis and word frequency

analysis
Task 1
1. Use the solution from homework 1 question 3.1 as the adjacency matrix
2. Read the adjacency matrix and convert it into a weighted network
3. Compute node degree and strength
4. Show the top 10 nodes by degree and top 10 nodes by strength
5. Show the top 10 node pairs by weight
6. Plot average strength on y-axis and degree on x-axis

Task 2
The link provides the twitter data of Elon Musk from 2010-2021. For analysis consider
the years 2017-2021. Each year has thousands of tweets. Assume each year to be a
document (all the tweets in one year will be considered as a document).
1. Compute word frequencies for each year. Exclude the stop words
2. Show top 10 words (for each year) by the highest value of word frequency
3. Plot histogram of word frequencies for each year
4. Use Zipf’s law and plot log-log plots of word frequencies and rank for each year
5. Create bigram network graphs for each year

Submission Format
1. Submit all the solutions as an R markdown file
2. Students can also create their own custom functions if necessary
3. This is a group effort
4. Only one member from each group needs to submit the solution
5. Submit the solution by Dec 15



Homework-1 for reference 

Direct to consumer marketing is an effective strategy to distribute agricultural and farm
products to consumers. Farmers market forms an important link between farmers and
consumers that helps foster farmer consumer relationships. The United States Department of
Agriculture (USDA) has recognized the importance of farmers markets. Through its many
programs, USDA has helped the growth of farmers markets across the country.
The data file contains the following details
a. Variables indicating the geographical location of the farmers market (lat, long, street, county,
state etc.)
b. Variables indicating types of products (herbs, vegetables, seafood etc.)
c. Variables indicating type of payment accepted (cash, WIC, SNAP, SFMNP etc.)
d. Variables indicating online social media presence
e. Variables indicating date and time
The directory of farmers market across the US is given in the file Answer the following
questions from the dataset (fm.csv) For questions 1.2-1.3 use for loop
1.1 (10 points) Compute the number of farmers market in the United States
1.2 (10 Points) Write a code to compute the number of farmers markets by state and arrange
them in descending order of number of farmers market.
1.3 (10 Points) Write a code to compute the number of farmers market by cities in
Massachusetts and display the top five cities.
1.4 (10 Points) Write a code to show the top 5 states by number of farmers market that offers
coffee

From the “wine_data.csv” answer the following question
2.1 (20 points) Use the “designation” variable and calculate the number of 20 year old wine in
the dataset
In this problem, the students are expected to create a keyword co-occurrence network (KCN).
Any article be it academic or otherwise is tagged with a bunch of keywords to help the article
popup in database searches. Not all articles have the same type or an equal number of
keywords. They vary according to the content of the article.
A KCN is created by treating each keyword as a node and each co-occurrence of a pair of words
as a link between those two words (see Fig below). The number of times that a pair of words
co-occurs constitutes the weight of the link connecting these two keywords. The network
constructed in this manner represents a weighted network.
3.1 (40 points) Create a KCN network from a sample data
1. Download the dataset
(https://docs.google.com/spreadsheets/d/1GTwv07i98vL7S-J9eeP8NV1fJVnymm1eJ
31RDyt4Mxw/edit?usp=sharing)
2. Write an R code to extract keyword data from the above file and convert it to a
weighted adjacency matrix. See the figure below to understand the process
Submission Format
1. Each group should submit only one homework copy
2. Submit the R markdown file
3. Each question should be in one code block
4. The codes for reading the input data must be included in the code block
5. Make sure the code follows the R coding standards ( Link)
