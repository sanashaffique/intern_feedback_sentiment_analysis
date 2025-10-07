Project Overview

This project evaluates internship feedback to understand interns’ satisfaction and identify areas for improvement. Using sentiment analysis, feedback is classified as positive, neutral, or negative, and department-wise trends are visualized.

Dataset
File: synthetic_intern_feedback.csv
The dataset contains 100 rows and the following columns:
FeedbackID: Unique identifier for each feedback entry
Date: Date of feedback submission
Source: Platform or source of feedback (e.g., survey, email)
Department: Intern’s department
FeedbackText: Text content of the feedback
TrueSentiment: Original sentiment label (positive, neutral, negative)

Note: The dataset is clean, with no missing values, ready for analysis.

Python Script
File: sentiment_analysis.py

This script performs:
Data Cleaning & Preprocessing
Converts date column to datetime
Standardizes text (lowercase, trim spaces)
Sentiment Classification
Applies VADER sentiment scoring
Classifies feedback as positive, neutral, negative

Visualization
Histogram of feedback sentiment distribution
Department-wise stacked bar chart of feedback

Insights

Majority of feedback is positive

Neutral and negative feedback is smaller but varies by department
Department-wise distribution highlights areas for improvement

Mentor / Guidance
Project completed under the guidance of a mentor to understand data cleaning, sentiment analysis, and visualization workflow.

Usage
Clone the repository:
git clone <https://github.com/sanashaffique/intern_feedback_sentiment_analysis>
Open sentiment_analysis.py or sentiment_analysis.ipynb in Python.

Run the script to see sentiment classification and visualizations.
