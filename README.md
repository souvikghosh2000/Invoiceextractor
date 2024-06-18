## Step 1: Initialize Git Repository

First, initialize a git repository in the desired folder on your PC:

```bash
git init
Step 2: Clone the Project
Clone the project repository using the following command:

bash
Copy code
git clone url_of_the_project
Replace url_of_the_project with the actual URL of the project repository.

Step 3: Set Up Python Environment
Using Conda
Create a Python environment using conda. In this example, the environment is named venv:

bash
Copy code
conda create -p venv python==3.10 -y
Activate the environment:

bash
Copy code
conda activate venv/
Step 4: Install Necessary Libraries
Install the required libraries listed in the requirements.txt file:

bash
Copy code
pip install -r requirements.txt
