# CS5425-big-data-and-data-science
Projects for CS5425 big data and data science

## 1. [Common Word Count](commonword)

* Problem:  
Given TWO textual files, count the number of words that are common 
* Goals:  
You should learn how to 
write programs that involve multiple stages
perform a task that combine information from two files
* Scenarios to consider:  
Remove stop-words like “a”, “the”, “that”, “of”, …
Sort the output in descending order of number of common words
* Input data:  
>- Use the stop-word file: 
Stopwords.txt
>- Use the following two files:
Task1-input1.txt
Task1-input2.txt
* Output:  
>- Wordcount for two input files
>- Top-15 output of the result using the data files listed above (you only need to extract these 15 output from the sorted output)

## 2. [Recommendation System](Recommendation-System)

Collaborative Filtering (CF)  
Item-based techniques have two major parts:
1. analyze the user-item matrix to identify relationships between different items, 
2. use these relationships to indirectly compute recommendations for uses.

So we need to implement two parts:  
1. PART 1: Compute the similarities between items.
1. PART 2: Predict the recommendation scores for every user. 

## 3. [User Clustering for StackOverflow](User-cluster)

Use k-means on Spark to cluser users of StackOverflow based on features.

We follow a structure like this. 
1. group the questions and answers together
2. computing the highest score
3. design the vectors for clustering from the data
4. clustering
5. some additional parts

## 3. [A survey for NoSQL](NoSQL.pdf.pdf)

The bigdata technologies raise more and more attentions in recent years, as the size of data, which the
internet companies usually deal with, has scale to TBs or PBs. The traditional databases meet great
challenges for the bigdata demands, especially the large scale and high-concurrency applications.
NoSQL databases are created for the raising demand for store and query for bigdata. This survey
paper will cover three representative databases of three different NoSQL types according to CS5425
course requirement and summarize the several key points, the course may certain, of each NoSQL
database.

Database list:  
Redis, Cassandra, Neo4j
