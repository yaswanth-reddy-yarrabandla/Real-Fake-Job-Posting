# Real/Fake Job Posting Prediction 🧑‍💼📊

## Overview  
This project addresses the growing concern of fraudulent job postings on online platforms, which pose significant risks to job seekers, including identity theft and financial fraud. Leveraging machine learning techniques, this solution enhances the detection of fake job listings, making job platforms safer and more reliable.

---

## Key Highlights  
- **Dataset**:  
  - Analyzed a [Kaggle dataset](https://www.kaggle.com/) containing **18,000 job descriptions**, with **800 labeled as fraudulent**.  
  - Included textual and metadata features such as job titles, locations, and requirements.

- **Techniques**:  
  - **Class Imbalance Handling**: Addressed imbalance using **SMOTE** and **ADASYN**.  
  - **Text Preprocessing**: Employed advanced techniques like **TF-IDF vectorization**, **tokenization**, and **lemmatization**.  

- **Models**:  
  - **Random Forest**: Balanced precision and recall after applying SMOTE.  
  - **LSTM**: Captured complex text patterns, achieving high recall for fraudulent cases.  
  - **SVM**: Delivered the highest accuracy (**99%**) with balanced performance.  
  - **XGBoost**: Focused on high recall for fraudulent cases, useful in applications prioritizing fraud detection.  

- **Deployment**:  
  - Deployed the best-performing **SVM model** as a **Streamlit web application** for real-time fraud detection.  

---

## Results  

| Model               | Accuracy | Precision (Class 1) | Recall (Class 1) | F1-Score (Class 1) |
|---------------------|----------|----------------------|-------------------|---------------------|
| Random Forest       | 98.32%  | 0.88                 | 0.75              | 0.81                |
| LSTM                | 97%     | 0.69                 | 0.87              | 0.77                |
| SVM                 | 99%     | 0.97                 | 0.75              | 0.85                |
| XGBoost             | 89%     | 0.30                 | 0.92              | 0.45                |

---

## Features  
- **Automated Fraud Detection**: Integrated **text and metadata analysis** for accurate classification.  
- **Real-Time Predictions**: Deployed a user-friendly **Streamlit interface** for real-time fraud detection.  
- **Comprehensive Evaluation**: Used metrics like **accuracy**, **precision**, **recall**, and **F1-score** to assess model performance.  

---

## Future Scope  
- **Enhance Predictive Accuracy**: Experiment with **ensemble** or **hybrid models** for improved performance.  
- **Optimize Real-Time Deployment**: Scale the system for **large-scale applications**.  
- **Adapt to Evolving Trends**: Refine the model to handle **emerging patterns** in fraudulent job postings.  

---

Feel free to explore the repository and contribute to enhancing this solution! 🚀
