# ATS Resume Reviewer and Score Generator

## Problem Statement

In today's competitive job market, many qualified candidates fail to secure interviews because their resumes are not optimized for Applicant Tracking Systems (ATS). Modern recruitment platforms automatically filter resumes based on formatting, keyword relevance, skill matching, and content quality before they ever reach a recruiter. As a result, job seekers often struggle to identify weaknesses in their resumes and understand how ATS systems evaluate their applications.

## Solution

ATS Resume Reviewer and Score Generator is an AI-powered web application designed to help job seekers optimize their resumes for ATS compatibility. The system automatically extracts and analyzes resume content from PDF and DOCX files, evaluates the document against ATS best practices, and generates a comprehensive ATS score along with actionable improvement recommendations.

By combining artificial intelligence, keyword analysis, and automated document processing, the application provides users with detailed feedback on resume quality, skill relevance, formatting effectiveness, and overall job-market readiness.

## Key Features

* Automated resume parsing from PDF and DOCX formats.
* AI-powered resume evaluation using Google's Generative AI.
* ATS compatibility scoring based on industry-standard criteria.
* Keyword and skill analysis using pattern matching and regular expressions.
* Identification of missing skills, formatting issues, and optimization opportunities.
* Interactive ATS score visualization through dynamic Plotly charts.
* Generation of personalized improvement recommendations.
* Export of review reports in professional PDF and DOCX formats.
* User-friendly web interface built with Streamlit.

## System Workflow

1. User uploads a resume in PDF or DOCX format.
2. Resume content is extracted and converted into structured text.
3. Keywords, skills, and formatting patterns are analyzed.
4. Google Generative AI evaluates resume quality and ATS compatibility.
5. ATS score and detailed feedback are generated.
6. Interactive visualizations present score breakdowns.
7. Users can export the complete analysis report in PDF or DOCX format.

## Technology Stack

### Frontend

* Streamlit

### Artificial Intelligence & NLP

* Google Generative AI (Gemini)

### File Processing

* PyPDF2
* python-docx
* ReportLab

### Data Analysis & Visualization

* Plotly
* Regular Expressions (re)
* JSON Processing

### Environment & Configuration

* Python
* dotenv
* os
  
# System Workflow
<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/4d652277-4076-4c6b-94b2-40dec583218a" />

## Project Impact

This project demonstrates the practical integration of Artificial Intelligence, Natural Language Processing, and document analysis to solve a real-world recruitment challenge. By providing ATS-focused insights and automated resume optimization recommendations, the system empowers job seekers to improve their resume effectiveness, increase ATS compatibility, and enhance their chances of securing interview opportunities.
