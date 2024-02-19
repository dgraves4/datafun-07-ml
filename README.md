# datafun-07-ml
This project is a guided learning exercise that serves to showcase the use of machine learning, and in particular, a simple type of supervised machine learning called simple linear regression to build a model, make predictions, visualize the model, and publish insights about the final product. 

## Project Setup and Layout
Project setup consists of beginning a git repository with a README.md, cloning the project down to the root project folder, adding necesssary files and depenency installs, and performing initial commits to Github. 

### Project Structure & Deliverables
- `README.md`: Provides an overview of the project and instructions for setting up the environment and running the notebook.
- `requirements.txt`: Lists all dependencies needed to run the notebook.
- `dgraves_ml.ipynb`: Jupyter notebook.

### Environment Setup 
- Create a new github repository 'yourname_ml.ipynb'.
- Include a README.md file.

#### Clone project down and open project folder in VS Code
```bash
git clone https://github.com/dgraves4/datafun-07-ml
cd "C:\Users\derek\OneDrive\Documents\44608 Data Analytics Fundamentals\Mod 7\datafun-07-ml"
code .
```

#### Create and activate virtual environment
```bash
python -m venv .venv
source .venv/scripts/activate #windows
```

#### Create and add .gitignore file to root project folder
- Create a .gitignore file in project directory "C:\Users\derek\OneDrive\Documents\44608 Data Analytics Fundamentals\Mod 7\datafun-07-ml\.gitignore"
- Add .vscode/ and .venv/ to .gitignore file.

#### Install dependencies and freeze to requirements.txt
Dependencies for this project:
- Jupyterlab 
- pandas 
- pyarrow
- matplotlib 
- seaborn
- scipy
- stats
```bash
pip install jupyterlab pandas pyarrow matplotlib seaborn scipy stats sklearn numpy
pip freeze > requirements.txt
```
#### Initial and Subsequent Commits to Github for version control

```bash
git add .
git commit -m "Initial commit"
git push origin main
```
## Project Start
- Create the Notebook: In the VS Code Explorer, create a new file i.e., yourname_eda.ipynb. Ensure it has a .ipynb extension.
- Verify your new notebook is open for editing. If needed, view the project files in VS Code Explorer and double-click the notebook file to open it for editing.
- Add a Markdown cell at the top of your notebook with the introduction (include the title, author, date and the purpose of the project).

### Import Dependencies
- Install dependencies in .ipynb file at the top of the file and after markdown introduction.

```bash
import matplotlib.pyplot as plt
import pandas as pd
import seaborn as sns
```


