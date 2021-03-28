# Transformer Based Spam Classifier

# Motivation

In the last few years Transformer based models have revolutionized the NLP sphere
making it easy to use transfer learning to finetune an already pre-trained model
trained on very large corpora. In this task, I used a predefined labeled data set with
text messages and a label of whether the message is spam or ham.
We will use transfer learningto finetune large pre-trained transformer models and create a spam classifier 
![Random GIF](https://media.giphy.com/media/l0IylR4JqKHLjaP60/giphy.gif) 

#Requirements and Installation
Python 3.6.9
Google Colab GPU
fp 16 using NVIDIA, training at half precision reduces training time (Nvidia apx): https://docs.nvidia.com/deeplearning/performance/mixed-precision-training/index.html
anaconda or miniconda https://www.anaconda.com/products/individual

The project can be cloned on your device using the following command:
```git init```

```git clone https://github.com/abdulbaza/Recipe_Classifier.git```

After cloning into a directory of your choice

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install the following python packages:
```bash
pip install pytorch
pip install tensorflow
pip install transformers
pip install nltk
pip install numpy
pip install pandas
pip install sklearn
pip install seaborn
pip install ast
pip install tqdm
```
The project is fully runable in jupyternotebook which can be accessed with the command on Linux 
 ```bash
 jupyter notebook
```


