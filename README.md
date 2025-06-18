# Deep Learning for Natural Language Processing

This repository contains implementations of various deep learning models for natural language processing (NLP) tasks, specifically sentiment classification on an English Twitter dataset. The project is based on assignments for the Department of Informatics and Telecommunications (DIT) at the University of Athens (UOA).

## Table of Contents

- [Overview](#overview)
- [Repository Structure](#repository-structure)
- [Models Implemented](#models-implemented)
- [Setup Instructions](#setup-instructions)
- [Usage](#usage)
- [Results](#results)
- [License](#license)

---

## Overview

The goal of this project is to build and fine-tune sentiment classifiers using various deep learning models, including BERT, DistilBERT, and traditional machine learning approaches like TF-IDF with logistic regression. The models are trained and evaluated on a Twitter dataset, with the final goal of predicting sentiment labels for unseen tweets.

---

## Repository Structure

```
├── data/
│   ├── sample_submission.csv
│   ├── test_dataset.csv
│   ├── train_dataset.csv
│   ├── val_dataset.csv
├── docs/
│   ├── AI2_Homework_1_2025.pdf
│   ├── AI2_Homework_2_2025.pdf
│   ├── AI2_Homework_3_2025.pdf
├── notebooks/
│   ├── bert_transformer.ipynb
│   ├── distilbert_transformer.ipynb
│   ├── tfidf_logistic_regression.ipynb
│   ├── word_embeddings_deep_neural_networks.ipynb
├── reports/
│   ├── figures/
│   │   ├── activation_functions_training_results.png
│   │   ├── base_model_training_results.png
│   │   ├── dataset_file_sizes_pie.png
│   ├── PDFs/
│   │   ├── BERT_and_DistilBERT_transformers_in_NLP.pdf
│   │   ├── TF-IDF_and_Logistic_Regression_in_NLP.pdf
│   │   ├── Word_Embeddings_and_FeedForward_Neural_Networks.pdf
├── LICENSE
├── README.md
```

### Key Files and Directories

- **`data/`**: Contains the datasets used for training, validation, and testing.
- **`docs/`**: Documentation and assignment PDFs related to the project.
- **`notebooks/`**: Jupyter notebooks implementing various models and experiments.
- **`reports/`**: Visualizations and reports generated during the experiments.
- **`requirements.txt`**: Python dependencies required to run the project.
- **`LICENSE`**: MIT License for the repository.

---

## Models Implemented

1. **BERT**:
   - Fine-tuned using the `bert-base-uncased` model from HuggingFace.
   - Implemented in [notebooks/bert_transformer.ipynb](notebooks/bert_transformer.ipynb).

2. **DistilBERT**:
   - Fine-tuned using the `distilbert-base-uncased` model from HuggingFace.
   - Implemented in [notebooks/distilbert_transformer.ipynb](notebooks/distilbert_transformer.ipynb).

3. **TF-IDF with Logistic Regression**:
   - A traditional machine learning approach for sentiment classification.
   - Implemented in [notebooks/tfidf_logistic_regression.ipynb](notebooks/tfidf_logistic_regression.ipynb).

4. **Word Embeddings with Deep Neural Networks**:
   - Explores the use of word embeddings in deep learning models.
   - Implemented in [notebooks/word_embeddings_deep_neural_networks.ipynb](notebooks/word_embeddings_deep_neural_networks.ipynb).

---

## Setup Instructions

### Prerequisites

- Python 3.8 or higher
- GPU support (optional but recommended for training deep learning models)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/AntonisZks/Deep-Learning-for-Natural-Language-Processing.git
   cd Deep-Learning-for-Natural-Language-Processing

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Download the datasets and place them in the [`data/`](data/) directory

## Usage

### Running Notebooks

1. Open any of the Jupyter notebooks in the `notebooks/` directory to explore the models:
   - [BERT Transformer](notebooks/bert_transformer.ipynb)
   - [DistilBERT Transformer](notebooks/distilbert_transformer.ipynb)
   - [TF-IDF Logistic Regression](notebooks/tfidf_logistic_regression.ipynb)
   - [Word Embeddings with Deep Neural Networks](notebooks/word_embeddings_deep_neural_networks.ipynb)

2. Execute the cells step-by-step to train, evaluate, and test the models.

### Training and Evaluation

- Modify hyperparameters, dataset paths, or model configurations directly in the notebooks.
- Use the provided visualization functions to analyze training and validation performance.

## Usage

### Running Notebooks

1. Open any of the Jupyter notebooks in the `notebooks/` directory to explore the models:
   - [BERT Transformer](notebooks/bert_transformer.ipynb)
   - [DistilBERT Transformer](notebooks/distilbert_transformer.ipynb)
   - [TF-IDF Logistic Regression](notebooks/tfidf_logistic_regression.ipynb)
   - [Word Embeddings with Deep Neural Networks](notebooks/word_embeddings_deep_neural_networks.ipynb)

2. Execute the cells step-by-step to train, evaluate, and test the models.

### Training and Evaluation

- Modify hyperparameters, dataset paths, or model configurations directly in the notebooks.
- Use the provided visualization functions to analyze training and validation performance.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.