# Topic Modeling on news articles
Large amounts of data are collected everyday. As more information becomes available, it becomes difficult to access what we are looking for. So, we need tools and techniques to organize, search and understand vast quantities of information.Topic modelling provides us with methods to organize, understand and summarize large collections of textual information. 
### Problem Description
The npr dataset has around 12000 news articles,unlabeled,we need to extract groups of important words from these articles.These groups of words are basically topics which would help in ascertaining what each article is about. 
### Objectives
Our goal is to identify the number of topics and determine the theme of each topic.
### Approaches
This is an unsupervised learning problem in which we find various topics that are present in the news articles.I will be using the Latent Dirichlet Allocation (LDA) from Gensim package along with the Mallet’s implementation.
### Libraries used
gensim,nltk and spacy are used to process text.pyLDAvis,matplotlb and seaborn for visualization and numpy and pandas for manipulating and viewing data in a tabular format.


