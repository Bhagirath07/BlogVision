# #31 Machine Learning & Data Science Challenge 31

# What is Association Analysis? Where is it used?

**Association analysis uses a set of transactions to discover rules that indicate the likely occurrence of an item based on the occurrences of other items in the transaction.**

* The technique of association rules is widely used for retail basket analysis. It can also be used for classification by using rules with class labels on the right-hand side. It is even used for outlier detection with rules indicating infrequent/abnormal association.
    
* Association analysis also helps us **to identify cross-selling opportunities.**
    
* for example, we can use the rules resulting from the analysis to place associated products together in a catalog, in the supermarket, or the Webshop, or apply them when targeting a marketing campaign for product B at customers who have already purchased product A.
    

### Association rules are given in the form below:

* **A=&gt;B**\[Support, Confidence\]
    
    * The part before ( **\=&gt;** ) is referred to as if (**Antecedent**).
        
    * The part after ( **\=&gt;** ) is referred to as then (**Consequent**).
        
    * Where A and B are sets of items in the transaction data, a and B are disjoint sets.
        

#### **Computer=&gt;Anti−virusSoftware\[Support=20%,confidence=60%\] Above rule says:**

1. 20% of transactions show Anti-virus software is bought with the purchase of a Computer.
    
2. 60% of customers who purchase Anti-virus software bought with the purchase of a Computer.
    

#### **An example of Association Rules \* Assume there are 100 customers:**

1. 10 of them bought milk, 8 bought butter, and 6 bought both of them 2.
    
    bought milk =&gt; bought butter.
    
2. support = P(Milk & Butter) = 6/100 = 0.06
    
3. confidence = support/P(Butter) = 0.06/0.08 = 0.75
    
4. lift = confidence/P(Milk) = 0.75/0.10 = 7.5