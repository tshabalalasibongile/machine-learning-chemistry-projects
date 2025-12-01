# Wine Classification

## Overview
This project applies machine learning techniques to classify wines into their respective classes based on their chemical properties. The dataset contains 178 samples, each belonging to one of three wine classes.

## Tools & Libraries
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn (Decision Tree, Random Forest, KNN, SVM)

## Project Tasks
1. **Data Exploration**
   - Checked dataset structure and summary statistics.
   - Visualized distributions with histograms, pairplots, and correlation heatmaps.

2. **Data Preprocessing**
   - Checked for missing values.
   - Scaled features using StandardScaler.
   - Split dataset into training and test sets (70-30 split).

3. **Model Training**
   - Trained Decision Tree, Random Forest, K-Nearest Neighbors, and SVM classifiers.

4. **Model Evaluation**
   - Evaluated models using accuracy, classification report, confusion matrices, and ROC curves.
   - Random Forest achieved highest accuracy and most robust performance.

5. **Feature Importance**
   - Identified key chemical properties (Flavanoids, Proline, Color Intensity, Alcohol) driving classification decisions.

## Key Learnings
- Ensemble methods like Random Forest outperform simpler models on small datasets.
- Feature scaling is essential for algorithms sensitive to magnitude.
- Visualizing relationships between features helps identify important predictors.

## How to Run
1. Clone this repository.
2. Install dependencies: `pip install -r requirements.txt`
3. Open the notebook `wine_classification.ipynb` in Jupyter or Google Colab.

