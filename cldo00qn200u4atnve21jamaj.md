# #89 Machine Learning & Data Science Challenge 89

# What is Doc2vec?

**Paragraph Vector (more popularly known as Doc2Vec) — Distributed Memory (PV-DM)**

Paragraph Vector (Doc2Vec) is supposed to be an extension to Word2Vec such that Word2Vec learns to project words into a latent d-dimensional space whereas Doc2Vec aims at learning how to project a document into a latent d-dimensional space.

The basic idea behind PV-DM is inspired by Word2Vec. In the CBOW model of Word2Vec, the model learns to predict a center word based on the context.

* For example- given the sentence “The cat sat on the table”, the CBOW model would learn to predict the words “sat” given the context words — the cat, on, and table.
    
* Similarly, in PV-DM the main idea is: randomly sample consecutive words from the paragraph and predict a center word from the randomly sampled set of words by taking as the input — the context words and the paragraph id.
    

Let’s have a look at the model diagram for some more clarity.

* In this given model, we see the Paragraph matrix, (Average/Concatenate) and classifier sections.
    
* **Paragraph matrix**: It is the matrix where each column represents the vector of a paragraph.
    
* **Average/Concatenate**: It means whether the word vectors and paragraph vectors are averaged or concatenated.
    
* **Classifier**: In this, it takes the hidden layer vector (the one that was concatenated/averaged) as input and predicts the Centre word
    

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1675184908641/4040cf41-4ae5-403a-ba39-500734ff3c0b.png align="center")

In matrix D, It has the embeddings for “seen” paragraphs (i.e. arbitrary length documents), the same way Word2Vec models learn embeddings for words.

* For unseen paragraphs, the model is again run through gradient descent (5 or so iterations) to infer a document vector.