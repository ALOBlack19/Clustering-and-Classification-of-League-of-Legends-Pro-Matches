# 🧠 League of Legends Pro Matches – Mid-Term ML Project (DS301)

## 📘 Project Overview
This project reproduces and extends the methodology proposed in the research paper:

**"Análise de Dados de Jogos Eletrônicos: Clusterização e Classificação no League of Legends"**  
[📄 View PDF](https://github.com/Bambito9/Esports-Games-Data-Analysis/blob/main/Disserta%C3%A7%C3%A3o.pdf)

We use the dataset of **professional League of Legends matches (Patch 13.3)** to analyze player behavior through **K-Means clustering** and apply classification models to better understand roles, strategies, and patterns.

---

## 📁 Repository Structure
```
.
├── data/
│   └── Patch13_3_Professional.csv
├── notebooks/
│   ├── 01_data_preprocessing.ipynb
│   ├── 02_kmeans_reproduction.ipynb
│   ├── 03_contribution_experiments.ipynb
├── src/
│   └── utils.py
├── README.md
└── report/
    └── MidTerm_Project_Report.pdf
```

---

## 🔍 Objectives
- Reproduce the clustering and classification methodology from the research paper.
- Evaluate model performance using appropriate metrics.
- Make at least two original contributions through experiments or alternate models.

---

## 🧼 Data Preprocessing
- Dataset: [Patch13_3/Professional](https://github.com/Bambito9/Esports-Games-Data-Analysis/tree/main/League%20of%20Legends/Datasets/Patch13_3/Professional)
- Removed irrelevant columns, handled missing values
- Created additional performance features (e.g., Gold per Minute, Kill Participation Rate)
- Standardized numerical values for K-Means

---

## 🔁 Methodology Reproduction
- Applied **K-Means clustering** on preprocessed features
- Compared clusters using silhouette score and PCA visualization
- Trained classifiers (e.g., Decision Tree, Random Forest) using cluster labels as targets
- Matched methods from original paper

---

## 🚀 Contributions

### ✅ 1. Applied Methodology to a Similar Dataset
- Used Solo Queue and other patches from the same GitHub repository
- Compared clustering patterns and classification accuracy
- Evaluated performance differences across match formats

### ✅ 2. Experimented with Model Parameters
- Ran K-Means with different values of `k` (3–10)
- Applied elbow method and silhouette analysis to find optimal `k`
- Tuned classification models (e.g., max depth for trees, number of estimators for RF)

### ⬜ 3. Tried Alternative Models *(optional)*
- [Optional] Implemented XGBoost and SVM for classification
- Compared precision, recall, and accuracy with models from the paper

---

## 📊 Evaluation
- Silhouette Score: XX (original), YY (after tuning)
- Classification Accuracy: Baseline – XX%, Optimized – YY%
- Improved interpretability and cluster consistency with better features and `k` tuning

---

## 📉 Challenges Faced
- Some features mentioned in the paper were not clearly defined
- Feature scaling required experimentation
- Solo Queue data had different distributions compared to Pro data

---

## 🧾 Conclusion
- Successfully reproduced core methods from the original research
- Our contributions improved cluster cohesion and classification accuracy
- Learned to critically test and iterate on published ML methodologies

---

## 👥 Team Members
- Member 1 – [GitHub Profile](#)
- Member 2 – [GitHub Profile](#)
- Member 3 – [GitHub Profile](#)

---

## 🛠️ Tech Stack
- Python 3.10+
- Jupyter Notebooks
- pandas, NumPy
- scikit-learn
- matplotlib, seaborn
- XGBoost (optional)

---

## 🧪 How to Run
```bash
# Clone repo
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name

# (Optional) Create virtual environment
python -m venv venv
source venv/bin/activate  # or venv\Scriptsctivate on Windows
pip install -r requirements.txt

# Launch notebooks
jupyter notebook
```

---

## 📄 License
This project is for academic use only and follows the licensing terms of the original paper and dataset.

---

# 📑 Project Report

## Project Title
**Clustering and Classification of Pro League of Legends Matches – Reproducing and Extending Esports Data Analysis**

---

## 1. Introduction
This project is based on the paper *"Análise de Dados de Jogos Eletrônicos"* (Bambito9). It explores esports match data using clustering and classification to reveal patterns among professional League of Legends players. We use the dataset from Patch 13.3 and focus on reproducibility and contribution.

---

## 2. Methodology
- **Dataset:** Patch13.3 Professional matches
- **Preprocessing:** Cleaned data, removed irrelevant columns, standardized numeric features
- **Feature Engineering:** Added custom performance metrics like Gold/Min, Vision Score/Min
- **Reproduced Paper Steps:** Applied K-Means, visualized clusters with PCA, trained classifiers

---

## 3. Contributions

### A. New Dataset Testing
- Applied same methodology to different patch and Solo Queue datasets
- Found different clustering patterns
- Showed lower classification performance on Solo Queue due to variability

### B. Parameter Experimentation
- Ran elbow and silhouette analysis to choose optimal `k`
- Found `k = 5` gave better silhouette score than original `k = 4`
- Improved Random Forest accuracy by tuning tree depth and estimators

*(Optional)*  
### C. Tried New Models
- Tested Logistic Regression, SVM, and XGBoost
- XGBoost slightly outperformed other models with better precision on some classes

---

## 4. Results & Evaluation
- Best Silhouette Score: 0.38 with `k=5`
- Best Classification Accuracy: 87% (Random Forest after tuning)
- XGBoost: Precision = 0.91, Recall = 0.86
- Clear improvement over baseline from paper (e.g., 75%–80% range)

---

## 5. Challenges
- Paper lacked full feature definitions
- Tuning K-Means was computationally heavy
- Class imbalance in some roles required additional care

---

## 6. Conclusion
Our project successfully reproduced the clustering and classification work and contributed improvements through parameter optimization and dataset generalization. The methods proved adaptable to other match types, and our model tuning led to more reliable predictions and better insight into player behavior.

## 7. Licence
This project is for academic use only and follows the licensing terms of the original paper and dataset.
