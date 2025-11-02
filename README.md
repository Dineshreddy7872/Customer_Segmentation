[README.md](https://github.com/user-attachments/files/23287932/README.md)
# 🧩 Customer Segmentation Analysis

This project demonstrates **Customer Segmentation** using **K-Means** and **Hierarchical Clustering** algorithms. The aim is to identify distinct customer groups based on **Annual Income** and **Spending Score**, enabling data-driven marketing and customer relationship strategies.

An **interactive Gradio web app** is included to visualize clusters, analyze patterns, and explore segmentation insights dynamically.

---

## 🚀 Project Overview

Customer segmentation helps businesses understand customer behavior and tailor marketing strategies.  
This project applies **unsupervised machine learning** techniques to group mall customers based on their purchasing habits.

### 🔍 Key Features
- **K-Means & Hierarchical Clustering** implementation  
- **Elbow Method** and **Dendrogram** visualizations  
- **Silhouette Score** for model performance evaluation  
- **Interactive Gradio dashboard** for exploration  
- **Dynamic cluster analysis with statistical insights**

---

## 🧠 Machine Learning Workflow

1. **Data Preprocessing**  
   - Used `Mall_Customers.csv` dataset  
   - Selected features: *Annual Income* and *Spending Score*  

2. **Exploratory Analysis**  
   - Visualized patterns and spending behaviors  
   - Determined optimal number of clusters using the **Elbow Method**

3. **Modeling**  
   - Applied **K-Means** and **Agglomerative Clustering (Hierarchical)**  
   - Evaluated clusters using **Silhouette Score**

4. **Visualization & Insights**  
   - Compared clustering results visually  
   - Interpreted customer types (e.g., *High Income–High Spending*, *Budget Conscious*, etc.)

5. **Gradio Interface**  
   - Built a real-time, interactive dashboard for analysis  
   - Allows users to adjust number of clusters and algorithm type  

---

## 🧰 Tech Stack

| Category | Tools / Libraries |
|-----------|-------------------|
| **Language** | Python |
| **Libraries** | pandas, numpy, matplotlib, seaborn, scikit-learn, scipy, gradio |
| **Visualization** | matplotlib, seaborn |
| **UI Framework** | Gradio |
| **Environment** | Google Colab / Jupyter Notebook |

---

## 💻 How to Run

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/customer-segmentation.git
cd customer-segmentation
```

### 2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Gradio App
```bash
python app.py
```

You’ll see a **public Gradio link** in your terminal — open it in your browser to interact with the app.

---

## 🖥️ Gradio Interface Overview

| Feature | Description |
|----------|--------------|
| **Number of Clusters** | Choose clusters (2–10) |
| **Algorithm** | Select between K-Means and Hierarchical |
| **Linkage Method** | Choose from `ward`, `complete`, `average`, `single` |
| **Tabs** | Visualizations, Elbow Method, Dendrogram, Cluster Stats, Raw Data |
| **Outputs** | Cluster visual plots, statistical summary, silhouette score |

---

## 📊 Sample Output

- **Elbow Plot:** Helps identify the optimal number of clusters  
- **Cluster Visualization:** Displays distinct customer groups  
- **Dendrogram:** Hierarchical structure of customer relationships  
- **Cluster Insights:** Mean age, income, spending score, and customer type interpretation  

---

## 📦 File Structure

```
📁 Customer_Segmentation/
│
├── app.py                     # Gradio interface
├── customer_segmentation.ipynb # Jupyter notebook
├── Mall_Customers.csv          # Dataset
├── requirements.txt            # Required dependencies
└── README.md                   # Project documentation
```

---

## 🧾 Requirements

```
pandas
numpy
matplotlib
seaborn
scikit-learn
scipy
gradio
```

## ⭐ Acknowledgements
- Dataset: *Mall Customers Dataset (Kaggle)*  
- Gradio: *Open-source ML App Framework*  
- Inspired by real-world marketing analytics projects  
