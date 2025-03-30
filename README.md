# Breast Cancer Classification

## Overview

This project focuses on breast cancer classification using machine learning techniques. It leverages various preprocessing steps, feature scaling, and classification models to predict whether a tumor is malignant or benign.

## Dataset

The dataset used in this project contains medical diagnostic data related to breast cancer. The features include various characteristics of cell nuclei present in the dataset.

## Installation

To run this project, ensure you have Python installed along with the necessary dependencies. You can install the required libraries using the following command:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn plotly joblib
```

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/breast-cancer-classification.git
   cd breast-cancer-classification
   ```
2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook breast-cancer-classification.ipynb
   ```
3. Run the cells sequentially to preprocess the data, train the model, and evaluate the results.

## Features Implemented

- Data preprocessing (handling missing values, scaling, and normalization)
- Exploratory Data Analysis (EDA) using Matplotlib, Seaborn, and Plotly
- Model training with Logistic Regression
- Performance evaluation using accuracy score, confusion matrix, and classification report
- Model persistence using `joblib`

## Results

The trained model achieves an accuracy of **97%** on the test dataset, effectively distinguishing between malignant and benign cases.

## Contributing

Feel free to fork the repository and submit pull requests with improvements or new features.

## Contact

For any inquiries or suggestions, please reach out via GitHub Issues or contact me at [marawan.abdellah0@gmail.com](mailto:marawan.abdellah0@gmail.com).
