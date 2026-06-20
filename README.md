# How to Set Up a Python Virtual Environment using venv

When you build different software projects, they often need different versions of external libraries. If you install everything globally, things will break. A virtual environment is like a private, isolated sandbox for a single project so your files never conflict.

## Prerequisites
Before running these commands, ensure you have:
* Python 3.3 or higher installed on your computer.
* A terminal window open (Command Prompt on Windows, Terminal on Mac/Linux).

## Step-by-Step Instructions

### 1. Create a dedicated project directory
Navigate to your desired folder location and create a new directory for your project files using the command line:
bash
mkdir my-python-project
cd my-python-project

### 2. Initialize the virtual environment
Run Python's built-in `venv` module. This creates a hidden configuration folder named `env` inside your project directory.
bash
python -m venv env
### 3. Activate the environment
You must turn the environment "on" before installing any project packages. 
* **On Windows:** `.\env\Scripts\activate`
* **On macOS/Linux:** `source env/bin/activate`

*Expected Outcome:* You will see `(env)` appear at the very beginning of your terminal command line.

### 4. Deactivate the environment
When you are finished working on your project, type the following command to exit the virtual sandbox:bash
deactivate
*Expected Outcome:* The `(env)` prefix will disappear from your terminal command line.
Click the green Commit changes... button in the top right. A tiny window will pop up—just click Commit changes again to confirm.

