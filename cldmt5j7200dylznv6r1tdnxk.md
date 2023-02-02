# #87 Machine Learning & Data Science Challenge 87

# What do you understand by TF-IDF?

### TF-IDF:

I**t stands for the term frequency-inverse document frequency.**

### TF-IDF weight:

* It is a statistical measure used to evaluate how important a word is to a document in a collection or corpus.
    
* The importance increases proportionally to the number of times a word appears in the document but is offset by the frequency of the word in the corpus.
    

1. **Term Frequency (TF):**
    

* It is a scoring of the frequency of the word in the current document.
    
* Since every document is different in length, it is possible that a term would appear much more times in long documents than in shorter ones. The term frequency is often divided by the document length to normalize
    

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1675183559396/2db00a52-b358-4780-98c6-95de5c74bcf2.png align="center")

1. **Inverse Document Frequency (IDF):**
    

* It is a scoring of how rare the word is across the documents. It is a measure of how rare a term is, the Rarer the term, and more is the IDF score.
    

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1675183584311/022fc019-6731-4fde-95f4-4ddccb3cff38.png align="center")

Thus,

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1675183594558/7a7d543d-19cc-45c3-a42c-d37a0c75d77f.png align="center")