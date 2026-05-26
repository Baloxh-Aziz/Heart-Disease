# Heart Disease Prediction

A machine learning project that predicts the presence of heart disease using Logistic Regression.

## Overview

This notebook trains a binary classification model on the [Heart Disease dataset](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset) to predict whether a patient has heart disease (`target = 1`) or not (`target = 0`).

## Project Structure

```
├── heart_datase.ipynb   # Main notebook
├── requirements.txt     # Python dependencies
└── README.md
```

## How It Works

1. **Load data** — reads `heart.csv` into a pandas DataFrame
2. **Explore** — inspects shape, types, and summary statistics
3. **Prepare** — splits features (`X`) and label (`y = target`)
4. **Train/Test Split** — 80% train / 20% test (`random_state=42`)
5. **Model** — Logistic Regression (`max_iter=1000`)
6. **Evaluate** — accuracy score, confusion matrix, classification report
7. **Predict** — runs inference on a sample input

## Results

The model outputs:
- **Accuracy** on the test set
- **Confusion Matrix**
- **Classification Report** (precision, recall, F1-score)

## Getting Started

### 1. Clone the repo
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Add the dataset
Download `heart.csv` from [Kaggle](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset) and place it in the project folder. Update the file path in the notebook if needed.

### 4. Run the notebook
```bash
jupyter notebook heart_datase.ipynb
```

## Dependencies

- Python 3.8+
- pandas
- numpy
- scikit-learn
- jupyter

## License

This project is for educational purposes.
