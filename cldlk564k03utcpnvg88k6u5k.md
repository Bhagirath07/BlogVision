# #86 Machine Learning & Data Science Challenge 86

# What is Bag-of-Words Model?

We need a way to represent text data for the machine learning algorithms, and the bag-of-words model helps us to achieve the task.

* This model is very understandable and to implement.
    
* It is a way of extracting features from the text for use in machine learning algorithms.
    
* In this approach, we use the tokenized words for each of observation and find out the frequency of each token.
    
* Let’s do an example to understand this concept in depth.
    

1. “It is going to rain today.”
    
2. “Today, I am not going outside.”
    
3. “I am going to watch the season premiere.”
    

* We treat each sentence as a separate document and we make a list of all words from all three documents excluding the punctuation.
    
* We get, ‘It’, ’is’, ’going’, ‘to’, ‘rain’, ‘today’ ‘I’, ‘am’, ‘not’, ‘outside’, ‘watch’, ‘the’, ‘season’, ‘premiere.’
    
* The next step is the create vectors. Vectors convert text that can be used by the machine learning algorithm.
    
* We take the first document — “It is going to rain today”, and we check the frequency of words from the ten unique words.
    

**“It” = 1, “is” = 1, “going” = 1, “to” = 1, “rain” = 1, “today” = 1, “I” = 0, “am” = 0, “not” = 0, “outside” = 0**.

#### The rest of the documents will be:

* “It is going to rain today” = \[1, 1, 1, 1, 1, 1, 0, 0, 0, 0\]
    
* “Today I am not going outside” = \[0, 0, 1, 0, 0, 1, 1, 1, 1, 1\]
    
* “I am going to watch the season premiere” = \[0, 0, 1, 1, 0, 0, 1, 1, 0, 0\]
    
    *In this approach, each word (a token) is called a “gram”. Creating the vocabulary of two-word pairs is called a bigram model.*
    

**The process of converting the NLP text into numbers is called vectorization in ML.**

#### There are different ways to convert text into vectors :

• Count the number of times that each word appears in the document.

• I am calculating the frequency that each word that appears in a document out of all the words in the document.