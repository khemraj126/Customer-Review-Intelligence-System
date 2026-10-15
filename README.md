# Customer Review Intelligence System

## Overview
The Customer Review Intelligence System uses Natural Language Processing (NLP) and Machine Learning to analyze customer reviews and classify them by sentiment. The project aims to help businesses understand customer feedback, identify potential dissatisfaction, and make data-driven decisions.

## Problem Statement
Businesses receive large volumes of customer reviews. Manually reading every review is time-consuming. This project explores how text preprocessing, machine learning, and data visualization can help summarize customer sentiment efficiently.

## Objectives
- Clean and preprocess raw customer review text.
- Explore customer ratings and sentiment distributions.
- Convert text into numerical features using TF-IDF.
- Train and compare multiple machine learning models.
- Evaluate model performance using classification metrics.
- Identify common words in negative reviews and derive potential business insights.

## Technologies Used
- **Language:** Python
- **Data Analysis:** Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn
- **NLP:** NLTK, text preprocessing, tokenization, stop-word removal, lemmatization
- **Feature Extraction:** TF-IDF
- **Machine Learning:** Scikit-learn, Logistic Regression, Multinomial Naive Bayes, Linear SVM
- **Environment:** Jupyter Notebook

## Project Workflow
1. Load and inspect the review dataset.
2. Clean the text by removing HTML tags, punctuation, and unwanted characters.
3. Tokenize text, remove stop words while preserving negation where appropriate, and lemmatize words.
4. Explore ratings and create sentiment labels.
5. Split the dataset into training and testing sets.
6. Convert reviews into TF-IDF features.
7. Train Logistic Regression, Multinomial Naive Bayes, and Linear SVM.
8. Evaluate predictions using accuracy, precision, recall, F1-score, and confusion matrices.
9. Test the selected model on new customer reviews.
10. Visualize sentiment distributions, ratings, and frequently occurring words in negative reviews.

## Business Applications
- Summarizing customer feedback at scale.
- Monitoring positive and negative sentiment.
- Identifying recurring terms in customer complaints.
- Supporting product and customer-experience improvement decisions.

## Model Evaluation
The models are compared using accuracy, weighted precision, weighted recall, and weighted F1-score. The best-performing model is selected based on the evaluation results.

**Results:** Add your actual model comparison table, best model, and test-set scores here after running the notebook.

## Limitations
- Sentiment labels derived from customer ratings may not always match the sentiment expressed in the review.
- Sarcasm, context, spelling errors, and ambiguous language can affect predictions.
- Frequently occurring words do not necessarily reveal the root cause of customer dissatisfaction.
- Performance depends on dataset quality and representativeness.

## Future Improvements
- Build an interactive dashboard using Streamlit or Tableau.
- Add topic modeling to discover recurring complaint themes.
- Test performance on additional datasets.
- Save and deploy the trained model for interactive predictions.
- Evaluate class-wise performance and investigate misclassified reviews.

## How to Run
1. Clone or download this repository.
2. Install the required Python libraries.
3. Open `customer_review_analysis.ipynb` in Jupyter Notebook.
4. Place the permitted dataset in the expected location and update the file path.
5. Run the notebook cells in order.


