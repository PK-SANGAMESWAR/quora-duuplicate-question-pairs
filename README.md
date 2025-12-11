# Duplicate Question Pairs

This project aims to detect duplicate questions from the Quora dataset using various Natural Language Processing (NLP) techniques and Machine Learning models.

## Project Structure

- `BoW_with_adv_features.ipynb`: Notebook containing Bag of Words implementation with advanced feature extraction.
- `BoWwithfeatures.ipynb`: Notebook with standard Bag of Words features.
- `BoWwithoutpre.ipynb`: Notebook demonstrating Bag of Words without preprocessing.
- `eda.ipynb`: Exploratory Data Analysis of the dataset.
- `main.py`: Simple entry point script.
- `train.csv.zip`: Dataset file.

## Features

- **Data Preprocessing**: Cleaning and normalizing text data (removing special characters, decontracting words, etc.).
- **Feature Extraction**:
    - Basic Features: specific characteristics of the questions.
    - Advanced Features: complex NLP-based features including fuzzy matching and distance metrics.
- **Machine Learning**: Utilization of models like XGBoost for classification.

## Installation

1.  Clone the repository.
2.  Install the required dependencies:

```bash
pip install -r requirements.txt
```

## Usage

You can run the analysis by executing the Jupyter Notebooks:

```bash
jupyter notebook BoW_with_adv_features.ipynb
```

Or run the main script:

```bash
python main.py
```
