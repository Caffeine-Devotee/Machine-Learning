# Machine-Learning
Course Project for CS651

This paper presents the use of machine learning for categorization of feedbacks as well as sentiment analysis of feedbacks in any respective domain. The text is used for generating quantitative representation of feedbacks. Does not only identify the polarity of a feedback but also identifies the extent of how positive or negative a feedback is. The project focuses on student feedbacks on instructors of various courses taken up during the semester.
The attached code is a Python implementation of a dictionary-based sentiment classification procedure which combines two different bootstrapping procedures, namely for subjectivity and polarity detection.

-Installing dependencies

    Python programming language and pip package manager

    $ pip install nltk  
    $ pip install stemmer 
    $ pip install numpy
    $ pip install pickle

    $ python 
        import nltk
        nltk.download() 

        From the list select and download the following corpora: tokenizers/punkt/english, wordnet, brown, conll2000 and treebank.

    pyml library is needed for the SVM classifier
    Download http://pyml.sourceforge.net/ and then issue:
    $ tar zxvf PyML-0.7.11.tar.gz
    $ cd PyML-0.7.11
    $ python setup.py build
    $ python setup.py install 
    
    
-How to Run

    To estimate the total sentiment and total normalized sentiment, you can simply execute the sentiment.py file and give the desired block of text as an argument. Make sure that you escape symbols such as '"' and '!'. 

    $ python sentiment.py "Delivery of instructor is clear. Knows the basic and advance of the course, best teacher ever."
