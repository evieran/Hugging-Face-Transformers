# Hugging-Face-Transformers

This project serves educational purposes and is focused on demonstrating the use of Hugging Face Transformers for tasks like Named Entity Recognition (NER) and Sentiment Analysis. Here, you'll find guidelines to set up the environment and execute various tasks.

## Setup Environment
Ensure to execute this notebook in the course's Python environment to install all the prerequisites:

!pip install tensorflow
!pip install torch
!pip install keras
!pip install transformers
!pip install datasets
!pip install sentencepiece
!pip install evaluate
!pip install nltk
!pip install rouge_score

## Named Entity Recognition
Explore basic and enhanced Named Entity Recognition using Transformers.

- Basic NER
import transformers
from transformers import pipeline

- Enhanced NER
from transformers import AutoTokenizer, TFAutoModelForTokenClassification

## Sentiment Analysis with Transformers
Explore sentiment analysis with Hugging Face Transformers.

- Reviewing the pipeline
import transformers
from transformers.pipelines import PIPELINE_REGISTRY

- Predicting Sentiment with Default Model
from transformers import pipeline
import os

- Using a Custom Model
sentiment_classifier = pipeline(task="sentiment-analysis",
                                model="finiteautomata/bertweet-base-sentiment-analysis")





