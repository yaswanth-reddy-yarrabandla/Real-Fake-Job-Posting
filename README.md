Real/Fake Job Posting Prediction
Overview
This project addresses the growing concern of fraudulent job postings on online platforms, which pose significant risks to job seekers, including identity theft and financial fraud. Leveraging machine learning techniques, this solution enhances the detection of fake job listings, making job platforms safer and more reliable.

Key Highlights
Dataset: Analyzed a Kaggle dataset containing 18,000 job descriptions with 800 labeled as fraudulent. The data includes textual and metadata features such as job titles, locations, and requirements.
Techniques: Addressed class imbalance using SMOTE and ADASYN. Employed advanced text preprocessing techniques like TF-IDF vectorization, tokenization, and lemmatization.
Models: Implemented multiple machine learning models:
Random Forest: Balanced precision and recall after applying SMOTE.
LSTM: Captured complex text patterns, achieving high recall for fraudulent cases.
SVM: Delivered the highest accuracy (99%) with balanced performance.
XGBoost: Focused on high recall for fraudulent cases, useful in applications prioritizing fraud detection.
Deployment: Deployed the best-performing SVM model as a Streamlit web application for real-time fraud detection.
Results
Model	Accuracy	Precision (Class 1)	Recall (Class 1)	F1-Score (Class 1)
Random Forest	98.32%	0.88	0.75	0.81
LSTM	97%	0.69	0.87	0.77
SVM	99%	0.97	0.75	0.85
XGBoost	89%	0.30	0.92	0.45
Features
Automated fraud detection system integrating text and metadata analysis.
Real-time predictions via a user-friendly Streamlit interface.
Comprehensive evaluation using metrics like accuracy, precision, recall, and F1-score.
Future Scope
Enhance predictive accuracy with ensemble or hybrid models.
Optimize real-time deployment for large-scale applications.
Adapt the model to evolving trends in fraudulent job postings.
