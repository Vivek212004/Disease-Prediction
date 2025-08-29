# Disease-Prediction

# 🩺 Disease Prediction

A machine learning project for predicting diseases based on user symptoms and medical data.

## 🛠️ Technologies Used

- 🐍 **Python 3.x**
- 📊 **NumPy, Pandas** &rarr; Data handling
- 🤖 **Scikit-learn** &rarr; Machine learning algorithms (Random Forest, Logistic Regression)
- 📈 **Matplotlib, Seaborn** &rarr; Visualization
- 💾 **Joblib** &rarr; Model persistence

## ✨ Features

- 🔬 Predicts diseases using trained machine learning models.
- 🌳 Implements Random Forest and Logistic Regression algorithms from scikit-learn.
- 💾 Uses joblib for model serialization and loading.
- 📓 All code is provided in a Google Colab notebook for easy experimentation and reproducibility.
- 📂 Includes a sample dataset: `heart_dataset.csv` for quick testing and demonstration.

## 🚀 Getting Started

### 📝 Prerequisites

- Google Account (for using Google Colab)
- Kaggle account and user API key (for dataset download)
- Basic knowledge of Python and machine learning

### 📦 Dataset

- The dataset used is **heart_disease_uci** from Kaggle.
- Download the dataset using your Kaggle account and API key.
- After downloading, ensure the dataset file is named `heart_dataset.csv` in your working directory or Colab session.

#### 📥 Downloading the Dataset

1. Get your Kaggle API key from your [Kaggle account settings](https://www.kaggle.com/settings).
2. Upload `kaggle.json` (API key) to your Colab session.
3. Run the following commands in a Colab cell to download the dataset:
    ```python
    !pip install kaggle
    import os
    os.environ['KAGGLE_CONFIG_DIR'] = "/content"
    !kaggle datasets download -d ronitf/heart-disease-uci
    !unzip heart-disease-uci.zip
    ```
4. Rename or use the extracted `.csv` as `heart_dataset.csv`.

### ▶️ Usage

1. **Open the Google Colab notebook:**
    - Either upload the provided `.ipynb` file to [Google Colab](https://colab.research.google.com/) or open directly from GitHub.

2. **Upload the sample dataset:**
    - Ensure that `heart_dataset.csv` is available in your Colab session.

3. **Run the notebook cells:**
    - Follow the step-by-step instructions in the notebook.
    - You can train, evaluate, and use Random Forest and Logistic Regression models for disease prediction.

4. **Save or load models:**
    - The notebook uses `joblib` to save trained models and load them for predictions.

## 🤝 Contributing

Contributions are welcome! Please open an issue or submit a pull request for improvements.

## 👤 Author

- [Vivek212004](https://github.com/Vivek212004)

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
