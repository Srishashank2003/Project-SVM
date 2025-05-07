# Airline Customer Satisfaction Prediction using SVM

This project uses Support Vector Machines (SVM) to classify Airline passengers as **"Satisfied"** or **"Neutral/Dissatisfied"** based on various service-related features. Multiple SVM kernels (Linear, Polynomial, RBF) are evaluated to determine the most accurate classifier.

---

## Problem Statement

Accurately predicting Customer Satisfaction levels is critical for enhancing airline service quality. This project aims to build a machine learning model that can classify passengers satisfaction using historical data and identify which service factors most influence satisfaction outcomes.

---

## Algorithm

- **Model used:** Support Vector Machine (SVM)
- **Kernels compared:** Linear, Polynomial, Radial Basis Function (RBF)
- **Evaluation Metrics:**
  - Accuracy
  - Classification Report (Precision, Recall, F1-score)
  - Feature Importance via Permutation Importance

---

## Results

- Each kernel was tested for performance using the same train-test split.
- Visual comparison chart added for model accuracies.
- Feature importance plot generated to understand key influencing features.

---

## Setting Up the Virtual Environment

To ensure that all necessary libraries are installed and to avoid dependency issues, it's highly recommended to use a virtual environment. Here's how to set it up:

### 1. **Create a Virtual Environment:**

   In the project directory, Open a terminal and run:

   ```bash
   python -m venv venv
  ```
### 2. **Activate Virtual Environment:**
- On Windows, run:

  ```bash
  .\venv\Scripts\activate
  ```
- On MacOS/Linux, run:

  ```bash
  source venv/bin/activate
  ```
  Once activated, you should see (venv) at the beginning of the terminal prompt.

### 3. **Install Required Libraries:**

```bash
pip install -r requirements.txt
```

### 4. **Deactivating Virtual Environment:**

```bash
deactivate
```
---

## Future Scope

- Deploy the model using a Flask/Django web app.
- Integrate real-time feedback for continuous learning.
- Try ensemble methods (e.g., Random Forest, XGBoost) for comparison.
- Expand to multi-class classification (e.g., level of satisfaction).
- Combine clustering techniques with classification to get insights to different type of customer profiles.

---

## References

- Scikit-learn documentation: https://scikit-learn.org
- Airline Passenger Satisfaction Dataset (source: Kaggle)

## Attribution

This project was developed under the **Microsoft AI National Skilling Initiative (AINSI)** in collaboration with the **All India Council for Technical Education (AICTE)**, Government of India.

Submitted as the **Capstone project** of the Internship program, the project showcases the use of Support Vector Machine (SVM) classification to build a predictive model using Real-World data.