# Sparse T5 Automatic Music Transcription
This project is being undertaken as part of the [SHREC](http://nsf-shrec.org/)-SURG 2022 program. The goal is to improve upon an existing paper [(Hawthorne et. al 2021)](https://arxiv.org/abs/2107.09142) in terms of compute power required and/or training time by replacing the standard scaled dot-product attention blocks with an implementation of the sparse attention blocks highlighted in [(Chris et. al 2019)](https://arxiv.org/abs/1904.10509).

## Dataset
Dataset, compute access allowing, will be the [MAESTRO v1.0.0](https://magenta.tensorflow.org/datasets/maestro#v100) dataset. This was chosen to be able to directly compare accuracy and training time with the original paper.

## Installation
[Conda](https://www.anaconda.com/) is recommended, and an environment file is provided to install the correct packages and their versions.
