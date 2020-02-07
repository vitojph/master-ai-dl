# Managing Dependencies

## For the notebook on [Word Embeddings](word-embeddings.ipynb)

Create a virtual env with `conda` and Python>=3.6

    conda create -n nlp python=3.7 pip jupyterlab
    conda activate nlp

Install the libraries

    pip install pandas numpy scikit-learn
    pip install nltk
    pip install spacy
    pip install gensim
    pip install tensorflow-cpu | tensorflow
    pip install keras

Download the models

    python -m nltk.downloader brown
    python -m nltk.downloader cess_esp
    python -m spacy download en_core_web_md
    python -m spacy download es_core_news_md



## For the notebook on [Contextual Word Embeddings](contextual-embeddings.ipynb)

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

