
**RESUME ANALYSER AND SKILL GAP DETECTION**

Resume Analyzer is designed to automate the process of resume evaluation. Users can upload their resumes in PDF or DOCX format, and the system extracts relevant information using Natural Language Processing (NLP). The extracted skills are then compared with predefined job-role requirements to calculate a match score and identify missing skills.


## Features

- User registration and login
- Resume upload (PDF/DOCX)
- Automatic skill extraction using NLP
- Resume and job role matching
- Skill gap identification
- Match score calculation
- Support for multiple job roles

## Tech Stack

**Client:**  HTML5 , CSS3 , Bootstrap , JavaScript

**Server:** Python ,Django

**Database:** SQLite

**Libraries :** SpaCy (Natural Language Processing) ,PyPDF2 (PDF Text Extraction) , python-docx (DOCX File Processing)
## Installation

**Clone the Repository**:

- git clone https://github.com/Rithika-1806/Resume-Analyzer.git
- cd Resume-Analyzer

**Create a Virtual Environment:**
- python -m venv venv

**Activate the Virtual Environment:**

**Windows:**
- venv\Scripts\activate

**Linux/macOS:**
- source venv/bin/activate

**Install Required Packages:**
- pip install -r requirements.txt

**Download SpaCy Model:**
- python -m spacy download en_core_web_sm

**Apply Database Migrations:**
- python manage.py makemigrations
- python manage.py migrate

**Start the Server:**
- python manage.py runserver

**Access the Application:**

- http://127.0.0.1:8000/
    
## Screenshots

![1](https://github.com/user-attachments/assets/9674791d-0174-474d-abd4-e711855295ea) 
![2](https://github.com/user-attachments/assets/f44225a4-d9d0-4741-bedc-f0821757dc67)
![3](https://github.com/user-attachments/assets/6f7de78a-cc3c-4b39-afaa-34b8fc7eb717)
![4](https://github.com/user-attachments/assets/5ea3ccdf-68c9-48e9-b558-98b8f3c46889)
![5](https://github.com/user-attachments/assets/8a1ff4d0-12b8-4cd0-b57e-5e1687052dcd)

## Demo

https://github.com/user-attachments/assets/8cb1c5c9-17cf-42d7-a414-fe0462904bf4

