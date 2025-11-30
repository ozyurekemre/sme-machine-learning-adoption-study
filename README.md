# Expected Transaction Volume Estimation for SMEs  
### SME-Focused Machine Learning Feasibility Study Using Instacart Dataset  
📄 MSc Data Analytics Dissertation – Berlin School of Business & Innovation (BSBI), 2025

---

## 🎯 Project Overview  
This project investigates **how Small and Medium-Sized Enterprises (SMEs)** can adopt  
machine learning to improve **transaction volume forecasting**, despite resource constraints,  
fragmented data systems, and limited technical expertise.

The study combines:

- **Real SME survey (n = 100)**  
- **ML modelling on Instacart’s 3M-order public dataset**  
- **Experiments with Logistic Regression, Collaborative Filtering, ARIMA, and Federated Learning**  
- **Evaluation of AutoML and privacy-preserving approaches**

📌 *This project is **not** just a forecasting model — it is an applied machine learning feasibility study for real-world SMEs.*

---

## 🔍 Research Goals  
Based on gaps identified in literature and SME feedback, the study explores:

1. **How ML models can be adapted for SMEs operating under data & resource constraints**  
2. **Whether real-time analytics can enhance forecasting accuracy for SMEs**  
3. **How behavioral economics insights (anchoring, herd behavior, mental accounting) influence transaction volume**  
4. **Whether AutoML and Federated Learning can make ML adoption easier and more secure for SMEs**

_Source: Full dissertation, pp. 2–4, 66–72_  
:contentReference[oaicite:2]{index=2}

---

## 🧠 Methodology  
This is a **mixed-methods study** combining:

### ✔ Primary Data  
Survey of 100 SME managers & ML professionals  
- 70% rely on manual or Excel forecasting  
- 10% use ML models  
- 70% have *never heard* of federated learning  
- 60% believe behavioral data improves forecasting accuracy  
_Source: Survey Analytics, pp. 49–54_  
:contentReference[oaicite:3]{index=3}

### ✔ Secondary Data  
Instacart dataset (3+ million orders, 200k users)  
Used for ML experiments simulating SME forecasting scenarios.

---

## 📊 Machine Learning Experiments

### 1️⃣ **Collaborative Filtering (Product Recommendations)**  
- Built a user-item interaction matrix  
- Applied cosine similarity for top-N recommendations  
- Identified strongest patterns in repeat purchases  
- Limitations: sparsity, cold-start, scalability  
_Source: Model Results, pp. 56–58_  
:contentReference[oaicite:4]{index=4}

---

### 2️⃣ **Logistic Regression (Reorder Prediction)**  
- High accuracy: **90%**  
- But **severe class imbalance issues**  
  - Precision (Class 1): 0.41  
  - Recall (Class 1): 0.00  
- Shows that simple models work for SMEs but fail on minority-class forecasting  
_Source: Classification report & confusion matrix, pp. 59–61_  
:contentReference[oaicite:5]{index=5}

---

### 3️⃣ **Time-Series Forecasting (ARIMA)**  
- Weekly transaction volume prediction  
- ARIMA(5,1,0) captures general trend  
- MAE: 374  
- RMSE: 476  
- Struggles with short-term fluctuations  
_Source: Time-series forecasting, pp. 62–64_  
:contentReference[oaicite:6]{index=6}

---

### 4️⃣ **Federated Learning Simulation**  
- Local training on dataset partitions  
- Privacy-preserving aggregation  
- Demonstrated feasibility for SMEs who cannot share raw data  
- Strong potential for retail, healthcare, multi-location SMEs  
_Source: Federated learning experiment, p. 64–65_  
:contentReference[oaicite:7]{index=7}

---

## 📌 Key Findings  
1. **SMEs lack data quality, infrastructure, and ML talent**  
2. **Even simple ML models require class balancing and feature engineering**  
3. **Real-time analytics are powerful but hard to adopt**  
4. **Behavioral economics improves forecasting but is rarely used**  
5. **AutoML can democratize ML adoption**  
6. **Federated learning is a genuine solution for privacy-constrained SMEs**

_Source: Findings & Discussion, pp. 65–71_  
:contentReference[oaicite:8]{index=8}

---

## 💡 Business Impact  
- Improved accuracy in demand & transaction forecasting  
- Reduced stockouts & overstock  
- Privacy-preserving model sharing among SMEs  
- Lower ML entry barrier through AutoML tools  
- Better understanding of customer behavior patterns

---

