# Transformer Based Recipe Classifier

# Motivation

In the last few years Transformer based models have revolutionized the NLP sphere
making it easy to use transfer learning to finetune an already pre-trained model
trained on very large corpora. In this task, given a predefined labeled data set with
recipes and a label of whether the recipe is good or bad.
This dataset only contains a thousand equally split entries. We will use transfer learning
to finetune large pre-trained transformer models and create a recipe classifier for a friend
who would like to open a restaurant!

![Random GIF](https://media.giphy.com/media/b5Hcaz7EPz26I/giphy.gif) 

#Requirements and Installation
Python 3.6.9
NVIDIA P6000 30 GB RAM 8 CPUS (or any NVIDIA GPU)
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

# Acknowledgement and Resources
I'd like to thank the team at Trevor Project for assigning this exciting project. It has been a pleasure 
creating this classifier and gaining new insights from the dataset

Resources:

Evaluating Gender Bias in Natural Language... (Sharma, Dey, Sinha 2020)
RecipeGPT: Generative Pre-training Based Cooking...(Lee et al, 2020)
RecipeNLP: A Cooking Recipes Dataset...(Bien et al, 2020)
RoBERTa: A Robustly Optimized BERT Pretraining Approach (Liu et al 2020)
DistilBERT, a distilled version of BERT: smaller, faster, cheaper and lighter (Sanh et al, 2020)
BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding (Devlin et al, 2020)

# Disclaimer
The data for this project was provided by The Trevor Project



