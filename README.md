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

