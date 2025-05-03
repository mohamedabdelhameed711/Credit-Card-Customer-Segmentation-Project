# 🧾 Customers Transactions Analysis & Segmentation

A comprehensive Jupyter Notebook for analyzing customer transaction data through **exploration**, **cleaning**, **preprocessing**, **dimensionality reduction**, and **clustering**. This notebook is ideal for customer segmentation using advanced visualization and machine learning techniques.

---

## 🚀 Features

- ✅ Data cleaning & preprocessing  
- 📊 Advanced visualization with Seaborn & Matplotlib  
- 🔄 Feature engineering with scaling & encoding  
- 📉 Dimensionality reduction using PCA  
- 🔍 Clustering using K-Means and Gaussian Mixture Models  
- 🎯 Visual analysis of clustering results  

---

## 🧰 Libraries Used

### 📦 Data Manipulation & Analysis
- `pandas` – Data loading & transformation  
- `numpy` – Numerical operations  

### 📈 Data Visualization
- `matplotlib.pyplot` – Plotting
- `seaborn` – Statistical visualizations  
- `matplotlib.lines.Line2D` – Custom legend elements  

### 🧹 Preprocessing
- `sklearn.preprocessing.MinMaxScaler`  
- `sklearn.preprocessing.LabelEncoder`  
- `sklearn.preprocessing.PowerTransformer`  

### 📉 Dimensionality Reduction
- `sklearn.decomposition.PCA`  

### 📊 Clustering
- `sklearn.cluster.KMeans`  
- `sklearn.mixture.GaussianMixture`  

### 🔧 Utilities
- `datetime`, `re`, `warnings`, `ast`, `typing.Tuple`  

### 🎨 Styling
- Seaborn style: `seaborn-v0_8-whitegrid`  
- Color palette: `viridis`

---

## 🧪 Notebook Workflow

1. **📥 Library Imports**  
   All required libraries are imported up front.

2. **📂 Data Loading & Exploration**  
   - Load the CSV file.
   - Preview dataset with `.head()`, `.info()`, and descriptive stats.

3. **🧹 Data Cleaning**  
   - Handle missing data.
   - Clean and consolidate product-related columns.

4. **🛠️ Feature Engineering**  
   - Scale numeric features (`MinMaxScaler`)
   - Encode categoricals (`LabelEncoder`)
   - Normalize features (`PowerTransformer`)

5. **📉 PCA for Dimensionality Reduction**  
   - Reduce high-dimensional data to fewer components.

6. **🔍 Clustering**  
   - Apply **K-Means** and **Gaussian Mixture Models**
   - Visualize clusters using PCA-reduced features

7. **📊 Visualization**  
   - Distribution plots, pairplots, and cluster visualizations  

---

## ⚙️ Installation & Setup

### 🔑 Prerequisites
- Python 3.x
- Jupyter Notebook or Jupyter Lab

### 📦 Install Dependencies
``` pip install pandas numpy matplotlib seaborn scikit-learn ``` 

## 📁 Data Description
The notebook expects a CSV file (e.g., bank_transactions.csv) containing columns such as:

### Column Name	Description
#### TransactionID:	Unique transaction identifier
#### CustomerID:	Unique customer identifier
#### TransactionDate:	Date of the transaction
#### TransactionAmount:	Amount spent in the transaction
#### OwnedProducts:	List of products owned



## 📤 Output
### Cleaned and transformed dataset

### Cluster-labeled customer groups

### Visual reports for business insight


## 💡 Notes
All plots follow the seaborn-v0_8-whitegrid style with a viridis color palette for visual clarity.

Warnings are suppressed for smoother notebook execution.



