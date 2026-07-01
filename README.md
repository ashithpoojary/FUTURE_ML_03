# Task 3: Resume / Candidate Screening System

## Overview
This project develops an intelligent machine learning system to
automatically screen, score and rank job candidates based on
their resume content and relevance to a target job role.
Built as part of the Future Interns Machine Learning Internship (2026).

## Dataset
- Source: Resume Dataset (Kaggle)
- Link: https://www.kaggle.com/datasets/snehaanbhawal/resume-dataset
- Size: 2,484 resumes across 24 job categories
- Filtered to: Engineering category (118 resumes)
- Note: Dataset not included due to file size limits.
  Download the CSV from the link above and place it in the project folder.

## Tools & Libraries
- Python 3.14
- Pandas, NumPy
- NLTK (text cleaning, stopword removal)
- spaCy (NLP pipeline setup)
- Scikit-learn (TF-IDF, Cosine Similarity)
- Matplotlib
- Jupyter Notebook

## Key Steps
1. Loaded and explored 2,484 resumes across 24 job categories
2. Filtered to Engineering category (118 candidates)
3. Defined a Data Engineer job description with required skills
4. Cleaned and preprocessed all resume text using NLTK
5. Applied TF-IDF vectorization to convert text to numerical form
6. Calculated cosine similarity between each resume and job description
7. Ranked all 118 candidates by their match score
8. Identified missing skills for each candidate automatically
9. Visualized top 10 ranked candidates in a horizontal bar chart

## Key Insights
- Top candidate scored 14.87% match and requires minimal
  additional training in Java, Cloud and Agile methodologies
- Match scores reflect broad engineering backgrounds versus
  specific role requirements in the job description
- Skill gap analysis enables targeted interview questions
  and focused onboarding plans for selected candidates
- System can be easily adapted to any job role by simply
  updating the job description text

## Business Value
This resume screening system helps recruiters and HR teams:
- Process hundreds of resumes in seconds automatically
- Rank candidates objectively based on skill relevance
- Identify specific skill gaps before interviews
- Reduce time-to-hire significantly
- Make fair and consistent hiring decisions at scale

## How to Run
1. Clone this repository
2. Install dependencies:
   pip install pandas numpy matplotlib scikit-learn nltk spacy jupyter
   python -m spacy download en_core_web_sm
3. Download Resume.csv from Kaggle link above
4. Place Resume.csv in the project folder
5. Open task3.ipynb in Jupyter or VS Code
6. Run all cells in order

## Deliverable
A fully functional resume screening and ranking system with
candidate scoring, skill gap identification, match visualization
and business insights suitable for recruiters, HR managers
and HR-tech startups.
candidate scoring, skill gap identification, match visualization
and business insights suitable for recruiters, HR managers
and HR-tech startups.
