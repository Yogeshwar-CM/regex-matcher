# Regex Matcher Web App

This project is a simple Regex Matcher web application developed for personal practice. The application is built using Flask, a lightweight Python web framework. It allows users to input a test string and a regular expression (regex) and displays the matching results. Additionally, there's a basic feature to validate email addresses using a predefined regex pattern.

## Usage

1. **Regex Matcher:**
   - Enter a test string and a regex pattern in the provided form.
   - Click the "Match" button to see the matching results.

2. **Email Validation:**
   - Navigate to the "Validate Email" section.
   - Enter an email address in the provided form.
   - Click the "Validate" button to see if the email is valid or not.

## Setup and Run

1. **Clone the repository:**

    ```bash
    git clone <repository_url>
    cd regex_matcher
    ```

2. **Set up a virtual environment:**

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. **Install dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

4. **Run the Flask application:**

    ```bash
    python app.py
    ```

5. **Open your web browser and go to [http://localhost:5000](http://localhost:5000).**

