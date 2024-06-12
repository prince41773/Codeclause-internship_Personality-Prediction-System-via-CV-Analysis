# Resume Analysis and Personality Prediction System

This project analyzes resumes to extract and process relevant information such as names, contact details, education, work experience, and skills. It supports both PDF and DOCX formats, preprocesses the text, and uses TF-IDF for feature extraction. The processed data is saved to a CSV file for further analysis and usage. By employing sentiment analysis, linguistic pattern recognition, and personality trait models, the system will predict personality characteristics like extroversion, conscientiousness, openness, agreeableness, and neuroticism.

## Features

- Extracts text from PDF and DOCX resumes.
- Preprocesses text by removing punctuation, tokenizing, removing stop words, and lemmatizing.
- Extracts specific details such as name, contact information, education, work experience, and skills.
- Uses TF-IDF for feature extraction.
- Saves the structured data to a CSV file.

## Requirements

- Python 3.x
- Libraries: 
  - os
  - PyPDF2
  - textract
  - spacy
  - re
  - docx
  - string
  - nltk
  - scikit-learn

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/resume-analysis.git
   cd resume-analysis

2. Install the required Python libraries:

   ```sh
   pip install -r requirements.txt

3. Download the necessary NLTK data:
   ```sh
   import nltk
   nltk.download('punkt')
   nltk.download('stopwords')
   nltk.download('wordnet')

## Usage
1. Place the resumes (PDF or DOCX format) you want to analyze in the uploads folder.

2. Run the app.py script:

   ```sh
   python app.py

3. The processed data will be saved to a CSV file named resume_dataset.csv.

##  Project Structure
  
resume-analysis/
├── app.py
├── resume_extraction.py
├── requirements.txt
├── uploads/
│   ├── resume1.pdf
│   ├── resume2.docx
│   └── ...
├── education.txt
├── workExp.txt
├── skills.txt
└── README.md

##  Files Description

-  app.py: Main script to run the resume analysis.
-  resume_extraction.py: Contains all the functions for text extraction, preprocessing, and feature extraction.
-  requirements.txt: List of required Python libraries.
-  uploads/: Directory where resumes are stored.
-  education.txt: List of keywords related to education.
-  workExp.txt: List of keywords related to work experience.
-  skills.txt: List of keywords related to skills.
