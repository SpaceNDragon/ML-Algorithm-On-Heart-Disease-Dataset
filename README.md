# Machine Learning Algorithm on Heart Disease Dataset (heartbeat.csv)

This repository contains the implementation of machine learning algorithms on the Heart Disease Dataset (heartbeat.csv). The objective of this project is to predict the presence of heart disease in patients based on their medical attributes.

## Dataset

The Heart Disease Dataset (heartbeat.csv) contains 303 observations and 14 attributes, including the target variable 'target', which is binary, indicating the presence (1) or absence (0) of heart disease. The other attributes include age, sex, chest pain type, resting blood pressure, serum cholesterol levels, fasting blood sugar levels, resting electrocardiographic results, maximum heart rate achieved, exercise-induced angina, ST depression induced by exercise relative to rest, slope of the peak exercise ST segment, number of major vessels (0-3) colored by fluoroscopy, and thallium stress test results.

The dataset can be downloaded from the following link:

[Heart Disease Dataset (heartbeat.csv)](https://www.kaggle.com/ronitf/heart-disease-uci)

## Machine Learning Algorithms

The following machine learning algorithms were implemented on the Heart Disease Dataset:

- Logistic Regression
- Support Vector Machine (SVM)
- Decision Tree Classifier
- Random Forest Classifier
- Bagging Classifier
- AdaBoost Classifier
- Gradient Boosting Classifier
- XGB Classifier

## Requirements

The following packages are required to run the code:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- warnings

## Usage

1. Clone the repository to your local machine:

```
git clone https://github.com/username/heart-disease.git
```

2. Install the required packages:

```
pip install -r requirements.txt
```

3. Run the Jupyter Notebook:

```
jupyter notebook heart-disease.ipynb
```

4. Follow the instructions in the notebook to execute the machine learning algorithms.

## Results

The accuracy, precision, recall, and F1-score of each machine learning algorithm are reported in the notebook. The results show that the Random Forest algorithm achieved the highest accuracy of 86.88% on the test set. 

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
