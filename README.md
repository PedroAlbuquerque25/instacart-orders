# 🛒 Instacart Orders Analysis (TripleTen)

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)

## 📝 Description
This project performs a detailed **Exploratory Data Analysis (EDA)** on order records from the Instacart platform. The main objective was to clean a dataset intentionally modified with missing values and duplicates, and then extract insights about user purchasing behavior.

This project is part of the **TripleTen Data Science curriculum**.

---

## 📊 Data Source
The data used in this project was originally released by **Instacart** in 2017 for a **Kaggle** competition.  
**Context:** The real-world dataset reflects online grocery ordering behavior.  
**Modifications:** For this educational project at **TripleTen**, the data was altered to include missing values and duplicates, allowing the practice of data cleaning and preprocessing techniques.  
**Original Source:** https://tech.instacart.com/3-million-instacart-orders-open-sourced-d40d29ead6f2

---

## 📂 Repository Structure
datasets/ — Folder containing CSV files (headers only)  
aisles.csv  
departments.csv  
instacart_orders.csv  
order_products.csv  
products.csv  

notebooks/ — Project development notebooks  
Instacart-orders.ipynb  

.gitignore — Ignored files (large data and system files)  
requirements.txt — Environment dependencies  
README.md — Main project documentation  

---

## 🛠️ Project Steps
1. **Data Preprocessing**  
   Identification and treatment of missing values.  
   Removal of duplicate records.  
   Data type conversion for memory optimization.  

2. **Exploratory Data Analysis (EDA)**  
   Order distribution by hour of day and day of week.  
   Analysis of time intervals between orders.  
   Identification of the most popular products and departments.  

3. **Conclusions**  
   Summary of the main purchasing patterns identified.  

---

## 🚀 Technologies and Libraries
**Python 3.x**  
**Pandas** — Data manipulation and cleaning  
**NumPy** — Numerical operations  
**Matplotlib & Seaborn** — Data visualization and plotting  

---

## ⚙️ How to Run
1. Clone the repository:  
git clone https://github.com/seu-usuario/instacart-orders.git  

2. Install dependencies:  
pip install -r requirements.txt  

3. **Data**  
The CSV files in the datasets folder contain **only column headers**.  
You must add the actual data to the CSV files as described in the notebook.  
The original data is based on the Instacart dataset and can be obtained separately.  

4. Open the Jupyter Notebook:  
jupyter notebook Instacart-orders.ipynb  

5. Run the cells sequentially to reproduce the analysis.

---

## 📊 Dataset
The dataset consists of **5 CSV tables**:  
instacart_orders.csv — Order-level information  
products.csv — Product details  
order_products.csv — Items included in each order  
aisles.csv — Product aisles  
departments.csv — Product departments  

**Note:** The CSV files included in this repository contain only column headers. You must insert the corresponding data to execute the analysis.

---

## 📈 Key Results
Order patterns by hour of day and day of week.  
Most popular products.  
Distribution of items per order.  
Reorder behavior analysis.  

---

## 🤝 Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request.

---

## 📄 License
This project is intended for educational purposes only.

---

## 🤝 Contato
[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/phaa/)
