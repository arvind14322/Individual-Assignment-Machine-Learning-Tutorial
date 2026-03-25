# Individual-Assignment-Machine-Learning-Tutorial

TiTle:Trade‑off_Between_Accuracy_and_Computation_in Decision_Tree_and_Random_Forest

description:
Breast cancer classification project using the Breast Cancer Wisconsin (Diagnostic) dataset. The repository compares a single Decision Tree and a Random Forest classifier, focusing on the trade‑off between predictive accuracy and computational cost (training time, prediction time, and model size). Experiments are implemented in Python with scikit‑learn, and include evaluation via accuracy, confusion matrices, and visualisations of model performance

What’s inside:
Uses the Breast Cancer Wisconsin (Diagnostic) dataset from scikit‑learn.
Implements two models: DecisionTreeClassifier and RandomForestClassifier in Python (scikit‑learn).
Measures model accuracy, AUC, and class-wise precision/recall/F1, plus confusion matrices.
Records training time, prediction time, and model size (bytes) for each model to study the accuracy–computation trade‑off.
Provides plots: confusion matrices and a bar chart comparing accuracy and error for Decision Tree vs Random Forest.

Installation / requirements:
Python 3.10+

Recommended: create and activate a virtual environment.

Install dependencies:
```
pip install numpy pandas scikit-learn matplotlib
```

Optionally, install Jupyter if you want to run the notebooks locally:
```
pip install notebook
```

How to run:
Clone the repository:
```bash
git clone <your-repo-url>
cd <your-repo-folder>
```

Install the required packages (see above).

Open the main notebook (e.g. ml2-1.ipynb) in Jupyter:
```
jupyter notebook ml2-1.ipynb
```
Run all cells to:
load the Breast Cancer dataset,
train the Decision Tree and Random Forest models,
compute metrics and timings,
generate confusion matrices and accuracy/error plots.

License:
This project is licensed under the MIT License.

Author / acknowledgements :
Author: Aravind Nayini – MSc Data Science student, University of Hertfordshire.
This project uses the Breast Cancer Wisconsin (Diagnostic) dataset and the scikit‑learn implementations of DecisionTreeClassifier and RandomForestClassifier.
Background reading and implementation details were supported by the scikit‑learn documentation and online tutorials on Decision Trees and Random Forests.
