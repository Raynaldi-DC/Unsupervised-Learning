# IDXCluster: Automatic Stock Index Construction using Gaussian Mixture Model
📌 Automatically construct a stock index (like LQ45) from Yahoo Finance data using clustering algorithms, focused on Indonesian main board stocks.

---

## 🧠 Project Overview
Creating stock indexes like LQ45 typically involves manual selection. This project introduces an automated approach to construct stock indices using **clustering models**.

We use **Yahoo Finance** to fetch historical stock data for all main board stocks listed on the **Indonesia Stock Exchange (IDX)**. Then, we apply **Gaussian Mixture Models (GMM)** to group similar-performing stocks and identify the most stable and representative stocks for index construction.

## 🚀 How It Works
1. **Data Collection**: Fetch historical OHLCV data using Yahoo Finance.
2. **Feature Engineering**: Calculate turnover, volatility, and market cap.
3. **Clustering**: Apply GMM to group stocks based on quantitative patterns.
4. **Index Selection**: Extract representative stocks from dense clusters.

## 📌 Example
From a dataset of 300+ IDX stocks:
- The model identifies 3 optimal clusters.
- Stocks in the most stable and dense cluster are selected for the index.

## 📂 Project Structure
```
IDXCluster/
├── notebook/
│   └── Tugas_Akhir_Cluster_Saham_YahooFinance.ipynb   # Main notebook
├── requirements.txt                                   # Python dependencies
├── README.md                                          # Project documentation
```

## 💻 Installation & Usage
1. Clone the repository:
```bash
git clone https://github.com/Raynaldi-DC/IDXCluster.git
cd IDXCluster
```

2. Install the dependencies:
```bash
pip install -r requirements.txt
```

3. Run the notebook:
```bash
jupyter notebook notebook/Tugas_Akhir_Cluster_Saham_YahooFinance.ipynb
```

## 🛠️ Tech Stack

- `yfinance`
- `pandas`
- `scikit-learn`
- `matplotlib`, `seaborn`
- `GaussianMixture` from `sklearn.mixture`

---

**Raynaldi Dwi Cahyono**  
📧 raynaldidwicahyono@gmail.com  
🔗 [LinkedIn](https://linkedin.com/in/raynaldidc) | [GitHub](https://github.com/Raynaldi-DC)  
_(This project is licensed under the **MIT License**.)_

---

## Navigation
- [🗣️ Natural Language Processing (NLP)](https://github.com/Raynaldi-DC/Natural-Language-Processing)  
- [🧠 Supervised Learning](https://github.com/Raynaldi-DC/Supervised-Learning)  
- [📊 Unsupervised Learning](https://github.com/Raynaldi-DC/Unsupervised-Learning)  
- [📈 Time Series](https://github.com/Raynaldi-DC/Time-Series)   

[| Main Menu ](https://github.com/Raynaldi-DC)[| Resume ](https://github.com/Raynaldi-DC/Resume)[| Certificates ](https://github.com/Raynaldi-DC/Certificates)[| Portfolio Main Page |](https://github.com/Raynaldi-DC/Portofolio)   
