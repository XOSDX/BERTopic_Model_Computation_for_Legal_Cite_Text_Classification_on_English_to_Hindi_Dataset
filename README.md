# BERTopic Model Computation for Legal Cite Text Categorization on English to Hindi Dataset

This repository contains code and resources for a project to categorize the text using the BERTopic model on an English-to-Hindi legal dataset. The project uses the BERTopic algorithm to effectively group and classify text for prediction and analysis, and also help us analyze the weightage and importance of the words in the sentences in different languages in multiple possible cases.

Access the code from: 
https://github.com/XOSDX/BERTopic_Model_Computation_for_Legal_Cite_Text_Classification_on_English_to_Hindi_Dataset/blob/main/BERTopic_Model_Computation_for_Text_Categorization_and_Classification_on_English_to_Hindi_Dataset.ipynb
https://colab.research.google.com/drive/1gUmACsK2jtqXZV12u0XAD_AxuoOOZf32?usp=sharing

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Model](#model)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributions](#contributions)
- [License](#license)

## Overview

Legal citation prediction is a crucial aspect of Natural Language Processing (NLP) in the legal domain. This project employs the BERTopic model, a topic modeling technique based on transformers and clustering, to classify and group legal citations. The dataset used is an English-to-Hindi bilingual corpus tailored for legal texts.

### Project Objectives:
- Perform legal citation classification and topic modeling on English-to-Hindi legal texts.
- Utilize the BERTopic model to understand key citation clusters.
- Analyze the performance and accuracy of the classification on a bilingual dataset.

## Dataset

The dataset consists of English-to-Hindi legal texts, formatted to include citations, summaries, and reference sections. This bilingual corpus includes data processed for BERTopic, focusing on cleaning, tokenization, and multilingual embedding generation.

- **Data Format**: Text data with citation labels.
- **Data Preprocessing**: Tokenization, language translation consistency checks, removal of non-essential metadata, and multilingual embedding preparation.

- Dataset is accessible from the link -> https://www.kaggle.com/datasets/kuldeepsingharya/english-to-hindi-parallel-dataset
  
## Model

### BERTopic
BERTopic is a state-of-the-art topic modeling approach that utilizes embeddings generated from transformers to create dynamic topic clusters. It is particularly effective for legal text analysis, as it allows for an unsupervised yet highly relevant classification approach.

- **Embedding Model**: We use multilingual transformer embeddings to support English-Hindi processing.
- **Clustering Technique**: HDBSCAN for density-based clustering.
- **Dimensionality Reduction**: UMAP for reducing embedding dimensions.

### Key Features:
- **Multilingual Support**: Leverages multilingual embeddings to handle the English-Hindi corpus.
- **Dynamic Topic Generation**: Adapts to changing data clusters in legal citations.
- **Hierarchical Topic Representation**: Allows for nested legal citation clusters.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/BERTTopic_Model_Computation_for_Legal_Cite_Text_Classification.git
   cd BERTTopic_Model_Computation_for_Legal_Cite_Text_Classification

2. Install the required packages:
   pip install -r requirements.txt

## Results
The model was evaluated using the following metrics:

Topic Coherence: Ensures topics are meaningful and interpretable.
Accuracy: Measures classification performance based on citation labels.
Silhouette Score: Validates clustering quality.
For more detailed results, see the Results directory.

## Contributions
Contributions are welcome! Please submit a pull request or create an issue for any improvements, feature requests, or bug fixes.
