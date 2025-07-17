# Assignment4-Stats-Scripts
This repository contains a Jupyter notebook that walks through statistical analysis in Python, based on exercises from the SciPy Lecture Notes. The goal is to practice applying common statistical and plotting techniques that will be useful in future data analysis labs.
## Source
Tutorial followed:
https://scipy-lectures.org/packages/statistics/index.html
## Contents

```
Assignment4-Stats-Scripts/
├── notebooks/
│ └── stats_python.ipynb # Notebook with completed exercises and comments
├── environment.yml # Conda environment definition
├── requirements.txt # Pip-based environment definition 
└── README.md # This file


### Create the Conda Environment

```
conda env create -f environment.yml
conda activate stats-env
```

pip:*

```
pip install -r requirements.txt
```

### Launch Jupyter Lab or Notebook

```
jupyter lab
```

Then navigate to and open `notebooks/stats_python.ipynb`.
###**Dependencies**
-numpy
-pandas
-matplotlib
-seaborn
-scipy
-statsmodels
##Dataset 
-'brain_size.csv'
-'iris.csv
-'https://lib.stat.cmu.edu/datasets/CPS_85_Wages'

###Notes
-Each excercise from the Scipy tutorial is placed in its own cell
-Markdown cells are used to describe the stastical analysis done in each section





