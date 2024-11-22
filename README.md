# Randomized Optimization


 

## About this Project
This is a project that explores randomized optimization using 3 optimization problems on two fitness functions.
The 3 random optimization problems are:
1. Random Hill Climbing
2. Genetic Algorithms
3. Simulated Annealing
Each optimization problem will be applied to the following 2 fitness functions to explore the benefits of each:
1. Flip Flop Generator
2. Four Peaks

The second part of this experiment explores the same 3 optimization problems on the neural network architecture against
backpropagation.

Different hyperparameters are explored for each optimization problem. Each hyperparameter that is explored is explained
in the pdf.

Scikit-learn (python3) is used to evaluate the algorithms.

Overleaf read only project can be found here: "insrt url"

## How to run this project
## 1. Prereqs
- Python3
- pip3
- conda
- jupyter notebook
- mlrose_hiive
- 
## 1. Setting up environment
- The data can be found here so no need to download it externally
- Navigate to the `randomized-optimization` directory using `cd randomized-optimization`
- Clone the mlrose repository into the randomized-optimization folder so it can be used in the notebooks
using the command `git clone git@github.com:gkhayes/mlrose.git`
- `cd mlrose`
- Install it using `pip install .`
- Install conda (refer to https://conda.io/projects/conda/en/latest/user-guide/install/index.html for instructions)
- Set up virtual environment:
```
conda env create -f environment.yml
conda activate randomized_optimization
```

## 2. Downloading data
- The data will already be in the box link in the data folder. 
- There is only one dataset: 'phishing_dataset.csv' for the neural networks sections
- There is no need to navigate to the data folder as the jupyter notebooks will automatically access the necessary datasets

## 3. Directory Structure
- data: holds the datasets
- images: holds 6 directories (1 for each algorithm per dataset) containing images/plots from the perspective notebook
- notebooks: holds the jupyter notebook files
- results: holds .txt files for NN part of experiment


## 3. Running the Notebooks/Algorithms/Experimments
### 3.1 Running the code
- Ensure that you complete the setup in section 1 and 2.
- Verify your conda environment is active. You should see (supervised_learning) at the beginning of your terminal line.
- From the `randomized-optimization` directory launch Jupyter Notebook using the command `jupyter notebook`
- It should automatically open 'http://localhost:8888/tree' in your browser but if not navigate there
- From there navigate to the notebooks folder. This folder contains all several .ipynb files
- Open any notebook by double-clicking on it. (Note the process for running all the algorithms/notebooks is the same here on out)
- For notebooks with 'with-size' at the end i.e. 'flip-flop-with-size' feel free to change the size variable to change the size
- and thus the results. Files ending in 'all-sizes' run a list of size. This is editable up to you
  - To run the code, click 'Run' in the toolbar then in that drop down and select 'Run All Cells'
  - This will run all your cells and may take up to an hour+ depending on the algorithm and machine it's being run on
  - You can view the progress in the output cells (most cells have a %%time to show how long each cell took and so you know when it's done)
  - While it is running there will be an hour glass in Jupyter notebook tab. When it is done it will be a notebook icon
- 
### 3.2 Viewing the results
The notebooks automatically save all text statistics to the results folder and all plots to the images folder, just
navigate to the respective directory to view them. They are also displayed in the notebooks.

## 4. References 
Note some of the code was copied/stolen from some of these files. Most of it is original though
- https://www.kaggle.com/datasets/akashkr/phishing-website-dataset/data
- https://github.com/hiive/mlrose/blob/master/problem_examples.ipynb
- https://github.com/hiive/mlrose/blob/master/nn_examples.ipynb
- https://github.com/hiive/mlrose/blob/master/tutorial_examples.ipynb
- https://github.com/hiive/mlrose

### Notes:
The images are and results are already in the folders but will be regenerated if the notebooks are run again.

## Disclaimer
This code repository and all its contents are the intellectual property of the owner and are protected under applicable copyright laws. Unauthorized copying, distribution, or reproduction of any part of this repository, whether in whole or in part, is strictly prohibited. This includes, but is not limited to, duplicating, sharing, or deriving works without explicit written consent from the owner. By accessing this repository, you agree to respect these terms and refrain from any actions that violate intellectual property rights.
