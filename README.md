# Bert Embeddings

[![Build Status](https://travis-ci.org/imgarylai/bert_embedding.svg?branch=master)](https://travis-ci.org/imgarylai/bert_embedding) [![PyPI version](https://badge.fury.io/py/bert-embedding.svg)](https://badge.fury.io/py/bert-embedding)

## Install

```
pip install bert-embedding
```
If you want to run on GPU machine, please install `mxnet-cu92`.

```
pip install mxnet-cu92
```

## Usage

```python
from bert_embedding import BertEmbedding

sentences = ["Hello World", "Token level embeddings from BERT model on mxnet and gluonnlp"]
bert = BertEmbedding()
result = bert.embedding(sentences)
```