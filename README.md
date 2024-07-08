# MLHC_project_2

This project involves performing 3 tasks to solve a classification problem on a dataset consisting of 200k Pubmed RCT abstracts. In total, the dataset consists of 2.3MM sentences, each of which must be classified to 5 categories (BACKGROUND, OBJECTIVE, METHODS, RESULTS, CONCLUSIONS).

The tasks are:
1) Use a TF-IDF (e.g. sklearn TfidfVectorizer) preprocessing step followed by a classifier.
2) Train and use a word embedding Word2Vec or FastText (e.g. gensim library) model as preprocessing step followed by a classifier (that acts on concatenated or averaged embedding).
3) Use a pretrained BERT model with and w/o finetuning (HuggingFace transformers).

Most convenient way to run this notebook is on google colab.

To do so, please first download the dataset from https://github.com/Franck-Dernoncourt/pubmed-rct/tree/master.