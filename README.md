# Resume Checking Project

## Overview
This project aims to create an application for checking resumes using natural language processing (NLP) techniques. It utilizes Python, pandas for data manipulation, spaCy for NLP tasks, Flask for creating a web application, and Render for deployment.

## Components

### 1. Data Preparation
- **Input Data**: Resumes in various formats (e.g., PDF, Word) collected for analysis.
- **Processing**: Using pandas to read and preprocess the resumes, extracting relevant information such as text content, education, experience, skills, etc.

### 2. Natural Language Processing
- **Library**: Utilizing spaCy for NLP tasks such as tokenization, named entity recognition (NER), part-of-speech (POS) tagging, etc.
- **Tasks**:
  - Tokenization: Breaking down resumes into individual words or phrases.
  - Named Entity Recognition: Identifying entities like names, organizations, locations, etc.
  - POS Tagging: Assigning parts of speech to words in the resumes.

### 3. Resume Analysis
- **Criteria**: Establishing criteria for evaluating resumes, such as required skills, experience, education, etc.
- **Matching**: Comparing the extracted information from resumes against the predefined criteria.
- **Scoring**: Assigning scores to resumes based on the match with the criteria.

### 4. Flask Application
- **Framework**: Using Flask to create a web application for users to interact with the resume checking system.
- **Endpoints**:
  - Upload Resume: Allows users to upload their resumes for analysis.
  - View Results: Displays the analysis results, including scores and feedback.
  - Download Report: Provides an option to download a detailed report of the analysis.

### 5. Deployment on Render
- **Platform**: Deploying the Flask application on Render for accessibility over the internet.
- **Configuration**: Setting up necessary environment variables, dependencies, and server configurations.
- **Monitoring**: Ensuring the application's availability and performance through monitoring tools provided by Render.

## Usage
1. Users visit the deployed web application.
2. They upload their resumes through the designated interface.
3. The system analyzes the resumes against predefined criteria.
4. Users receive feedback and scores based on the analysis.
5. Users can download detailed reports for further reference.

## Conclusion
This project demonstrates the integration of Python, pandas, spaCy, Flask, and Render for creating a robust resume checking application. By leveraging NLP techniques, it provides efficient and automated analysis of resumes, aiding in the recruitment process.
## Deployment 
https://test-x1t3.onrender.com
