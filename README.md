# 🎓 Student Performance Prediction (ML Project)

## 📌 Overview

This project is a Machine Learning model that predicts whether a student will **PASS or FAIL** based on academic and behavioral features such as attendance, study hours, assignments, and previous scores.

The entire dataset is created within the code using a pandas DataFrame, making the project **self-contained and easy to understand**.

---

## 🚀 Features

* Predict student performance (PASS/FAIL)
* Uses **Random Forest Classifier**
* Displays:

  * Model Accuracy
  * Classification Report
  * Feature Importance
* Accepts user input for prediction

---

## 🧠 Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn

---

## 📊 Input Features

* **Attendance (%)**
* **Study Hours per Day**
* **Assignments Completed**
* **Previous Score**

---

## ⚙️ How It Works

1. A dataset is created programmatically using pandas.
2. Data is split into training and testing sets.
3. A **Random Forest model** is trained on the data.
4. The model is evaluated using accuracy and classification metrics.
5. Feature importance is calculated to understand key factors.
6. User can input new data to get predictions.

---

## 🧪 Example Input

```
Attendance: 80
Study Hours: 3
Assignments: 7
Previous Score: 70
```

### Output

```
Result: PASS ✅
```

---

## 📈 Model Details

* Algorithm: **Random Forest Classifier**
* Evaluation Metrics:

  * Accuracy Score
  * Classification Report (Precision, Recall, F1-score)

---

## 💡 Key Insights

* Attendance and previous scores are strong indicators of performance.
* Model provides feature importance for interpretability.

---

## 🔮 Future Improvements

* Use a larger real-world dataset
* Add data visualization (graphs)
* Build a web interface (Flask/Streamlit)
* Deploy as an API for real-time use

---

## 🧑‍💻 Author

** Koppada Sanjay Kumar**

---

## ⭐ Conclusion

This project demonstrates a complete ML workflow including data creation, training, evaluation, and prediction — making it a solid beginner-to-intermediate level machine learning project.
