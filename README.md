# Fake_Job_Posting_Detection
## 📌 Project Overview

Fraudulent job postings on online platforms mislead job seekers and create serious security risks.
This project focuses on analyzing job posting data and predicting whether a job is Genuine or Fraudulent using machine learning techniques.

By automatically detecting fake job postings, recruitment platforms can improve trust, security, and user experience.

## 🎯 Objectives

Analyze job posting data

Predict whether a job posting is fake or genuine

Understand textual patterns in fraudulent postings

Compare classification models for performance

##💼 Problem Statement

Online job portals sometimes contain misleading or fraudulent job advertisements.
Manual detection is difficult and time-consuming.

This project uses machine learning-based classification models to analyze job posting content and predict whether a job is fake.

##📂 Dataset Description

The dataset contains job posting attributes representing company details, job descriptions, and related information.

📊 Dataset Source:
https://www.kaggle.com/datasets/shivamb/real-or-fake-fake-jobposting-prediction

Columns Used:

title – Job title

location – Job location

department – Department name

salary_range – Salary details

company_profile – Company description

description – Job description

requirements – Job requirements

benefits – Benefits offered

employment_type – Type of employment

required_experience – Experience needed

required_education – Education qualification

fraudulent – Target variable (0 = Genuine, 1 = Fake)

The dataset captures both structured and unstructured textual job information, making it suitable for fraud detection.

##🛠️ Technologies Used

Python

Jupyter Notebook

Pandas

NumPy

Matplotlib

Scikit-learn

TF-IDF Vectorizer

##🔄 System Approach

Data Collection – Job posting dataset

Data Preprocessing – Handling missing values and combining text features

Feature Engineering – Creating a unified text column

Text Vectorization – Applying TF-IDF

Model Training – Applying classification models

Evaluation – Comparing actual and predicted results

Result Interpretation – Identifying best-performing model

##🤖 Machine Learning Models Used

Logistic Regression (Baseline Model)

##📊 Evaluation Metrics

As this is a classification problem, the following metrics were used:

Accuracy

Precision

Recall

F1-Score

Confusion Matrix

##📈 Visualizations

Distribution of genuine vs fraudulent jobs

Confusion Matrix

Model performance comparison

##🧪 Example Predictions
❌ Fake Job Example
predict_job(
    "Data Entry Job",
    "Work From Home",
    "NA",
    "50000 weekly",
    "Unknown",
    "No experience needed",
    "Just typing",
    "None",
    "Not required",
    "0 years"
)


Output:

Fake Job (1)

##✅ Genuine Job Example
predict_job(
    "Customer Service - Cloud Video Production",
    "NZ, Auckland",
    "90 Seconds is a global cloud video production service...",
    "",
    "Marketing and Advertising",
    "Client focused, excellent communication skills",
    "Manage video projects and client communication",
    "",
    "Full-time",
    "Not Applicable"
)


Output:

Genuine Job (0)

##🧪 Results

Logistic Regression achieved high classification accuracy

Strong Precision and Recall values indicate reliable fraud detection

Confusion Matrix shows effective separation between fake and genuine jobs

Model successfully identifies patterns such as unrealistic salaries and vague job descriptions

##✅ Conclusion

The project successfully detects fraudulent job postings using machine learning techniques.

The classification model effectively analyzes textual job content and distinguishes between genuine and fake job advertisements.

This solution can help:

Improve security in recruitment platforms

Reduce online job fraud

Increase trust among job seekers

##🔮 Future Scope

Use advanced models like XGBoost or Deep Learning

Deploy as a web application

Integrate with real-time job portals

Improve handling of imbalanced datasets

##Author: Remya C
