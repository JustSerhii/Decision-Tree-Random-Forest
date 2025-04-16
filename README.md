# Pendigits Classification Colab

This Colab notebook demonstrates how to train and compare Decision Tree and Random Forest classifiers on the Pendigits dataset. It covers data loading, preprocessing, hyperparameter tuning, evaluation, and key visualizations.

## How to Use
1. **Run all cells** to install dependencies and download the dataset.
2. **Preprocess data** by cleaning headers and splitting into training and test sets.
3. **Train models** with GridSearchCV to find optimal hyperparameters.
4. **Evaluate performance** using accuracy, F1-score, confusion matrices, ROC curves.
5. **Visualize results** including t-SNE embeddings and learning curves.

## Key Results
- **Decision Tree**: Accuracy ~0.964, F1-score ~0.964, training time ~10 s
- **Random Forest**: Accuracy ~0.994, F1-score ~0.994, training time ~6 min

**Tip**: Use the Decision Tree for quick experiments and Random Forest when maximum accuracy is needed.

