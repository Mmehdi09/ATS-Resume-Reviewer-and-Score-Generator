# ATS-Resume Reviewer and Score Generator

ATS-Resume Reviewer and Score Generator is a Streamlit-based application that evaluates resumes against Applicant Tracking System (ATS) criteria using text extraction, keyword analysis, and AI-driven scoring. The system parses uploaded resumes (PDF/DOCX), analyzes key content such as skills, formatting, and job alignment, and generates an overall ATS score along with improvement suggestions.

# Key Features

Resume parsing and text extraction from PDF and DOCX formats
AI-powered content evaluation using Google’s Generative AI API
Keyword and pattern matching via regular expressions
Visualization of ATS score components using Plotly Graphs
Export of reviewed reports in both DOCX and PDF formats with professional formatting
Tech Stack & Libraries
Frontend: Streamlit
AI & NLP: google-generativeai
File Handling: PyPDF2, python-docx, reportlab
Data & Visualization: plotly.graph_objects, json, re, io
Environment Management: dotenv, os

# Core Functionality

Extracts structured text from resumes using PyPDF2 and python-docx.
Sends the parsed data to Google’s Generative AI model for evaluation.
Performs regex-based keyword and format validation.
Generates an ATS score and visual feedback via interactive graphs.
Exports the reviewed resume and feedback as formatted PDF/DOCX reports.

Goal

To provide developers and job seekers with a robust, AI-assisted tool for assessing and optimizing resumes to meet ATS standards.
