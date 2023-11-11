# Heart Disease Prediction 🩺

## Overview
This project aims to predict heart disease using the Heart Disease dataset. We employ the scikit-learn framework for feature engineering, data cleaning, and training a Random Forest Classifier.

## Dataset
The dataset used for this project is the Heart Disease dataset.

## Framework
The project is implemented using the scikit-learn machine learning library.

## Project Structure
- `data/`: Folder containing the dataset.
- `notebooks/`: Source code for the project.
  - `heart_disease_clf.ipynb`: Jupyter Notebook for feature engineering.
  - `model.ipynb`: Jupyter Notebook for building and training the Random Forest Classifier.
- `model/`: Contains the saved model after training.

## Feature Engineering
- Utilized scikit-learn for feature engineering.
- Techniques include:
  - Variance Threshold
  - Correlation Analysis
  - Feature importance based on Tree based classifier

## Handling Imbalance
- Addressed dataset imbalance using the SMOTEENN technique.

## Classifier
- Random Forest Classifier is chosen as the classifier for heart disease prediction.

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/heart-disease-prediction.git
   cd heart-disease-prediction
2. Set up a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate
3. Run the Jupyter Notebooks in the notebooks/ directory for feature engineering, data cleaning, and model training.


## Contributions
Contributions are welcome! Feel free to open issues or submit pull requests.

