# job-salary-prediction
Job Salary Prediction: Hybrid ML &amp; Deep Learning Approach

Overview

This project uses Natural Language Processing (NLP) and Machine Learning techniques to predict job salaries based on job descriptions.
The goal was to explore how textual information — like required skills, job titles, and company details — can be transformed into meaningful numerical features that help estimate salary ranges.

Methods

I started by preprocessing job postings, cleaning and vectorizing the text using techniques like:

Bag of Words (BOW)

TF-IDF (Term Frequency–Inverse Document Frequency)

These representations were then used to train and evaluate regression models.
Later, I extended the project by experimenting with deep learning methods to see if language models could improve predictions.

Technologies Used

Python

Pandas, NumPy, scikit-learn

Matplotlib / Seaborn

NLTK / spaCy

Jupyter Notebook

Results

The models were evaluated using Mean Squared Error (MSE), and I compared the performance of several algorithms to find the best balance between accuracy and interpretability.
