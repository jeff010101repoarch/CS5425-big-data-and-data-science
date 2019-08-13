# User Clustering for StackOverflow

Use k-means on Spark to cluser users of StackOverflow based on features.

We follow a structure like this. 
1. group the questions and answers together
2. computing the highest score
3. design the vectors for clustering from the data
4. clustering
5. some additional parts

DATA:  
Available [[here]](https://drive.google.com/open?id=12SqeviOLKMalmxnGW3y2CMO1nF0RUiQR)

The data value: (1,100,  ,9,Big Data)  
The meaning: PostingType, ID, ParentID, Score, Domains.
* PostingType:
* PostingType=1: this post is a question.
* PostingType=2: this post is an answer.
* ID: the id for the post	
* ParentId: which question it belongs to.
* Score: the score of the answer.
* Domains: which domain does this question belong to.

find more in [document](document.pdf)