# 🧠 Smart Market Intelligence & Business Insights System

### Using Evolutionary Algorithms for Feature Selection

---

## 👨‍💻 Author

**Sagnik Patra**

---

## 📌 Project Overview

This project focuses on building an intelligent **Market Intelligence System** using **Machine Learning and Evolutionary Algorithms**.

The system analyzes market data from an Excel dataset and applies advanced optimization techniques like:

* CSA (Clonal Selection Algorithm)
* PSO (Particle Swarm Optimization)
* QPSO (Quantum PSO)
* BA (Bat Algorithm)
* ALOA (Ant Lion Optimization Algorithm)
* GWO (Grey Wolf Optimization)
* WOA (Whale Optimization Algorithm)

to perform **feature selection and improve model accuracy**.

---

## 🎯 Objectives

* Extract meaningful insights from market data
* Perform intelligent **feature selection**
* Compare multiple **optimization algorithms**
* Improve prediction accuracy using ML models
* Generate visual analytics (graphs & heatmaps)

---

## 📂 Dataset

* Format: `.xls` (Excel file)
* Contains: Market/business-related data
* Preprocessing:

  * Missing value handling (`ffill`)
  * Label encoding for categorical data

---

## ⚙️ Technologies Used

* Python 🐍
* Pandas, NumPy
* Scikit-learn
* Matplotlib, Seaborn
* Evolutionary Algorithms

---

## 🤖 Machine Learning Model

* **Random Forest Classifier**

  * Used for prediction
  * Trained after feature selection
  * Evaluated using accuracy score

---

## 🧬 Algorithms Implemented

| Algorithm | Purpose                        |
| --------- | ------------------------------ |
| CSA       | Immune-based feature selection |
| PSO       | Swarm-based optimization       |
| QPSO      | Quantum-enhanced PSO           |
| BA        | Bio-inspired bat search        |
| ALOA      | Ant-lion hunting optimization  |
| GWO       | Wolf-pack hunting strategy     |
| WOA       | Whale bubble-net hunting       |

---

## 📊 Visual Outputs

### 🔥 Confusion Matrix Heatmap

**File:** `RandomForest_heatmap.png`

This heatmap shows the performance of the Random Forest classifier in terms of correct and incorrect predictions.

---

## 📈 Generated Graphs

* Accuracy convergence graph
* Model comparison graph
* Prediction vs Actual graph
* Feature correlation heatmap

---

## 📄 Output Files

### 📊 CSV Files

* `*_results.csv` → Actual vs Predicted
* `*_summary.csv` → Model accuracy
* `*_selected_features.csv` → Selected feature indices

### 🖼️ Graphs

* `*_heatmap.png`
* `*_accuracy_graph.png`
* `*_prediction_graph.png`
* `*_correlation_heatmap.png`

---

## 🚀 How to Run

### 1️⃣ Install Dependencies

```bash
pip install pandas numpy scikit-learn matplotlib seaborn openpyxl
```

### 2️⃣ Set Dataset Path

Update path in code:

```python
input_path = "your_dataset_path.xls"
```

### 3️⃣ Run the Script

```bash
python main.py
```

---

## 🧠 Key Features

* Multi-algorithm feature selection
* High accuracy optimization
* Visual analytics dashboard (via graphs)
* Fully automated ML pipeline
* Scalable for large datasets

---

## 📌 Results

* Improved model accuracy using evolutionary algorithms
* Identified optimal feature subsets
* Generated interpretable visualizations
* Built a robust decision-support system

---

## 🏆 Conclusion

This project demonstrates how **evolutionary algorithms can significantly enhance machine learning performance** by selecting the most relevant features.

It provides a **powerful framework for business intelligence and data-driven decision making**.

---

## 🔮 Future Enhancements

* Integration with **XGBoost / Deep Learning**
* Real-time dashboard using Streamlit
* Deployment as a web application
* Hyperparameter tuning automation

---

## ⭐ Acknowledgment

This project is developed as part of advanced learning in **Machine Learning and Optimization Techniques**.

---

## 📬 Contact

For queries or collaboration:
**Sagnik Patra**

---

# 🚀 If you like this project, give it a ⭐ on GitHub!
