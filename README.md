# Medical Cost Analysis and Prediction

An exploratory data analysis (EDA) and regression project analyzing individual medical charges based on patient demographics and lifestyle factors.

---

## Dataset Overview

The project uses `insurance.csv` (1,338 records, 7 columns):
* **Features**: `age`, `sex`, `bmi`, `children`, `smoker`, `region`
* **Target**: `charges` (individual medical costs)

---

## Key Highlights

* **Data Cleaning**: Removed duplicate row; dataset contains no missing values (final size: 1,337 rows).
* **Key Finding**: Smoking status is the primary driver of high medical charges, with BMI and age contributing secondary positive trends.

---

## Installation and Setup

1. **Clone the repository and install dependencies**:
   ```bash
   git clone https://github.com/CATPJCN/Medical-Cost-Analysis-and-Prediction.git
   cd Medical-Cost-Analysis-and-Prediction
   pip install -r requirements.txt