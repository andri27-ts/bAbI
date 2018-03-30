# Bubble

This repository contains a simple Question Answering algorithm developed in Tensorflow. 
We'll use the bAbI tasks 1-20, created by facebook, for testing the capacity of our algorithm to understand and reason the text.


## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

In order to run the notebook you need to install tensorflow and tqdm (to take progress).

```
$ pip install tensorflow --upgrade
$ pip install tqdm
```

### Installing

Next, install [git](https://git-scm.com/) if you don't have already it and run the following commands on your terminal

```
$ cd $HOME  # or any other development directory you prefer
$ git clone 
$ cd bAbI
```

## Tensorboard

To keep track of the progress and to visualize the histograms of the NN layers, use Tensorboard, running on your terminal

```
$ cd $HOME  # or any other development directory you prefer
$ cd bAbI
$ tensorboard --logdir tf_logs
```


## Contributing
Please let me know if you need more information or if you want to contribute in any way