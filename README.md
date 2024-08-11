# Text Classification Project

## Overview
This project focuses on classifying text data using various natural language processing (NLP) techniques. The primary goal is to preprocess the text data and train a machine learning model to categorize the text into predefined categories.

## Table of Contents
* Installation
* Usage
* Project Structure
* Methodology
* Results

## Installation
### Prerequisites
Ensure you have the following packages installed:
* `pandas`
* `numpy`
* `nltk`
* `sklearn`
* `matplotlib`

### Setup
1. Clone this repository:
```bash
git clone https://github.com/K1n031/Text_Classification_with_Naive_Bayes_Project
cd Text_Classification_with_Naive_Bayes_Project
```
2. Download the dataset:
```bash
!gdown --id 1N7rk-kfnDFIGMeX0ROVTjKh71gcgx-7R
```

## Usage
### 1. Load the Data:
The dataset should be in the CSV format. The notebook reads the data using `pandas`.

### 2. Preprocess the Data:
The notebook includes functions to clean and preprocess the text, including:
* Lowercasing
* Punctuation removal
* Tokenization
* Stopword removal
* Stemming

### 3. Train the Model:
After preprocessing, the data is split into training and test sets. A machine learning model, such as Naive Bayes, is trained on the training set.

### 4. Evaluate the Model:
The model is evaluated using metrics like accuracy on the test set.
```bash
jupyter notebook Text_Classification_Project.ipynb
```

## Project Structure
* `Text_Classification_Project.ipynb`: The main notebook containing the code and explanations.
* `data/`: Directory where the dataset is stored.
* `requirements.txt`: List of dependencies needed for the project.

## Methodology
### 1. Data Preprocessing
* `Lowercasing`: Convert all text to lowercase to ensure uniformity.
* `Punctuation` Removal: Remove punctuation marks to focus on meaningful words.
* `Tokenization`: Split text into individual words or tokens.
* `Stopword` Removal: Remove common words that do not contribute significant meaning.
* `Stemming`: Reduce words to their root forms to group similar words together.

### 2. Model Training
* `Naive Bayes`: A simple yet effective model for text classification, trained on the preprocessed data.

### 3. Model Evaluation
* `Accuracy Score`: The accuracy of the model on the test set is used to evaluate its performance.

## Results
The model demonstrates its ability to categorize text into the correct categories with a reasonable degree of accuracy. Specific results and model performance metrics can be found in the notebook.
