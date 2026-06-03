Resume Screening & Candidate Ranking System

Project Overview

This project focuses on automating the resume screening process using Machine Learning and Natural Language Processing (NLP) techniques.

The system analyzes resume data, extracts relevant skills, identifies skill gaps, ranks candidates based on role fit, and evaluates model performance. This helps recruiters streamline the hiring process and make data-driven hiring decisions.

Dataset

The dataset contains resume-related information with the following columns:

- skills
- skills_required
- career_objective
- job_position_name
- matched_score

Objective

To build a machine learning system that:

- Cleans and preprocesses resume data
- Extracts candidate skills
- Matches candidate skills with required skills
- Identifies skill gaps
- Ranks candidates based on skill match scores
- Evaluates model performance using classification metrics

Technologies Used

- Python
- Pandas
- NumPy
- NLTK
- Matplotlib
- Scikit-learn
- TF-IDF Vectorization
- Jupyter Notebook

Project Workflow

1. Data Collection

Loaded the resume screening dataset.

2. Data Preprocessing

- Removed duplicate records
- Handled missing values
- Converted text to lowercase
- Removed stopwords and special characters

3. Resume Text Cleaning & Parsing

- Processed resume content
- Created clean textual representations for analysis

4. Skill Extraction & Matching

- Extracted candidate skills
- Compared candidate skills with required skills
- Identified matched skills

5. Skill Gap Identification

- Detected missing skills required for specific job roles
- Generated skill gap insights

6. Candidate Ranking

- Calculated skill match scores
- Ranked candidates based on role fit

7. Feature Extraction

Used TF-IDF Vectorization to convert resume text into numerical features.

8. Resume Classification

Trained a Random Forest Classifier for resume classification.

9. Model Evaluation

The model performance was evaluated using:

- Accuracy Score
- Classification Report

10. Visualization

Generated:

- Skill Match Score Distribution
- Matched Skills Distribution
- Candidate Ranking Analysis

Key Features

✔ Resume Text Cleaning & Parsing

✔ Skill Extraction & Matching

✔ Skill Gap Identification

✔ Candidate Ranking Based on Role Fit

✔ TF-IDF Feature Extraction

✔ Resume Classification

✔ Model Performance Evaluation

✔ Data Visualization

Results

The machine learning system successfully analyzes resumes, performs skill matching, identifies missing skills, ranks candidates, and evaluates classification performance using machine learning techniques.

Deliverables

- Resume Screening System
- Candidate Ranking Model
- Jupyter Notebook
- Visualizations and Graphs
- Performance Evaluation Report

Repository Structure

FUTURE_ML_03

├── Resume_Screening_System.ipynb

├── resume_data.csv

├── requirements.txt

├── README.md

└── screenshots

    ├── graph1.png

    ├── graph2.png

    └── final_output.png

Future Improvements

- Implement advanced NLP techniques
- Improve skill extraction accuracy
- Develop real-time resume screening
- Deploy the model as a web application
- Enhance candidate recommendation capabilities

Author

K.Divya 

Internship

Future Interns – Machine Learning Internship

Task

Task 03: Resume Screening & Candidate Ranking System
