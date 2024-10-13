Data Science Project
A Sample Data Science Project for understanding the structure

Generating requirements.txt
If you are working in a virtual environment and have installed packages using pip, you can easily generate a requirements.txt file that includes all installed packages with their versions. Here’s how to do it:

Create venv python -m venv venv
Activate your virtual environment: If you are using a virtual environment (recommended), activate it first. For example:
# On Windows
.\venv\Scripts\activate

# On macOS/Linux
source venv/bin/activate
Generate the requirements.txt file: Use the following command:
pip freeze > requirements.txt
