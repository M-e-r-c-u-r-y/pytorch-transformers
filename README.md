# PyTorch Transformers

This repo contains tutorials covering transformer models using [PyTorch](https://github.com/pytorch/pytorch) 1.4 and [TorchText](https://github.com/pytorch/text) 0.5 using Python 3.6.

**If you find any mistakes with the code, please do not hesitate to submit an issue. I welcome any feedback, positive or negative!**

## Getting Started

To install PyTorch, see installation instructions on the [PyTorch website](pytorch.org).

To install TorchText:

``` bash
pip install torchtext
```

We'll also make use of spaCy to tokenize our data. To install spaCy, follow the instructions [here](https://spacy.io/usage/) making sure to install both the English and German models with:

``` bash
python -m spacy download en
python -m spacy download de
```

## Tutorials

* 1 - [Multi Head Attention is All You Need](https://github.com/M-e-r-c-u-r-y/pytorch-transformers/blob/master/Attention%20is%20All%20You%20Need.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/M-e-r-c-u-r-y/pytorch-transformers/blob/master/Attention%20is%20All%20You%20Need.ipynb)
* 2 - [Attention is All You Need(einsum Notation)](https://github.com/M-e-r-c-u-r-y/pytorch-transformers/blob/master/Attention%20is%20All%20You%20Need(einsum%20Notation).ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/M-e-r-c-u-r-y/pytorch-transformers/blob/master/Attention%20is%20All%20You%20Need(einsum%20Notation).ipynb)
* 3 - [Multi Query Attention](https://github.com/M-e-r-c-u-r-y/pytorch-transformers/blob/master/Multi%20Query%20Attention.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/M-e-r-c-u-r-y/pytorch-transformers/blob/master/Multi%20Query%20Attention.ipynb)
* 4 - [Multi Query Attention using (einsum Notation)](https://github.com/M-e-r-c-u-r-y/pytorch-transformers/blob/master/Multi%20Query%20Attention%20using%20(einsum%20Notation).ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/M-e-r-c-u-r-y/pytorch-transformers/blob/master/Multi%20Query%20Attention%20using%20(einsum%20Notation).ipynb)
## References

Here are some things I looked at while making these tutorials. Some of it may be out of date.

- https://github.com/bentrevett/pytorch-seq2seq
