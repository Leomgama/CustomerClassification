# Customer Classification Project

![Python](https://img.shields.io/badge/Python-3.14-blue)
![scikit-learn](https://img.shields.io/badge/scikit--learn-1.8.0-orange)
![Folium](https://img.shields.io/badge/Folium-0.20.0-green)
![Pandas](https://img.shields.io/badge/Pandas-2.2.3-lightblue)

## 📋 Business Problem
The Marketing and Sales Director of **BFLUBS** wants to segment the customer base into **five new divisions** using **data science**. This segmentation is based on the **geolocation of customers**, aiming for better organization and more effective commercial strategies.

An **automated methodology** was also developed to classify new customers into the correct divisions using **artificial intelligence**.

---

## 🎯 Approach
1. **Unsupervised Machine Learning** — KMeans clustering to create 5 customer divisions based on latitude and longitude
2. **Supervised Machine Learning** — Decision Tree Classifier trained on the clusters to predict which division new customers belong to

---

## 📁 Project Structure
```
CustomerClassification/
├── CustomerClassification.ipynb   ← Main analysis notebook
├── Business_Problem.ipynb         ← Original problem statement
├── customer_map.html              ← Interactive customer map
├── customer_clusters_map.html     ← Interactive clustered map
├── requirements.txt               ← Project dependencies
├── .gitignore                     ← Git ignore rules
└── data/
    ├── tbl_customers.csv
    ├── tbl_locations.csv
    └── tbl_plants.csv
```

---

## 🗺️ Interactive Maps
Since GitHub does not render interactive Folium maps, view the full notebook with maps here:

👉 [View on nbviewer](https://nbviewer.org/github/Leomgama/CustomerClassification/blob/main/CustomerClassification.ipynb)

---

## 📊 Results
| Metric | Result |
|---|---|
| Total Customers | 1,000 |
| Number of Divisions | 5 |
| Model | Decision Tree Classifier |
| Accuracy | **100%** |
| Test Set Size | 200 customers |

---

## 🔧 Technologies Used
- **Python 3.14**
- **Pandas** — data manipulation
- **Folium** — interactive map visualization
- **Scikit-learn** — KMeans clustering and Decision Tree Classifier
- **Matplotlib** — charts and visualizations

---

## 👤 Author
**Leonardo** — [GitHub](https://github.com/Leomgama)
