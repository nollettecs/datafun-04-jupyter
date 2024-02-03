# datafun-04-jupyter

## Module 4 Repository

### Steps to create project
1. Start a new project in GitHub and clone down into VS Code

# Create Virtual Environment

py -m venv .venv
.venv\Scripts\Activate
py -m pip install -r requirements.txt

# Add folders
1. Add requirements.txt
2. Add .gitignore file

# Import Dependencies

py -m pip install jupyterlab
py -m pip install numpy
py -m pip install pandas
py -m pip install matplotlib 
py -m pip install seaborn
py -m pip install scipy

# Freeze Dependencies

py -m pip freeze > requirements.txt

# Push to GitHub

git add .
git commit -m "add .gitignore, cmds to readme"
git push origin main
