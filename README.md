# Resume-Parsing-ML-Model

Resume Parsing and Job Matching using Natural Language Processing

**Objective:**
This project implements an end-to-end NLP pipeline that extracts structured information from resumes and intelligently matches candidates to job descriptions. It aims to automate and enhance recruitment processes by enabling efficient resume screening and relevant job recommendations.

**Problem Statement:**

Manual resume screening is time-consuming and error-prone. Recruiters often deal with hundreds of resumes, which makes identifying the best-fit candidates for a job a challenging task. The goal of this project is to:

Extract important details from resumes like name, experience, education, and skills.

Compare candidate profiles against job descriptions.

Rank job matches based on skill and experience relevance.

**Technologies Used:**

Category	Tools/Libraries
Programming Language	Python 3.x
NLP	spaCy, nltk, re
Data Processing	pandas, numpy
Vectorization	scikit-learn (TF-IDF)
Similarity Scoring	Cosine Similarity
Environment	Jupyter Notebook

**Key Features:**

Resume parsing and data cleaning using regular expressions and NLP.

Named Entity Recognition (NER) to extract candidate information.

TF-IDF vectorization for both resumes and job descriptions.

Cosine Similarity for matching and ranking.

Top-N job recommendations based on candidate skill alignment.
