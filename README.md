# Amazon Sale Report 2022 Analysis  
_E-commerce Operational Risk Analysis: Amazon India Case_  

## 📌 About the Project  
This project analyzes the **Amazon Sale Report 2022 dataset** from Kaggle.  
The main goal is to explore **operational risks in e-commerce**, such as cancellations, shipping integration issues, and SKU-related problems.  

➡ Kaggle Dataset: [Amazon Sale Report 2022](https://www.kaggle.com/datasets/thedevastator/unlock-profits-with-e-commerce-sales-data)  

The analysis includes:  
- 📊 Order and issue rates by **state and category**  
- 🚚 Distribution of critical statuses like **Cancelled** and **Unknown**  
- 📦 Comparison between **Merchant Fulfilled (MFN)** and **Fulfilled by Amazon (FBA)**  
- 🔎 SKU-level cancellation intensity  

---

## 🛠 Tools Used  
- **Python 3.12**  
- **Pandas** – data processing  
- **Matplotlib & Seaborn** – visualization  
- **Google Colab** – notebook environment  

---

## 📂 Repository Structure  
```bash
amazon-sale-report-2022-analysis/
│
├── data/                     # Source dataset (download from Kaggle)
│
├── notebooks/                
│   └── analysis.ipynb         # Google Colab / Jupyter notebook
│
├── images/                    # Visualizations
│   ├── example-heatmap.png
│   ├── state-category-bar.png
│   ├── mfn-fba-comparison.png
│
├── README.md                  # Project documentation
├── LICENSE                    # MIT License
## 📈 Example Visuals  

You can include the following visuals from your analysis:  

1. **Heatmap** → Problem rates by State x Category (Cancelled, Unknown, Unshipped)  
2. **Bar Chart** → Top 5 states with highest volume + highest issues (Maharashtra, Karnataka, Telangana, Tamil Nadu, Uttar Pradesh)  
3. **MFN vs FBA Plot** → Merchant Fulfilled vs Amazon Fulfilled share  
4. **SKU Analysis Chart** → Top cancelled SKUs (e.g., Set, Kurta, Western Dress)  

---

## 🚀 Key Findings  
- Maharashtra, Karnataka, Telangana, Tamil Nadu, and Uttar Pradesh → **high volume + high issue rates**  
- Set, Kurta, and Western Dress categories have **above-average cancellation rates**  
- “Unknown” statuses mainly come from **shipping integration & manifest problems**  
- Merchant Fulfilled orders in Uttar Pradesh had higher cancellation ratios → should be shifted toward **FBA**  

---

## 📜 License  
This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.  
