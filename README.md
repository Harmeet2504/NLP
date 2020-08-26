# Natural Language Processing

This repo deals with the basic concepts and python codes for mining of text data using python and its open source libraries (NLTK, SpaCy, Gensim, TextBlob). The objective is to use machine learning and deep learning approaches for important Natural Language Processing techniques like Sentiment analysis and Topic modeling. The repo will be updated regularly as progress is made:

Key concepts/terminologies:

* Stemming: Usually the first step in pre-processing. A stemmer function converts words to corresponding root word. Eg. Responsive, Unresponsive, Respond, Responsible would be converted to respon.
* Lemmatization: Similar to stemming,difference being stemming usually refers to a crude heuristic process that chops off the ends of words in the hope of achieving its goal correctly most of the time, and often includes the removal of derivational affixes. Lemmatization usually refers to doing things properly with the use of a vocabulary and morphological analysis of words, normally aiming to remove inflectional endings only and to return the base or dictionary form of a word, which is known as the lemma .
* Stop words: Words that occur frequently but doesn't add meaning to the document. Eg. a, the, be etc.
* Bag-of-words: Representation of text that describes the measure of occurrence of words within a document. 
Eg. Text1: Sunny day
    Text2: Bright and sunny day
    Vocabulary of words:
    Sunny
    Day
    Bright
    And
  Vocabulary of word frequency (For Text1)
    Sunny-1
    Day-1
    Bright-0
    And-0
* Document-term matrix: or term-document matrix is a mathematical matrix that describes the frequency of terms that occur in a collection of documents. In a document-term matrix, rows correspond to documents in the collection and columns correspond to terms. There are various schemes for determining the value that each entry in the matrix should take. One such scheme is tf-idf.     
* TFIDF: TF-Term frequency: assigns weights to words proportional to their frequency within a document. IDF-Inverse Document Frequency: assigns weights to words inversely proportional to their frequency within a corpus. Rare words get more weight as they will likely give more sense to the corpus than common and most frequently occurring ones
* Parts of speech tagging: A Part-Of-Speech Tagger (POS Tagger) is a program that reads text data and assigns parts of speech to each word (and other token), such as noun, verb, adjective, etc., although generally computational applications use more fine-grained POS tags like 'noun-plural'. POS-tagging algorithms fall into two distinctive groups: rule-based and stochastic.




