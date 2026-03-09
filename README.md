# ResuMentorFlaskApp
ResuMentor is full-stack web application designed to automate and personalize the job application process. It leverages a cloud-based large language model  to provide users with instant resume analysis and tailored cover letter generation, helping them become more competitive in the job market.
🎯 Key Features
AI Resume Analyzer:

Users can upload their resume in PDF format.
The application provides a comprehensive analysis covering:
Resume Feedback: Constructive criticism on structure, formatting, and content.
Job Matches: AI-powered recommendations for suitable job roles based on the resume's content.
Interview Preparation: A customized list of technical, behavioral, and system design questions tailored to the user's profile.
Includes a minimalist UI for users to select the exact number of interview questions they want to be generated.
AI Cover Letter Builder:

Users can paste a job description and upload their resume.
The AI synthesizes both documents to generate a unique, professional cover letter that highlights the candidate's relevant skills and experience for that specific role.
Dynamic & Responsive Frontend:

A clean, multi-page user interface built with HTML, CSS, and vanilla JavaScript.
Features include dynamic form fields, full-screen modal previews, and asynchronous communication with the backend to display results without reloading the page.
🛠️ Tech Stack
Backend: Python, Flask
AI & Machine Learning: Google Gemini API, LangChain
Frontend: HTML5, CSS3, JavaScript
Key Python Libraries: google-generativeai, pdfplumber, python-docx
Deployment: Render, Gunicorn
🚀 Setup and Installation
Follow these steps to get the project running on your local machine.

Prerequisites
Python (3.10+)
Conda for environment management
A Google Gemini API Key
Installation
Clone the repository:

git clone [https://github.com/Nishantr846/ResuMentorFlaskApp.git](https://github.com/Nishantr846/ResuMentorFlaskApp.git)
cd ResuMentorFlaskApp
Create and activate the Conda environment:

conda create --name rmenv python=3.10
conda activate rmenv
Install the required Python packages:

pip install -r requirements.txt
Set up your Environment Variable:

Create a new file in the root directory named .env.
Add your Google API key to this file:
GOOGLE_API_KEY="YOUR_API_KEY_HERE"
Running the Application
Ensure your Conda environment is activated (conda activate rmenv).
Start the Flask server:
flask run
Open your web browser and navigate to http://127.0.0.1:5000.
