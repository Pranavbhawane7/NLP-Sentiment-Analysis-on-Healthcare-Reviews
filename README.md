NLP Sentiment Analysis on Healthcare Reviews


📌 Objective


The goal of this project is to develop a model that can classify sentiments in healthcare reviews. This involves analyzing text data from healthcare reviews and determining whether the sentiment expressed in each review is positive, negative, or neutral.


🛠️ Tasks
Data Preprocessing: Cleaning and preparing text data (tokenization, stopword removal, handling missing values).

Sentiment Analysis Model: Built ML/NLP models to classify reviews into positive, negative, or neutral.

Model Evaluation: Compared performance using metrics like accuracy, precision, recall, and F1-score.

Insights & Visualization: Generated insights from the sentiment analysis results and visualized findings.



⚙️ Models Used


KNN Classifier

Logistic Regression

Random Forest



📊 Insights from the Analysis

Positive Reviews


Experience → 209 mentions

Service → 139 mentions

Healthcare provider → 86 mentions

“Disappointing not” → 50 mentions

“Coming back” → 50 mentions

Negative Reviews


Experience → 186 mentions

Service → 131 mentions

Healthcare provider → 73 mentions

“Highly recommended” → 54 (wrongly classified)

“Not happier” → 48 mentions

“Experience terrible” → 36 mentions

Neutral Reviews


Experience → 87 mentions

“Terrible would” → 20 mentions

“Experience terrible” → 20 mentions

“Mixed feeling” → 20 mentions

“Bad experience” → 15 mentions

📝 Final Thoughts


The dataset has only 9 statements in the Review Text column, segmented into all 3 classes (positive, negative, neutral).

Because it’s a toy dataset, the model does not perform well and insights are limited.

Still, some patterns emerge:

Many people are satisfied with the healthcare provider (doctor).

Some are willing to return to the hospital.

A portion of patients had terrible experiences and expressed dissatisfaction.

A few reviews reflect mixed emotions about the healthcare center.

🌟 Key Learnings


Importance of dataset size and quality in NLP projects.

How misclassification can occur when training data is insufficient.

Practical application of text preprocessing and sentiment analysis models.
