# Wine Quality Prediction: Machine Learning Project

## Project Overview

The **Wine Quality Prediction** project applies machine learning techniques to predict wine quality based on physicochemical properties. The dataset used consists of attributes such as acidity, alcohol content, pH, and more, which serve as input features for a classification model. The project involves data preprocessing, feature scaling, model training, and performance evaluation using various classification metrics. The model's accuracy, precision, recall, F1-score, and confusion matrix are computed to assess its performance on both cross-validated training and test datasets.

### Key Features:
- Comprehensive **Data Preprocessing** and **Exploratory Data Analysis (EDA)**
- **Feature Scaling** with Min-Max normalization
- Training of classification models with cross-validation
- Performance evaluation with **accuracy**, **precision**, **recall**, **F1-score**, and **confusion matrices**
- Visualizations of model performance

## Requirements

- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

You can install the required dependencies using:

```bash
pip install -r requirements.txt
```


## Installation and Setup

1. **Clone the repository:**

```bash
git clone https://github.com/your-username/wine-quality-prediction.git
cd wine-quality-prediction
```

2. **Install dependencies:**

```bash
pip install -r requirements.txt
```

3. **Download the Dataset:**
   - The dataset used in this project can be found [here](https://archive.ics.uci.edu/ml/datasets/Wine+Quality). Ensure the dataset is placed in the `/data` folder within the project directory.

## Project Structure

```
wine-quality-prediction/
│
├── data/                        # Folder containing the wine quality dataset
│
├── src/                         # Source code
│   ├── main.py                  # Main script to execute the project
│   ├── data_preprocessing.py    # Data cleaning and preprocessing functions
│   ├── model.py                 # Model training, testing, and evaluation functions
│   ├── utils.py                 # Helper functions for model evaluation and metrics
│
├── requirements.txt             # Python dependencies
├── LICENSE                      # Project license information
└── README.md                    # Project overview and setup instructions
```

## Usage

To run the project and train the model, execute the following command:

```bash
python src/main.py
```

### Expected Output:
- **Performance Metrics:** The model's evaluation metrics (accuracy, precision, recall, F1-score) will be displayed in the console.
- **Confusion Matrices:** Visual representations of the confusion matrices for both training (cross-validated) and test sets will be generated.
