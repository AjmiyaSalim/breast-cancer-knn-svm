# Breast Cancer Diagnosis: KNN vs SVM Comparison

This project uses the **Breast Cancer Wisconsin Diagnostic Dataset** to classify tumors as benign or malignant. Two popular machine learning algorithms — **K-Nearest Neighbors (KNN)** and **Support Vector Machine (SVM)** — are implemented and compared based on their performance.


## 📂 Dataset

The dataset used in this project is referenced from the following UCI Machine Learning Repository source:

🔗 [https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic)](https://www.kaggle.com/datasets/gkalpolukcu/knn-algorithm-dataset)

You can download and explore the dataset from the above link. All rights and credit go to the original contributors at UCI.

> **Note:** The dataset is not uploaded to this repository due to licensing and distribution policies. Please download it from the above link.

---

The **Breast Cancer Wisconsin Diagnostic Dataset** contains features computed from digitized images of fine needle aspirate (FNA) of breast masses.

- **Total Instances:** 569
- **Features:** 30 numeric features
- **Target classes:** 
  - **M** = Malignant  
  - **B** = Benign

## 🔍 Objective

To build and evaluate classification models using:
- **K-Nearest Neighbors (KNN)**
- **Support Vector Machine (SVM)**

The goal is to compare the models' performance in terms of:
- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

## 🛠️ Tools & Libraries

- Python
- Scikit-learn (`sklearn`)
- Pandas
- NumPy
- Matplotlib / Seaborn (for visualization)

## 📈 Workflow

1. **Data Loading**
2. **Data Preprocessing**
   - Label Encoding (M/B → 1/0)
   - Feature scaling
3. **Train-Test Split**
4. **Model Training**
   - KNN (with `n_neighbors=3`)
   - SVM (with default settings)
5. **Evaluation Metrics**
   - Confusion Matrix
   - Accuracy Score
   - Precision, Recall, F1 Score

## 📌 Conclusion

- Both models performed very well, with **SVM slightly outperforming KNN**.
- **SVM** had higher recall for malignant cases, which is important in medical diagnostics.
- **KNN** is simpler and still effective, but may be more sensitive to scaling and choice of `k`.
