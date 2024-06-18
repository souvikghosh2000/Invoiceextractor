### Step 1: Initialize Git
Navigate to the directory where you want to keep the project and initialize git.

git init

### Step 2: Clone Repository
Clone the project repository using the provided URL.

git clone <url_of_the_project>

### Step 3: Open VS code
Open the cloned project directory in Visual Studio Code.

### Step 4:  Create and Activate Python Environment:
Create and activate a Python environment using conda. Replace venv with your preferred environment name.

conda create -p venv python==3.10 -y
conda activate venv/

### Step 5:  Install Required Libraries
Install the necessary libraries from the requirements file.

pip install -r requirements.txt

### Step 6: Run the Project

streamlit run app.py
