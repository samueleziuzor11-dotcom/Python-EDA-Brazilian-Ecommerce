# 🇧🇷 Brazilian E-Commerce Customer Analysis — Python EDA

## 📌 Business Problem
A Brazilian e-commerce company needed to understand **where their customers are located, which regions are underserved, and where growth opportunities exist** across Brazil's 27 states and 5 regions.

This exploratory data analysis (EDA) examines 99,441 customer records to uncover geographic concentration patterns and translate them into actionable business recommendations.

---

## 🛠️ Tools & Libraries Used

| Tool | Purpose |
|---|---|
| **Python** | Core programming language |
| **Pandas** | Data loading, cleaning, and manipulation |
| **Matplotlib** | Data visualization and charts |
| **Seaborn** | Statistical visualizations |
| **Jupyter Notebook** | Interactive analysis environment |

---

## 📂 Dataset
- **Source:** Olist Brazilian E-Commerce Dataset (Kaggle)
- **Records:** 99,441 customer entries
- **Key columns:** `customer_id`, `customer_city`, `customer_state`

---

## 🔍 Analysis Performed

### 1. Data Exploration
- Loaded and inspected dataset shape, data types and structure
- Checked for duplicates and data quality issues
- Mapped state abbreviations to full Brazilian state names for readability

### 2. Customer Analysis by State
- Identified top 10 states by number of customers
- Visualized with a bar chart using Seaborn

### 3. Top 10 Cities by Customer Count
- Ranked cities by customer volume
- Built a horizontal bar chart to visualize city-level dominance

### 4. Regional Distribution
- Mapped all 27 states to Brazil's 5 official regions (Southeast, South, Northeast, Central-West, North)
- Visualized regional breakdown with a pie chart

---

## 📊 Key Insights

### 🏙️ Geographic Concentration Risk
- **São Paulo state alone accounts for ~42% of all customers**
- The top 3 states (São Paulo, Rio de Janeiro, Minas Gerais) represent **over 60% of the entire customer base**
- This level of concentration exposes the business to significant regional risk — any disruption in São Paulo directly threatens the majority of revenue

### 🌆 City-Level Dominance
- **São Paulo city has more customers than the next 4 cities combined**
- Rio de Janeiro is a distant second, followed by Belo Horizonte
- Mid-sized cities like Curitiba and Porto Alegre show meaningful bases and could be high-ROI targets for focused marketing

### 🗺️ Regional Inequality in E-Commerce Reach
- The **Southeast region captures 60%+ of all customers**
- The **North region covers 45% of Brazil's land area but contributes less than 5% of customers**
- The Northeast has a large population but low e-commerce penetration — a major untapped opportunity

---

## 💡 Business Recommendations

1. **Diversify beyond São Paulo** — over-reliance on one state is a strategic risk
2. **Target mid-sized cities** like Curitiba and Porto Alegre — lower competition, meaningful existing demand
3. **Investigate North and Northeast barriers** — are low numbers caused by delivery costs, internet access, or lack of awareness?
4. **Launch regional campaigns** in underrepresented states to grow the customer base more sustainably

---

## 📁 Files in This Repository

| File | Description |
|---|---|
| `Brazillian_EDA_Project.ipynb` | Full Jupyter Notebook with code, charts and insights |

> 💡 **Tip for recruiters:** Open the `.ipynb` file directly on GitHub — it renders the notebook with all charts and markdown insights visible without needing to run any code.

---

## 👤 Author
**samueleziuzor11-dotcom**
Aspiring Data Analyst | Python • SQL • Excel • Power BI | Open to first role
