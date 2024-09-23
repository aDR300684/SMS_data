# SMS Data Analysis Project

## Project Overview
This project involves the application of Natural Language Processing (NLP) techniques on a large SMS dataset. The goal is to uncover meaningful insights and patterns from the text messages using various NLP models and techniques, including sentiment analysis, topic modeling, word frequency analysis, part-of-speech (POS) tagging, and message similarity analysis.

## Key Steps and Findings

### 1. Sentiment Analysis
- **Objective**: Determine the sentiment of the messages (positive, neutral, or negative).
- **Model Used**: Naive Bayes Classifier.
- **Key Findings**: Neutral and positive sentiments dominated the dataset, with fewer negative messages. This reflects the generally casual and friendly tone of SMS conversations.

### 2. Topic Modeling
- **Objective**: Identify common themes or topics in the messages.
- **Technique Used**: Latent Dirichlet Allocation (LDA).
- **Key Findings**: Key topics identified included casual conversations, greetings, humor, and planning-related exchanges. Word clouds were generated to visualize the most common words for each topic.

### 3. Word Frequency Analysis
- **Objective**: Analyze the most frequently used words and phrases.
- **Technique Used**: Bag-of-Words (BoW).
- **Key Findings**: Common words included casual terms such as "haha", "go", and "lol". This highlights the conversational and informal nature of the dataset.

### 4. Part-of-Speech (POS) Tagging
- **Objective**: Analyze the grammatical structure of the messages.
- **Key Findings**: Common **adjective-noun** pairs such as "next time" and **noun-verb** pairs such as "u go" were identified. Positive messages and longer messages tended to have more complex grammatical structures.

### 5. Similarity Analysis
- **Objective**: Analyze the similarity of messages across different users based on sentiment, message length, and country.
- **Technique Used**: Levenshtein Distance.
- **Key Findings**: Neutral messages were more similar in structure, while positive messages showed more variability. Short messages tended to be more similar than longer ones.

### 6. Message Complexity by POS Tags
- **Objective**: Measure sentence complexity using the diversity of POS tags.
- **Key Findings**: Positive and long messages had higher complexity, indicating richer sentence structures.

## Jupyter Notebook
The analysis is conducted using a Jupyter Notebook, which is included in this repository as `nus_sms.ipynb`. The notebook contains all the data processing, analysis, and visualizations that are part of this project.

## Requirements
To replicate the analysis, the following libraries and tools are required:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `nltk`
- `spacy`
- `scikit-learn`

## Conclusion
This project highlights the effectiveness of NLP techniques in understanding and analyzing text-based communication. The insights derived from this analysis could be used for various applications, such as sentiment tracking, message classification, and user behavior analysis.

## Author
- [aDR300684](https://github.com/aDR300684)