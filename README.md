# Project Title

A brief description of your project goes here.  

---

## Table of Contents

- [Environment Setup](#environment-setup)  
- [Dependencies](#dependencies)  
- [Data Categories](#data-categories)  
- [Git LFS Setup](#git-lfs-setup)  
- [Usage](#usage)  

---

## Environment Setup

To create and activate a Python virtual environment for this project:

```bash
# Create a virtual environment and register it with Jupyter
python -m ipykernel install --user --name=myenv --display-name "Python (myenv)"

- Activate your environment as usual (depending on your OS):
# Windows
myenv\Scripts\activate

# macOS / Linux
source myenv/bin/activate

# Dependencies
- All required Python packages are listed in requirements.txt. Install them with:
```bash
pip install -r requirements.txt
```
- To generate requirements.txt after installing packages:
  ```bash
  pip freeze > requirements.txt
  ```
# Git LFS Setup
```shell
# Install Git LFS
git lfs install

# Track all CSV files
git lfs track "*.csv"

# Add changes and commit
git add .
git commit -m "Cleaned notebook and tracked large files with LFS"

# Push to remote repository
git push -u origin main
```  
