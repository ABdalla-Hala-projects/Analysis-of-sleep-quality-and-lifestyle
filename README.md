# 🌙 Sleep Health & Lifestyle Analysis using KNN
> **An AI-powered diagnostic tool to classify sleep disorders based on daily lifestyle patterns.**

---

## 📌 Project Overview
This project leverages Machine Learning to bridge the gap between daily habits and preventive healthcare. By analyzing the **Sleep Health and Lifestyle Dataset**, we developed a **K-Nearest Neighbors (KNN)** classifier capable of identifying whether an individual is healthy or suffering from sleep disorders like **Insomnia** or **Sleep Apnea**.

**The Goal:** To provide data-driven insights into how factors like stress, physical activity, and blood pressure directly influence sleep quality.

---

## 🛠️ Tech Stack & Tools
| Category | Technology |
| :--- | :--- |
| **Language** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) |
| **Data Science** | `Pandas`, `NumPy` |
| **Machine Learning** | `Scikit-Learn` (KNN, Scaling, Encoding) |
| **Visualization** | `Seaborn`, `Matplotlib` |

---

## ⚙️ Technical Workflow

### 1. Advanced Feature Engineering 🧬
* **Blood Pressure Deconstruction:** Split complex string data (e.g., "120/80") into **Systolic** and **Diastolic** numerical features for mathematical compatibility.
* **Missing Value Management:** Intelligently imputed "None" for missing sleep disorder labels to represent healthy subjects.

### 2. Preprocessing & Normalization 🔢
* **Categorical Encoding:** Transformed qualitative features (Gender, Occupation, BMI Category) into numerical labels.
* **Standard Scaling:** Applied `StandardScaler` to normalize features, ensuring the KNN algorithm treats all variables (like steps vs. age) with equal mathematical weight.

### 3. Model Training & Evaluation 🧠
* **Algorithm:** K-Nearest Neighbors (KNN) with $k=5$.
* **Data Splitting:** 80% Training / 20% Testing.
* **Metrics:** Evaluated using **Confusion Matrix**, **Precision**, **Recall**, and **F1-Score**.

---

## 📊 Results & Visualization
The model performance was visualized using a **Confusion Matrix Heatmap**, allowing for clear error analysis and identifying patterns where the model distinguishes between:
* ✅ **None** (Healthy)
- 💤 **Insomnia**
- 🌬️ **Sleep Apnea**



---

## 🚀 Future Roadmap (The Vision)
To evolve this project into a production-level application, the following steps are planned:
- [ ] **Hyperparameter Optimization:** Implementing `GridSearchCV` to find the mathematically optimal $k$.
- [ ] **Algorithm Benchmarking:** Comparing KNN against **Random Forest** and **XGBoost**.
- [ ] **Real-time Integration:** Developing a **Streamlit** dashboard for instant user diagnostics.
- [ ] **IoT Data Fusion:** Incorporating data from wearables (Heart Rate & SpO2) for dynamic tracking.

---

## 🏁 Conclusion
This project demonstrates that lifestyle factors are powerful predictors of sleep health. By utilizing AI, we can move from reactive treatments to proactive lifestyle management.

---

## 👩‍💻 Author
**waleed** *Data Science & Artificial Intelligence Student* [LinkedIn](Your-LinkedIn-URL) | [GitHub](Your-GitHub-URL)

---
*Developed with a commitment to academic excellence and innovation in AI.*
