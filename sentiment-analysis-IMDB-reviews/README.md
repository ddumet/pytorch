This a NLP (**Natural Language Processing**) learning project, of which task is to perform sentiment analysis on movie reviews. In this project we will be using an IMDB dataset containing 50,000 reviews classified as ***positive*** or ***negative***.

The core dataset contains 50,000 reviews split evenly into 25k train and 25k test sets. The overall distribution of labels is balanced (25k ***positive*** and 25k ***negative***). Also included are an additional 50,000 unlabeled documents for unsupervised learning.

**Our intent in that project is to use different methods, i.e. different ANN models and different text encodings/embeddings, in the search of the best accuracy.**

With regards to the ANN framework, we'll be using **PyTorch 1.5**.

This dataset has been made publicly available by the authors of the following paper:

***maas-EtAl:2011:ACL-HLT2011***
* **author**    = Maas, Andrew L.  and  Daly, Raymond E.  and  Pham, Peter T.  and  Huang, Dan  and  Ng, Andrew Y.  and  Potts, Christopher
* **title**     = Learning Word Vectors for Sentiment Analysis
* **booktitle** = Proceedings of the 49th Annual Meeting of the Association for Computational Linguistics: Human Language Technologies
* **date**      = June 2011
* **publisher** = Association for Computational Linguistics
* **pages**     = 142--150
* **url**       = http://www.aclweb.org/anthology/P11-1015

Also, the **best performances** of ANNs on this dataset are listed [here](https://paperswithcode.com/sota/sentiment-analysis-on-imdb). The different methods are often listed with a companion paper giving great source of inspiration.