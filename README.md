# Data Mining Assignment – Grade: 107/100 (+7% Bonus) 🎓

## 📚 Project Overview

This assignment for the Data Mining course demonstrates applied machine learning methods on real-world-style datasets. I explored several algorithms to address classification, clustering, regression, and anomaly detection tasks, emphasizing performance, interpretability, and data-driven decision-making.

---

## 🧠 Key Skills & Techniques

- Data preprocessing and feature engineering  
- Model comparison: classification, clustering, regression  
- Use of algorithms like Random Forest, Decision Trees, Logistic Regression, K-Means, etc.  
- Model evaluation with metrics suitable for each task  
- Demo mode for quick experimentation with sample subsets of the data  

---

## 🛠️ Setup & Usage

1. **Clone the repository**  
   ```bash
   git clone https://github.com/Dimitris-Anagnostopoulos/Assignment_2023_7th.Data_Mining.Assignment.git
   cd Assignment_2023_7th.Data_Mining.Assignment
   ```

2. **Setup environment (Python 3.9)**  
   ```bash
   conda create -n datamine39 python=3.9
   conda activate datamine39
   pip install -r Other/requirements.txt
   ```

3. **Run main program**  
   ```bash
   python main.py -alg SELECT_ALGORITHM
   ```

4. **Demo mode (for quick checks / small subset)**  
   ```bash
   python main.py -alg SELECT_ALGORITHM -demo NUM_OF_ROWS
   ```

---

## 📂 Project Structure

```
├── Data/               # datasets, CSVs used for experiments
├── Models/             # trained model files
├── Classes/            # classes implementing algorithms / utilities
├── Other/              # helper scripts, requirements, settings
└── main.py             # entry point to run experiments
```

---

## 🔧 Technical Stack

| Component         | Tools / Libraries                        |
|-------------------|-------------------------------------------|
| Language          | Python 3.9                                |
| Environment       | Conda                                     |
| Libraries         | scikit-learn, pandas, NumPy, matplotlib   |
| Algorithms        | Classification, Clustering, Regression    |
| Evaluation        | Accuracy, Precision, Recall, etc.         |

---

## 🌟 Results & Insights

- Achieved high accuracy in classification tasks, with thorough evaluation across models  
- Discovered that some algorithms overfit when feature sets are large — addressed via feature selection  
- Clustering showed meaningful grouping, useful for customer or market segmentation analyses

---

## 💡 Potential Extensions

- Add visualization dashboards (Plotly, Seaborn)  
- Expand to time‑series forecasting tasks  
- Implement model explainability tools (SHAP, LIME)  
- Deploy small models or pipelines into MLOps-ready setup  

---

## 📬 Contact & More

- GitHub: [Dimitris-Anagnostopoulos](https://github.com/Dimitris-Anagnostopoulos)  
- LinkedIn: [Dimitris Anagnostopoulos](https://www.linkedin.com/in/dimitris-anagnostopoulos-396361241/)  

Feel free to explore the code, run experiments, or reach out if you have questions or suggestions!
