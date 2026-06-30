# NLP Sentiment Analysis Model

## Project Overview

This project focuses on building a Natural Language Processing (NLP) model to classify movie reviews as positive or negative based on their text content. The goal was to transform unstructured text data into machine learning-ready features and train a classification model capable of identifying sentiment patterns.

The project includes text preprocessing, lemmatization, TF-IDF vectorization, model training, evaluation, and performance analysis.

## Business Context

Sentiment analysis is widely used in customer experience, product analytics, marketing, and support operations. By automatically classifying text sentiment, companies can better understand customer opinions, identify pain points, monitor satisfaction, and generate actionable insights from large volumes of text data.

This project simulates a real-world use case where unstructured customer feedback needs to be analyzed efficiently and converted into useful business information.

## Objectives

* Clean and preprocess unstructured text data.
* Apply NLP techniques to transform text into numerical features.
* Train a machine learning model for sentiment classification.
* Evaluate model performance using classification metrics.
* Identify strengths, limitations, and possible improvements of the NLP workflow.

## Dataset

The dataset contains movie reviews labeled by sentiment.

Main fields:

* `review`: Text content of the movie review.
* `pos`: Sentiment label, where positive and negative reviews are represented numerically.

The dataset was used to train and evaluate a supervised machine learning classification model.

## Technologies Used

Python | Pandas | NumPy | Scikit-learn | spaCy | TF-IDF | Logistic Regression | NLP | Sentiment Analysis | Jupyter Notebook

## Project Workflow

### 1. Data Loading and Exploration

The dataset was loaded and explored to understand its structure, target distribution, missing values, and text characteristics.

Key steps included:

* Checking dataset dimensions.
* Reviewing sample text records.
* Validating sentiment label distribution.
* Identifying missing or inconsistent values.

### 2. Text Preprocessing

Text preprocessing was performed to prepare the reviews for modeling.

Main preprocessing steps:

* Lowercasing text.
* Removing unnecessary characters.
* Tokenization.
* Lemmatization using spaCy.
* Cleaning text before vectorization.

The goal was to reduce noise and standardize the text while preserving meaningful information for sentiment classification.

### 3. Feature Extraction

The cleaned text was transformed into numerical features using TF-IDF vectorization.

TF-IDF helps represent the importance of words across the corpus by considering both term frequency and inverse document frequency.

This allowed the machine learning model to work with text data in a structured numerical format.

### 4. Model Training

A Logistic Regression model was trained for binary sentiment classification.

Logistic Regression was selected because it is efficient, interpretable, and commonly used as a strong baseline for text classification problems.

### 5. Model Evaluation

The model was evaluated using classification metrics such as:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

These metrics helped assess how well the model identified positive and negative sentiment.

## Key Responsibilities

* Cleaned and preprocessed unstructured text data for sentiment classification.
* Applied spaCy-based lemmatization to standardize text inputs.
* Used TF-IDF vectorization to transform text into machine learning-ready features.
* Trained and evaluated a Logistic Regression classification model.
* Analyzed model performance using classification metrics and error review.

## Results

The final model demonstrated the ability to classify movie reviews based on sentiment using a structured NLP pipeline.

Main outcomes:

* Built an end-to-end NLP workflow for text classification.
* Converted unstructured text into predictive features using TF-IDF.
* Applied sentiment analysis techniques relevant to customer feedback and conversation intelligence.
* Demonstrated practical use of machine learning for text-based business insights.
* Created a reproducible workflow for future NLP improvements.

## Business Impact

This project shows how NLP can be used to transform large volumes of text into actionable insights. A similar approach can be applied to:

* Customer reviews
* Support tickets
* Survey responses
* Chat transcripts
* Social media comments
* Contact center conversations

By automating sentiment classification, organizations can reduce manual review time, monitor customer satisfaction, and identify areas for improvement.

## Challenges

Some challenges encountered during the project included:

* Processing a large volume of text data efficiently.
* Managing NLP preprocessing runtime.
* Preserving meaningful context while cleaning text.
* Balancing model simplicity, interpretability, and performance.

## Future Improvements

Potential improvements include:

* Testing additional models such as Naive Bayes, Random Forest, XGBoost, or neural networks.
* Comparing TF-IDF with word embeddings.
* Applying hyperparameter tuning.
* Improving preprocessing performance using batch processing.
* Building a Streamlit app for interactive sentiment prediction.
* Adding model explainability to identify influential words.
* Deploying the model as an API for real-time predictions.

## How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/your-username/nlp-sentiment-analysis.git
cd nlp-sentiment-analysis
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

### 3. Activate the virtual environment

On Windows:

```bash
venv\Scripts\activate
```

On macOS/Linux:

```bash
source venv/bin/activate
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

### 5. Install spaCy language model

```bash
python -m spacy download en_core_web_sm
```

### 6. Run the notebook

```bash
jupyter notebook
```

Then open the project notebook and run the cells.

## Suggested Repository Structure

```text
nlp-sentiment-analysis/
│
├── data/
│   └── imdb_reviews.tsv
│
├── notebooks/
│   └── sentiment_analysis.ipynb
│
├── src/
│   └── preprocessing.py
│
├── requirements.txt
├── README.md
└── .gitignore
```

## Skills Demonstrated

* Natural Language Processing
* Sentiment Analysis
* Text Preprocessing
* Lemmatization
* TF-IDF Vectorization
* Supervised Machine Learning
* Classification
* Model Evaluation
* Data Cleaning
* Python Programming
* Reproducible ML Workflows

## Author

**Francisco Rodriguez**
Data Scientist | Machine Learning | NLP | Data Analytics

* LinkedIn: https://www.linkedin.com/in/franciscorodriguez-datascientist/
* GitHub: https://github.com/jfrf98
