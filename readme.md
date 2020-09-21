# Team Binet - SONNET AI

Sonnet AI is a character level RNN that can generate meaningful and sonnets based on Shakespeare's Sonnet

## Requirements
1. Python 64bit 

## Getting Started/Installation

1. Use the package manager [pip](https://pip.pypa.io/en/stable/) to 
 install tools required.

```bash
pip install -r requirements.txt
```                                                                     
 This will install all the necessary libraries and tools. Pytorch 
 installations may fail depending on the system and availability of GPU. 
 In that case delete the Pytorch entry from requirements file and follow 
 the below steps
 a. Visit https://pytorch.org/
 b. Select your configurations from the options and run the generated command on your commandline

2. In your terminal cd to this github project downloaded (eg cd Downloads\Sonnet-Ai) and run 
 ```bash
 jupyter notebook
```
This will open up the notebook for running the code

### sonnet_training Notebook
Almost Nothing has to be run in this notebook. This was where we trained all our models 

### sonnet_loading Notebook
This is where we do our inference. After running all the cells. The last cell can be used to get new poems.  


## References

The sonnet_training notebook is based upon the Udacity Deep Learning Course in which one of our team member is enrolled  https://github.com/udacity/deep-learning-v2-pytorch/tree/master/recurrent-neural-networks/char-rnn

