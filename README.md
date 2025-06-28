# 🎓 Student Performance Predictor

This project is a Machine Learning-based model that predicts whether a student will pass or fail based on their exam scores and gender. The dataset used is from Kaggle's [Students Performance in Exams](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams).

---

## 📌 Features

- Loads and cleans real-world student performance data.
- Uses Logistic Regression to predict student success.
- Handles missing data using imputation.
- Evaluates performance with accuracy, confusion matrix, and classification report.
- Predicts outcomes for new unseen students.

---

## 📊 Technologies & Libraries

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Seaborn, Matplotlib
- Scikit-learn

---

## 🔍 Dataset Info

- **Source**: Kaggle
- **Attributes**:
  - Gender
  - Reading Score
  - Writing Score
  - Math Score (used to label pass/fail)
  - Test Preparation Course, Parental Education, etc. (not used in this version)

---

## ⚙️ How It Works

1. **Data Cleaning**  
   - Converts gender into numeric.
   - Creates a binary label `pass` based on math score.
   - Handles missing values with `SimpleImputer`.

2. **Exploratory Data Analysis (EDA)**  
   - Visualizes the distribution of scores.

3. **Model Training**  
   - Uses Logistic Regression.
   - Performs train/test split.
   - Evaluates predictions with classification metrics.

4. **Prediction**  
   - Accepts new data to predict if the student is likely to pass.

---

## ✅ Project Results

- Model Accuracy: ~98%
- Strong performance on both precision and recall for identifying students who passed.

---

## 📁 Files

- `student-performance-prediction.ipynb`: Jupyter Notebook with all steps.
- `StudentsPerformance.csv`: Dataset file.

---

## 💡 Future Improvements

- Add more features (parental education, test preparation, etc.).
- Try other models (Random Forest, SVM).
- Build a web app using Flask or Streamlit.

---

## 🧠 Author

Made with 💻 by Ninad – 3rd Year Engineering Student passionate about AI & ML.
Connect with me on Linkdin ; ninad_gavhale 
---
