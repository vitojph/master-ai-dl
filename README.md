# README

This repository contains the materials used in the Master on Artificial Intelligence and Deep Learning.

## Dependencies

Before running the notebooks, make sure you have installed all the dependencies, namely:

### For the notebook on [Word Embeddings](word-embeddings.ipynb)

Create a virtual env with `conda` and Python>=3.6

    conda create -n nlp python=3.7 pip jupyterlab
    conda activate nlp

Install the libraries

    pip install pandas numpy scikit-learn
    pip install nltk
    pip install spacy
    pip install gensim
    pip install keras

Install the correct version of TF:

    pip install tensorflow-cpu | tensorflow
    
Lastly, download the models

    python -m nltk.downloader punkt    
    python -m nltk.downloader brown
    python -m nltk.downloader cess_esp
    python -m spacy download en_core_web_md
    python -m spacy download es_core_news_md



### For the notebook on [Contextual Word Embeddings](contextual-embeddings.ipynb)

Create a virtual env with `conda` and Python==3.6

    conda create -n dlnlp python=3.6 pip jupyterlab
    conda activate dlnlp

Install fastai

    pip install http://download.pytorch.org/whl/cpu/torch-1.0.0-cp36-cp36m-linux_x86_64.whl
    pip install fastai

Install flair and allennlp

    pip install flair
    pip install allennlp

Install transformers

    pip install transformers



## Notebooks

- [NLP is all Around](nlp-is-all-around.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/vitojph/master-ai-dl/blob/master/nlp-is-all-around.ipynb)

- [Named Entities Recognition & Question Answering](ner-qa.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/vitojph/master-ai-dl/blob/master/ner-qa.ipynb)

- [Word Embeddings](word-embeddings.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/vitojph/master-ai-dl/blob/master/word-embeddings.ipynb)

- [Word Vectors with `gensim`](gensim-word_vectors.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/vitojph/master-ai-dl/blob/master/gensim-word_vectors.ipynb)

- [Contextual Embeddings](contextual-embeddings.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/vitojph/master-ai-dl/blob/master/contextual-embeddings.ipynb)
