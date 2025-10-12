#ATS-Resume Reviewer and Score Generator

ATS-Resume Reviewer and Score Generator is a Streamlit-based web app that analyzes resumes for ATS (Applicant Tracking System) compatibility. It extracts, evaluates, and scores resumes based on structure, keyword usage, and job relevance using Google’s Generative AI.
The app supports PDF and DOCX formats, providing detailed feedback and improvement suggestions. It also visualizes scoring insights using interactive Plotly charts and allows exporting reviewed reports as professionally formatted PDF or DOCX files.

#Key Features
AI-driven resume review using Google Generative AI
Keyword and pattern analysis with regular expressions
ATS score visualization via Plotly
File parsing and text extraction using PyPDF2 and python-docx
Export of reports in PDF/DOCX formats with reportlab styling

#Tech Stack
Frontend: Streamlit
AI/NLP: google-generativeai
File Handling: PyPDF2, python-docx, reportlab
Visualization: plotly.graph_objects
Environment Management: dotenv, os, re, io, json

#Purpose
This project helps users understand how ATS systems interpret resumes and provides actionable insights to improve formatting, keyword alignment, and overall visibility in automated recruitment systems.
