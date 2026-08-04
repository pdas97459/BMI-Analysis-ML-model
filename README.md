# BMI Classification using Logistic Regression

## Overview
This project implements a Logistic Regression model to classify BMI into two categories based on height and weight.

The dataset is synthetically generated using NumPy. The model is trained using Scikit-learn and visualized using Matplotlib and mlxtend.

## Features
- Generates random height and weight data
- Calculates BMI
- Converts BMI into binary classes
- Splits data into training and testing sets
- Standardizes features using StandardScaler
- Trains a Logistic Regression model
- Evaluates model accuracy
- Visualizes decision boundaries

## Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- mlxtend

## Project Structure
```
BMI-Classification/
│── bmi_classification.py
│── README.md
│── requirements.txt
│── bmi_dataset.json (optional)
```

## Installation

1. Clone the repository
```
git clone https://github.com/yourusername/BMI-Classification.git
```

2. Install dependencies
```
pip install -r requirements.txt
```

3. Run the project
```
python bmi_classification.py
```

## Model
- Algorithm: Logistic Regression
- Features:
  - Height
  - Weight
- Target:
  - BMI Class (0 or 1)

## Results
The model predicts whether a person's BMI belongs to the lower or higher category based on the average BMI threshold of the generated dataset.

## Future Improvements
- Use a real-world BMI dataset
- Classify into standard BMI categories (Underweight, Normal, Overweight, Obese)
- Build a web application using Flask or Streamlit
- Deploy the model online

## Author
Pooja Das
