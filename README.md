# Introduction
Re-implementation of `Kim, Yoon. "Convolutional neural networks for sentence classification." arXiv preprint arXiv:1408.5882 (2014).`

# Requirements
* Python 3.*
* Chainer ver. 1.19.0 (or more)

# Usage
```
  $ python train_cnn.py
```

# Optional arguments
```
  -h, --help            show this help message and exit
  --gpu   GPU           negative value indicates cpu
  --epoch EPOCH         number of epochs to learn
  --batchsize BATCHSIZE
                        learning minibatch size
```

# Data format for input data
  - [0 or 1] [Sequence of words]
    - 1 and 0 are positive and negative, respectively.

## Examples
```
1 That was so beautiful that it can't be put into words . (POSITIVE SETENCE)
0 I do not want to go to school because I do like to study math . (NEGATIVE SENTENCE)
```
