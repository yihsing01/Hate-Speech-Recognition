# Hate-Speech-Recognition

# Description
This project implements a hate speech recognition model using transfer learning with RoBERTa. The project is done using datasets used by similar existing works. The objective of the project is for the model to achieve higher accuracy score than the existing work with their respective dataset used.

# Research Paper
https://drive.google.com/file/d/1BKcTy9CvleRjXFbfNJvv2YsOaDosR97J/view?usp=sharing

# Techniques
Transfer learning with RoBERTa<br/>
Synonym augmentation to handle imbalanced data<br/>
Customised activation and loss functions<br/>
L2 regularization to prevent overfitting<br/>
Early stopping to improve training efficiency<br/>
Fine-tuning the RoBERTa model<br/>

# Datasets
This project uses three existing datasets that can be obtained on Hugging Face:
ETHOS: https://huggingface.co/datasets/ethos<br/>
stormfront: https://huggingface.co/datasets/hate_speech18<br/>
Davidson: https://huggingface.co/datasets/hate_offensive

# Instructions
1. Create a Kaggle account and log in.
2. Download the datasets, load them into your Kaggle account by the names 'ethos-dataset', 'davidson' and 'stormfront-dataset' respectively.
3. Download the codes, load them into your Kaggle account.
4. Open the code on Kaggle, turn on one of the GPU accelerators in the settings, run the code.
