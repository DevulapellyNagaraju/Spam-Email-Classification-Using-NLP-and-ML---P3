# SpamGuard Application 🤖

SpamGuardApp is a powerful email classification tool that leverages NLP and ML to protect your inbox from spam. With an intuitive interface built on Streamlit, it accurately identifies and filters spam, ensuring a secure and clutter-free email experience.


## Features

- **Email Classification**: Enter an email and classify it as either Spam or Not Spam.
- **Model Performance**: View accuracy, confusion matrix, and classification report on the dataset.
- **User-Friendly Interface**: The result is displayed with a colored background to clearly indicate whether an email is Spam (red) or Not Spam (green).

## Installation

<h1>To clone a GitHub repository and use it with Streamlit, follow these steps: </h1>

### Prerequisites
1. **Install Git**: Download and install Git if it's not already installed. [Download Git](https://git-scm.com/).
2. **Install Python**: Ensure Python is installed on your machine. [Download Python](https://www.python.org/).
3. **Install Streamlit**: Install Streamlit using pip:
   ```bash
   pip install streamlit
   ```

---

### Steps to Clone and Run a Streamlit App from GitHub
1. **Clone the Repository**
   - Open your terminal or command prompt.
   - Navigate to the folder where you want to clone the repository.
   - Run the following command:
     ```bash
     git clone <repository_url>
     ```
     Replace `<repository_url>` with the URL of the GitHub repository.

2. **Navigate to the Project Directory**
   - After cloning, navigate to the repository folder:
     ```bash
     cd <repository_folder_name>
     ```

3. **Create a Virtual Environment (Optional but Recommended)**
   - Create a virtual environment:
     ```bash
     python -m venv venv
     ```
   - Activate the virtual environment:
     - **Windows**:
       ```bash
       venv\Scripts\activate
       ```
     - **macOS/Linux**:
       ```bash
       source venv/bin/activate
       ```

4. **Install Dependencies**
   - Check if a `requirements.txt` file exists in the repository.
   - If it does, install the dependencies:
     ```bash
     pip install -r requirements.txt
     ```

5. **Run the Streamlit App**
   - Look for a `.py` file that is the main entry point of the Streamlit app (often named `app.py` or `main.py`).
   - Run the app using Streamlit:
     ```bash
     streamlit run <script_name>.py
     ```
     Replace `<script_name>` with the name of the file.

6. **Access the App**
   - Once the app starts, Streamlit will provide a local URL (e.g., `http://localhost:8501`) in the terminal.
   - Open this URL in your web browser to access the app.

---

