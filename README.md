# LLM-Based-Sentiment-Analysis
## Overview
Sentiment analysis is a powerful technique for understanding the emotions conveyed in text. By interpreting these emotions, businesses and organizations can gain valuable insights into public opinion, enabling them to make informed decisions that drive growth. This analysis provides real feedback from the public, helping organizations take necessary actions based on genuine sentiments.

I have developed a sentiment analysis model designed to help people understand the sentiment behind various texts. This model has been trained on diverse datasets, like the IMDB dataset and Hotel dataset and ensuring its ability to accurately interpret emotions from different sources of text.

To achieve this, a Large Language Model (LLM) was utilized and fine-tuned on these datasets. In the field of AI, one of the greatest advancements has been the development of transformers, which are designed to understand natural language with exceptional efficiency and accuracy. By incorporating this technique into my analysis, the model can accurately understand, interpret, and predict sentiments from text.

## Key Features
1. Data Wrangling: Collected data from multiple sources including the Stanford Library, Trivago Website, and other hotel websites.
2. Data Preprocessing: Utilized Python's Pandas library for efficient data preprocessing.
3. Exploratory Data Analysis (EDA): Implemented under sampling to address data imbalance.
4. Hugging Face Integration: Leveraged the Hugging Face Transformer library for accessing the Large Language Model (LLM), Tokenizer, and Datasets.
5. Parameter-Efficient Fine-Tuning (PEFT): Employed the Low-Rank Adaptation (LoRA) technique for faster and optimized training.
6. Fine-Tuning: Used Trainer and Training Arguments to fine-tune the DistilBERT LLM model.

## Usage
### Data Wrangling
Collected data from multiple sources including:
- Stanford Library
- Trivago Website
- Other hotel websites

### Data Preprocessing
- Utilized Python's Pandas library for data preprocessing. This step involves cleaning the data, handling missing values, and preparing the data for analysis.

### Exploratory Data Analysis (EDA)
- Implemented under sampling to address data imbalance. This ensures that the model is trained on a balanced dataset, improving its ability to generalize to unseen data.

### Model Training
- Leveraged the Hugging Face Transformer library for accessing the DistilBERT LLM model, tokenizer, and datasets. Employed the Low-Rank Adaptation (LoRA) technique for 
  faster and optimized training. Fine-tuned the model using the Trainer and Training Arguments.

## Skills and Tools
1. Data Preprocessing: Pandas Library
2. EDA: Pandas Library
3. PEFT Technique: LoRA for fast and optimized training
4. LLM Model: Hugging Face for accessing DistilBERT LLM Model
