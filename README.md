# 📊 Nova Mart Campaign Performance Analysis

This project delivers a comprehensive analysis of Nova Mart’s recent marketing campaign, focusing on sales performance across cities and product categories. Using seven different data visualizations, the analysis identifies **promotional inefficiencies**, **market execution gaps**, and **key revenue drivers** that inform clear, actionable business recommendations.

## 🚀 Overview
The analysis evaluates:
- Campaign performance across cities  
- Sales behavior across product categories  
- Effectiveness of different promotional schemes  
- Revenue lift before and after promotions  

The study leverages Python and Matplotlib as the primary tools for data exploration and visualization.

## 🔍 Key Findings & Strategic Conclusions

### **1. Promotional Inefficiency**
Deep percentage discounts (25% OFF, 50% OFF) significantly **destroy incremental revenue**, making them unviable for future campaigns.

### **2. Cashback Outperforms Discounts**
The **₹500 Cashback** offer consistently drives the highest **Incremental Revenue % (IR%)**, making it the most profitable promotion.

### **3. Market Execution Gap**
Secondary markets like **Madurai** exhibit strong execution (high ISU%), while major metros like **Visakhapatnam and Hyderabad** underperform — signaling a need for execution standardization.

### **4. Revenue Drivers**
The **Combo1** product category shows exceptional revenue lift post-promotion, indicating strong customer affinity.

## 📌 Actionable Recommendations

| Recommendation | Rationale | Data Source |
|---------------|-----------|-------------|
| **1. Eliminate deep percentage discounts** | Percentage-off promotions lead to negative IR%. | Slide 8 (Scatter Plot) |
| **2. Prioritize Cashback promotions** | ₹500 Cashback delivers the strongest IR%. | Slide 8 (Scatter Plot) |
| **3. Replicate Madurai’s execution model** | Madurai shows strong ISU% and drives high Combo1 revenue lift. | Slide 7, Slide 9 |
| **4. Tailor promotions to low-volume categories** | Home/Personal Care requires specific, not blanket, offers due to small-basket purchases. | Slide 6 |

## 🗂️ Data Sources
This project uses four main relational tables:
- **dim_campaigns**  
- **dim_products**  
- **dim_stores**  
- **fact_events**

## 📈 Visualizations (Analysis Modules)

| Graph | Purpose | Key Metric |
|-------|---------|-------------|
| **1. Bar Chart** | Store Distribution | Store Count by City |
| **2. Pie Chart** | Category Sales Mix | Quantity Sold (Sankranti) |
| **3. Heatmap** | Price Sensitivity | Price vs. Quantity |
| **4. Histograms** | Pre-Promo Patterns | Quantity Distribution |
| **5. Line Graph** | Execution Effectiveness | ISU% by City |
| **6. Scatter Plot** | Offer Profitability | IR% vs. ISU% |
| **7. Grouped Bar** | Revenue Impact | Pre vs. Post Promotion Revenue |

## ⚙️ Setup & Usage

### **Prerequisites**
- Python 3.x  
- Pandas  
- Matplotlib / Seaborn  

### **Installation**
```bash
git clone https://github.com/HruthikExploiter/Nova_Mart_Analysis_1.git
cd NOVA_MART_Analysis_1
add your dataset folder in teh NOVA_MART_Analysis_1 folder
pip install -r requirements.txt
```

### **Running the Analysis**
```bash
jupyter notebook NOVA_MART_project.ipynb
```

## 📬 Contact
**Hruthik Gajjala**  
[LinkedIn Profile](https://www.linkedin.com/in/hruthik-gajjala/)
