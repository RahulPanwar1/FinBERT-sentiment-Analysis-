# Enhancing Sentiment Analysis in Forex Trading Using FinBERT

## Table of Contents

1. [ Description ](#description)
2. [ Installation ](#installation)
3. [ Usage ](#usage)


## Description:
Improved the accuracy of the FinBERT model after Fine tuning the model on the Paraphrased dataset using ChatGPT 3.5 and Pegasus.
Used the Data Augmentation Technique of Paraphrasing on ChatGPT using the specific Prompt - "Generate a paraphrase for the following text, preserving the sentiment of the following statement: text" and with Pegasus keeping the sentiment of the news headlines same. Fine tuned the FinBERT model on the new augmented dataset. 

## Installation
<br>

- Clone the repository using:

```
git clone git@github.com:RahulPanwar1/FinBERT-sentiment-Analysis-.git
```
- For the dataset creation using ChatGPT 3.5 use the API key for ChatGPT and use the Prompt - "Generate a paraphrase for the following text, preserving the sentiment of the following statement: text" on the title column for generating the dataset.
- Setup the dataset in the .ipynb file 

## Usage:

Save the Fine-Tuned model and do the sentiment Prediction 


