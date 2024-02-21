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
```bash
pip install jupyterlab pandas pyarrow matplotlib seaborn scipy stats scikit-learn

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
import matplotlib
from matplotlib import pyplot as plt
import numpy as np
import pandas as pd
from scipy import stats
import seaborn as sns
import sklearn
from sklearn import metrics
from sklearn.linear_model import ElasticNet, Lasso, Ridge
from sklearn.linear_model import LinearRegression
from sklearn.model_selection import KFold, cross_val_score
from sklearn.model_selection import train_test_split
```
## Project Outline

Part 1 - Chart a Straight line
- Follow the instructions from 10.16
- Use pandas DataFrames to plot Celsius vs Fahrenheit 
Part 2 - Predict Avg high Temp in NYC in January (Object Oriented Programming)
- Section 1: Data Acquisition
- Section 2: Data Inspection
- Section 3: Data Cleaning
- Section 4: Descriptive Statistics
- Section 5: Build the Model
- Section 6: Predict
- Section 7: Visualizations
Part 3 - Predict Avg High Temp in NYC in January (Supervised Machine Learning)
- Section 1: Build the Model
- Section 2: Test the Model
- Section 3: Predict
- Section 4: Visualizations
Part 4 - Add Insights
- OOP method 
- SML method
- Conclusion
Part 5 - Bonus: Multiple Linear Regression with California Housing Dataset
- Section 1: Loading the Data
- Section 2: Exploring Data with Pandas
- Section 3: Visualizing the Features
- Section 4: Splitting the Data for Training and Testing
- Section 5: Training the Model
- Section 6: Testing the Model
- Section 7: Visualizing the Expected vs. Predicted Prices
- Section 8: Regression Model Metrics
- Section 9: Choosing the Best Model

## Contributing
We welcome contributions to this project. If you have suggestions to improve the project or encounter issues, please open an issue or submit a pull request.

## References & Acknowledgments
Much of the exercise example text and information is from the guided projects in 10.16 and 15.4 of the textbook: <a href=https://amzn.to/2KfCptN>_Intro to Python for Computer Science and Data Science: Learning to Program with AI, Big Data and the Cloud_.</a>.   

Special thanks to OpenAI for assistance with troubleshooting and script debugging as well as design. 

Additional references used for this project include:

- [JUPYTER.md](https://github.com/denisecase/datafun-04-spec/JUPYTER.md)
- [MARKDOWN.md](https://github.com/denisecase/datafun-04-spec/MARKDOWN.md)
- [Linear Regression in Python using Jupyter Notebooks!](https://www.youtube.com/watch?v=hitCh7-ZItQ)
- [Plotting graph For IRIS Dataset Using Seaborn And Matplotlib](https://www.tutorialspoint.com/plotting-graph-for-iris-dataset-using-seaborn-and-matplotlib)
- [Seaborn Tutorial](https://seaborn.pydata.org/tutorial.html)

