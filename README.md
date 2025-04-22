# Medical Data Classification 

## Overview
This Jupyter notebook explores classification algorithms on two medical datasets:

1. **NHANES Age Prediction** (`NHANES age prediction.csv`): Predicts age groups using K-Nearest Neighbors and a custom Decision Tree implementation.
2. **Breast Cancer Wisconsin**: Classifies tumor malignancy using K-Nearest Neighbors and a custom Decision Tree.

Key components:
- Data preprocessing and train-test splitting
- Custom implementations of KNN and Decision Tree classifiers
- Hyperparameter tuning (K selection, tree depth, cost functions)
- Model evaluation using ROC curves and AUC

## Requirements
- Python 3.7 or higher
- pandas
- numpy
- matplotlib
- scikit-learn
- ucimlrepo (`pip install ucimlrepo`)

Install dependencies:
```bash
pip install pandas numpy matplotlib scikit-learn ucimlrepo
```

## Data
- **`NHANES age prediction.csv`** should be placed in the notebook directory.
- **Breast Cancer Wisconsin** data is automatically fetched via `ucimlrepo.fetch_ucirepo`.

## Notebook Structure

1. **NHANES Age Prediction**
   - Data Preprocessing
   - Train/Test Split
   - `KNN` class definition and hyperparameter tuning
   - `DecisionTree` and `Node` class definitions
   - KNN model evaluation and ROC/AUC analysis
   - Decision Tree model evaluation and ROC/AUC analysis

2. **Breast Cancer Wisconsin**
   - Data Preprocessing
   - Train/Test Split
   - KNN model training, hyperparameter tuning, and ROC/AUC
   - Decision Tree training, depth/cost tuning, and ROC/AUC

3. **Combined ROC Curves**
   - Plot and compare ROC curves across models and datasets.

## Usage
1. Ensure `NHANES age prediction.csv` is in the same folder as the notebook.
2. Open `assignment1_group_46.ipynb` in Jupyter Notebook.
3. Run all cells sequentially.
4. Examine printed metrics and saved plots (ROC curves) for model performance insights.

## Authors
Maxx Railton
Dmitrii Vlasov

