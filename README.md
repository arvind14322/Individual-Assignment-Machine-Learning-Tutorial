# Individual-Assignment-Machine-Learning-Tutorial

## Title
Trade‑off Between Accuracy and Computation in Decision Tree and Random Forest

## Description
Breast cancer classification project using the Breast Cancer Wisconsin (Diagnostic) dataset.  
The repository compares a single `DecisionTreeClassifier` and a `RandomForestClassifier`, focusing on the trade‑off between predictive accuracy and computational cost (training time, prediction time, and model size). Experiments are implemented in Python with scikit‑learn and include evaluation via accuracy, confusion matrices, and visualisations of model performance. [file:12][file:13]

## What’s inside
- Uses the Breast Cancer Wisconsin (Diagnostic) dataset from scikit‑learn.  
- Implements two models: `DecisionTreeClassifier` and `RandomForestClassifier` in Python (scikit‑learn).  
- Measures model accuracy and class‑wise precision/recall/F1, plus confusion matrices.  
- Records training time, prediction time, and model size (bytes) for each model to study the accuracy–computation trade‑off.  
- Provides plots: confusion matrices and a bar chart comparing accuracy and error for Decision Tree vs Random Forest. [file:13]

## Installation / requirements
- Python 3.10+  
- Recommended: create and activate a virtual environment.

Install dependencies:

```bash
pip install numpy pandas scikit-learn matplotlib
```

Optionally, install Jupyter if you want to run the notebook locally:

```bash
pip install notebook
```

## How to run

```bash
git clone <your-repo-url>
cd <your-repo-folder>
```

Install the required packages (see above), then open the main notebook (e.g. `Trade-off_Between_Accuracy_and_Computation_in_Decision_Tree_and_Random_Forest_24127536.ipynb`) in Jupyter:

```bash
jupyter notebook Trade-off_Between_Accuracy_and_Computation_in_Decision_Tree_and_Random_Forest_24127536.ipynb
```

Run all cells to:

- Load the Breast Cancer dataset.  
- Train the Decision Tree and Random Forest models.  
- Compute metrics and timings.  
- Generate confusion matrices and accuracy/error plots. [file:13]

> Note: Because the train/test split uses a fixed random state, results are reproducible across runs. [file:13]

## License
This project is licensed under the MIT License. [page:18]

## Author / acknowledgements
Author: Aravind Nayini – MSc Data Science student, University of Hertfordshire.  
This project uses the Breast Cancer Wisconsin (Diagnostic) dataset and the scikit‑learn implementations of `DecisionTreeClassifier` and `RandomForestClassifier`. Background reading and implementation details were supported by the scikit‑learn documentation and online tutorials on Decision Trees and Random Forests. [file:12]
