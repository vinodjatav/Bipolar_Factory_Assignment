# Bipolar_Factory_Assignment
Crawl news &amp; information websites & anticipate the likelihood of its virality.

### Required Packages!
In the very fisrt step we need some packeges to extract news headline from news websites.\
Here is the list of packeges with their description.
1) bs4 in python\
bs4 — BeautifulSoup 4. Beautiful Soup is a Python library for pulling data out of HTML and XML files.

2) gensim in python\
Gensim is implemented in Python and Cython. Gensim is designed to handle large text collections using data streaming and incremental online algorithms, which differentiates it from most other machine learning software packages that target only in-memory processing.

3) nltk in python\
The Natural Language Toolkit (NLTK) is a platform used for building Python programs that work with human language data for applying in statistical natural language processing (NLP). It contains text processing libraries for tokenization, parsing, classification, stemming, tagging and semantic reasoning.

4) itertools in python\
The Python itertools module is a collection of tools for handling iterators. Simply put, iterators are data types that can be used in a for loop. The most common iterator in Python is the list.

5) WordNetLemmatizer\
Lemmatization is the process of grouping together the different inflected forms of a word so they can be analysed as a single item. Lemmatization is similar to stemming but it brings context to the words. So it links words with similar meaning to one word. Text preprocessing includes both Stemming as well as Lemmatization. Many times people find these two terms confusing. Some treat these two as same. Actually, lemmatization is preferred over Stemming because lemmatization does morphological analysis of the words.

Applications of lemmatization are:


    Used in comprehensive retrieval systems like search engines.
    Used in compact indexing

 Examples of lemmatization:

-> rocks : rock\
-> corpora : corpus\
-> better : good

6) requests module in python\
Requests is a Python module that you can use to send all kinds of HTTP requests. It is an easy-to-use library with a lot of features ranging from passing parameters in URLs to sending custom headers and SSL Verification.

### First Step: Extract the Headline from Viral News Websites
In this step take some url of news website and extract the headlines from the viral news website.
### Second Step: Pre processs the text and convert to tokens
In this step preprocess the text of headline news and convert to tokens and pass these tokens to the Bow and LDA models.
### Third Step: Build the Bow and LDA models
LDA is a generative probabilistic model that assumes each topic is a mixture over an underlying set of words, and each document is a mixture of over a set of topic probabilities.\
LDA Implementation

    Loading data
    Data cleaning
    Exploratory analysis
    Preparing data for LDA analysis
    Model Evaluation and parameter tuning


### Visualised The Results
Show the headline and wesite link
