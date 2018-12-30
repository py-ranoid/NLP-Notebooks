## Notebooks on building bots by matching Queries with FAQs
I've explored the following methods to find closest questions:
- [Jaccard similarity](https://www.statisticshowto.datasciencecentral.com/jaccard-index/) on tokens : [Notebook](https://github.com/py-ranoid/FAQ-Bot-Notebooks/blob/master/idft_matching.ipynb)
- Term Frequency–Inverse Document Frequency ([TF-IDF](http://www.tfidf.com/)) : [Notebook](https://github.com/py-ranoid/FAQ-Bot-Notebooks/blob/master/idft_matching.ipynb)
- [Word Mover's Distance](http://proceedings.mlr.press/v37/kusnerb15.pdf) using word2vec (Google News model) : [Notebook](https://github.com/py-ranoid/FAQ-Bot-Notebooks/blob/master/wmd_matching.ipynb)
