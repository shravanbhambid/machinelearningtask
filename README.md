# Accident Severity Prediction

This project predicts the severity of road accidents using machine learning techniques. The dataset is preprocessed, and a Random Forest model is trained to classify accident severity. The project also provides recommendations based on insights gained from the analysis.

---

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Model Training and Evaluation](#model-training-and-evaluation)
- [Recommendations](#recommendations)
- [Contributing](#contributing)
- [License](#license)

---

## Introduction

Road accidents are a significant concern worldwide, and their severity depends on various factors like time, location, weather conditions, and more. This project aims to:

1. Analyze and preprocess accident data.
2. Build a machine learning model to classify accident severity.
3. Provide actionable recommendations to reduce accident risks.

---

## Dataset

The dataset used in this project is `US_Accidents_March23.csv`, containing detailed information about accidents in the United States.

### Key Features:
- **Start_Time**: Timestamp of the accident.
- **Severity**: The severity of the accident (target variable).
- **Day_of_Week**: Day of the week extracted from `Start_Time`.
- **Hour**: Hour of the day extracted from `Start_Time`.

> Note: The dataset needs to be uploaded in the appropriate location before running the code.

---

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/accident-severity-prediction.git
   cd accident-severity-prediction
pip install -r requirements.txt

python accident_severity_prediction.py
