# Smart Resume Analyser

**Note:** This is a template README file. Please update the sections below with the specific details of your project.

## Description

The Smart Resume Analyser is a tool designed to streamline the process of resume screening and analysis. It leverages Natural Language Processing (NLP) to parse and understand resumes, extracting key information and providing insightful analytics. This helps recruiters and hiring managers to quickly identify the most suitable candidates for a given job description.

This tool can also be used by job seekers to improve their resumes by providing feedback on keywords, skills, and overall structure, thereby increasing their chances of passing through Applicant Tracking Systems (ATS).

## Features

- **Resume Parsing:** Extracts key information from resumes, such as contact information, work experience, education, skills, and projects.
- **Keyword Extraction:** Identifies and extracts relevant keywords and skills from the resume.
- **ATS Compatibility Score:** Scores the resume based on its compatibility with common Applicant Tracking Systems.
- **Job Description Matching:** Compares the resume with a given job description and provides a match score, highlighting missing keywords and skills.
- **Skill Analysis:** Identifies the candidate's skills and categorizes them.
- **Candidate Ranking:** Ranks candidates based on their resume's relevance to the job description.
- **Web-Based Interface:** A user-friendly web interface for uploading resumes and viewing the analysis.

## Technologies Used

- **Backend:** Python
- **Web Framework:** Flask / Django / Streamlit (Please choose the one you used)
- **NLP Libraries:**
  - NLTK (Natural Language Toolkit)
  - spaCy
  - PyResparser
- **Machine Learning Libraries:**
  - Scikit-learn
- **PDF Text Extraction:**
  - PyMuPDF (fitz)
  - PDFMiner
- **Frontend:** HTML, CSS, JavaScript (If you have a custom front-end)
- **Database:** SQLite / PostgreSQL / MySQL (If you are storing data)

## Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/Dxtro22/Smart-Resume-Analyser.git](https://github.com/Dxtro22/Smart-Resume-Analyser.git)
    cd Smart-Resume-Analyser
    ```

2.  **Create a virtual environment:**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3.  **Install the dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
4.  **Download NLP models (if required):**
    ```bash
    python -m spacy download en_core_web_sm
    python -m nltk.downloader punkt
    ```
5.  **Set up the database (if required):**
    ```bash
    python manage.py migrate
    ```

## Usage

1.  **Run the application:**
    ```bash
    python app.py
    ```
    or if you are using Streamlit:
    ```bash
    streamlit run app.py
    ```

2.  **Open your web browser and navigate to:**
    ```
    [http://127.0.0.1:5000](http://127.0.0.1:5000)
    ```
    or the address provided by Streamlit.

3.  **Upload a resume (in PDF or DOCX format) to see the analysis.**

## Contributing

Contributions are welcome! Please follow these steps:

1.  Fork the repository.
2.  Create a new branch (`git checkout -b feature-branch`).
3.  Make your changes.
4.  Commit your changes (`git commit -m 'Add some feature'`).
5.  Push to the branch (`git push origin feature-branch`).
6.  Open a pull request.

Please make sure to update tests as appropriate.

## License

This project is licensed under the MIT License - see the `LICENSE` file for details.
