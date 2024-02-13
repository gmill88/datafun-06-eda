# datafun-06-eda

## Overview
This project is designed to allow students the opportunity to create their own exploratory data analysis (EDA). Analysis tools like seaborn and jupyterlabs will be utilized in the EDA. 

## Project start
1. Start a new repository and select default README.md
2. Clone the repository to local environment. I Used VS Code to clone the repository. 
3. Open the project and activate the virtual environment
```bash
python3 -m venv .venv
source .venv/bin/activate
```
4. Install dependencies all dependencies into the .venv
```bash
python3 -m pip install pandas pyarrow jupyterlab matplotlib seaborn
```
5. Freeze dependencies into requirements.txt
 ```bash
 python3 -m pip freeze > requirements.txt
  ```
6.  Create a .gitignore using the touch commonad and add .venv, .vscode, and .DS_Store
