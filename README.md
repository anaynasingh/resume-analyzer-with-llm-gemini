# resume-analyzer-with-llm-gemini
 
# Resume Analyzer with LLM (Gemini)

This project is a Streamlit application that utilizes Google's Gemini LLM to analyze resumes against job descriptions, providing tailored feedback and improvement suggestions.

## Description

This application automates the process of resume review by:

* **Analyzing Resumes:** Extracting relevant information from uploaded resumes.
* **Comparing with Job Descriptions:** Comparing the resume content against provided job descriptions.
* **Providing Feedback:** Generating personalized feedback, including skill gap analysis, actionable suggestions, and resume formatting tips.
* **Leveraging Gemini LLM:** Using the power of Google's Gemini API to generate intelligent and insightful feedback.

## Features

* **Resume Upload:** Users can upload resume files.
* **Job Description Input:** Users can input job descriptions.
* **Automated Analysis:** The application automatically analyzes the resume and job description.
* **Detailed Report:** Generates a comprehensive report with feedback and suggestions.
* **Skill Gap Analysis:** Highlights areas where the resume falls short of the job requirements.
* **Actionable Suggestions:** Provides specific recommendations for improving the resume.
* **Resume Formatting Tips:** Offers guidance on optimizing resume formatting.

## Technologies Used

* **Streamlit:** For building the web application interface.
* **Langchain:** For managing LLM interactions.
* **Google Gemini API:** For generating intelligent feedback.
* **PDF Processing Libraries (pypdf, pdf2image):** For extracting text from PDF resumes.
* **Python:** For the application's backend logic.

## Setup

1.  **Clone the Repository:**

    ```bash
    git clone [https://github.com/anaynasingh/resume-analyzer-with-llm-gemini.git](https://www.google.com/search?q=https://github.com/anaynasingh/resume-analyzer-with-llm-gemini.git)
    cd resume-analyzer-with-llm-gemini
    ```

2.  **Create a Virtual Environment (Recommended):**

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Linux/macOS
    venv\Scripts\activate      # On Windows
    ```

3.  **Install Dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

4.  **Set Up Streamlit Secrets:**

    * Create a `.streamlit/secrets.toml` file (if you are running locally) or add secrets directly to your Streamlit Cloud app settings.
    * Add your Google Gemini API key:

        ```toml
        GEMINI_API_KEY = "YOUR_GEMINI_API_KEY"
        GOOGLE_API_KEY = "YOUR_GOOGLE_API_KEY" # if needed
        ```

5.  **Run the Application:**

    ```bash
    streamlit run streamlit/resume_suggestions.py
    ```

## Deployment

This application is designed to be deployed on Streamlit Cloud.

1.  **Create a GitHub Repository:** Push your code to a GitHub repository.
2.  **Create a Streamlit Cloud Account:** If you don't have one, create an account at [streamlit.io/cloud](https://streamlit.io/cloud).
3.  **Connect to Your Repository:** In Streamlit Cloud, connect to your GitHub repository and select the branch containing your application.
4.  **Add Secrets:** Add your `GEMINI_API_KEY` and `GOOGLE_API_KEY` to the Streamlit Cloud app's secrets.
5.  **Deploy:** Deploy your application.

## Contributing

Contributions are welcome! If you find a bug or have an idea for a new feature, please open an issue or submit a pull request.

## License

[MIT License](LICENSE) (Replace with your actual license if you have one)
