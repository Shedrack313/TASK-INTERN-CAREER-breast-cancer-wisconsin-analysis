# Breast Cancer Wisconsin (Diagnostic) Dataset Analysis

## Project Overview
This project involves the analysis of the Breast Cancer Wisconsin (Diagnostic) dataset, which includes features computed from breast mass images. The goal is to classify whether a breast mass is malignant or benign, making it a binary classification problem.

## Dataset
The dataset contains features computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. It includes characteristics of the cell nuclei present in the image. The target variable is 'diagnosis', indicating whether the mass is malignant (M) or benign (B).

## Contents
- `DataExploration.ipynb`: Jupyter notebook for initial data exploration and visualization.
- `DataPreprocessing.ipynb`: Notebook detailing the data cleaning and preprocessing steps.
- `ModelTraining.ipynb`: Notebook for model training including Logistic Regression, SVM, and Random Forest classifiers.
- `ModelEvaluation.ipynb`: Evaluation of models using metrics like accuracy, precision, recall, and F1-score.
- `HyperparameterTuning.ipynb`: Hyperparameter tuning for the models using GridSearchCV.

## Methodology
1. **Data Exploration**: Initial analysis to understand the dataset's structure and features, including checking for missing data and outliers.
2. **Data Preprocessing**: Handling missing values and standardizing features.
3. **Model Building**: Logistic Regression, SVM, and Random Forest classifiers were implemented.
4. **Model Evaluation**: Models were evaluated based on accuracy, precision, recall, and F1-score.
5. **Model Tuning**: Hyperparameter tuning was performed to optimize model performance.

## Results
- The models showed promising results in classifying breast masses as malignant or benign.
- The detailed evaluation and comparison of each model are provided in the respective notebooks.

## Technologies Used
- Python
- Jupyter Notebook
- Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

## How to Run
1. Clone the repository.
2. Install the required libraries: `pip install -r requirements.txt`.
3. Run the Jupyter notebooks in order.

## Author
[UDEH SHEDRACK IFEANYI]

## Acknowledgements
This project was inspired by the need for accurate breast cancer diagnosis and the potential of machine learning in medical imaging.

## License
This project is licensed under the [MIT License](LICENSE.md).
