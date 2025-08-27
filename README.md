## Iris Flower Classification using DecisionTree 🌸

This project demonstrates **Iris flower classification** using the **Decision Tree Classifier** from scikit-learn.  
The model is trained on the famous **Iris dataset** and visualized with **decision boundaries**.

---

## 📂 Project Structure
Iris-Classification/
- Iris Classification.ipynb   # Main Jupyter Notebook
- requirements.txt            # Required Python libraries
- README.md                   # Project documentation

---

## 🚀 How to Run
1. Clone this repository:
   git clone https://github.com/abdullahq-mlworks/Iris-Classification.git
   cd Iris-Classification
2. Install dependencies:
   pip install -r requirements.txt
3. Open Jupyter Notebook:
   jupyter notebook "Iris Classification.ipynb"

---

## 📊 Features
* Uses **Decision Tree Classifier** from scikit-learn
* Trains on **Iris dataset** (Petal length & width)
* Visualizes **decision boundaries** with matplotlib
* Accuracy evaluation with accuracy_score

---

## 📷 Output Example
Accuracy Score (≈ 1.0 on test set)
Decision boundary plot separating the 3 flower classes:
* Setosa
* Versicolor
* Virginica

---

## 🛠️ Libraries Used
**scikit-learn** – Machine Learning models
**matplotlib** – Visualization
**numpy** – Numerical operations

---

## 📌 Notes
Only **2 features (Petal length & Petal width)** are used for 2D plotting.
np.meshgrid + contourf are used to display **decision boundaries**.

---