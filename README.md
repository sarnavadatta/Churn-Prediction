# Churn-prediction

## Overview
This Jupyter Notebook focuses on predicting customer churn using machine learning techniques. It involves data processing, visualization, and the implementation of classification models to analyze customer behavior and identify potential churners.

## Features
- Data preprocessing and visualization.
- Implementation of machine learning models including Decision Trees and Random Forests.
- Evaluation metrics such as recall, classification reports, and confusion matrices.
- Handling imbalanced datasets using `imbalanced-learn`.

## Requirements
To run this notebook, ensure the following dependencies are installed:

- Python 3.x
- Jupyter Notebook or Google Colab
- Libraries:
  - numpy
  - pandas
  - matplotlib
  - seaborn
  - scikit-learn
  - imbalanced-learn

## How to Use

### Clone the Repository
The notebook starts by cloning the required repository. Run the following command in your environment:
```bash
!git clone https://github.com/sarnavadatta/Churn-prediction.git
```

### Setup Environment
If using Google Colab, mount your Google Drive to access the necessary datasets:
```python
from google.colab import drive
drive.mount('/content/drive')
```

### Install Dependencies
Install the required packages:
```bash
!pip install -U imbalanced-learn
```

### Run the Notebook
Follow the notebook cells sequentially to:
1. Preprocess the data.
2. Visualize the data using `seaborn` and `matplotlib`.
3. Train machine learning models such as Decision Trees and Random Forests.
4. Evaluate the models using metrics and visualizations.

## Data
The dataset used for churn prediction is assumed to be included in the cloned repository or accessible via Google Drive. Ensure the data is properly loaded before proceeding with analysis.

## Results
The notebook provides detailed metrics and visualizations to assess the performance of the implemented models. It includes:
- Confusion Matrix
- Recall Scores
- Classification Reports

## Contribution
If you wish to contribute to this project, fork the repository and submit a pull request with your enhancements.

## License
This project is open-source and available under the [MIT License](https://opensource.org/licenses/MIT).

---

For more details, refer to the [GitHub repository](https://github.com/sarnavadatta/Churn-prediction).

