# 📊 Rockbuster Stealth LLC: SQL-Driven Film Rental Analysis | Advanced Analytics

![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white) ![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=Tableau&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=GitHub&logoColor=white)

## 🌟 **Introduction**  
This project analyzes **Rockbuster Stealth LLC’s film rental database** to uncover customer behavior, revenue trends, and global market opportunities. Developed as part of the CareerFoundry Data Analytics Program, it combines SQL-driven analysis with Tableau visualizations to guide strategic decision-making for competing with streaming platforms like Netflix.  

🔗 **Video Presentation Walkthrough:**  
[![Google Drive Video](https://img.shields.io/badge/Video_Presentation-Watch_Here-4285F4)](https://drive.google.com/file/d/1l2hhTfqy13cO6esnYlpCElx6qmo4cf7B/view?usp=sharing)  

---

## 🎯 **Project Objectives**  
1. **Customer Segmentation**: Identify VIP customers and high-revenue markets.  
2. **Genre Performance**: Analyze top-performing movie genres and rental trends.  
3. **Global Expansion**: Recommend target cities/countries for growth.  
4. **Revenue Optimization**: Provide pricing and inventory strategies.  

---

## 🛠️ **Tools & Technologies**  
- **SQL (PostgreSQL)**: Data extraction, cleaning, and aggregation.  
- **Tableau**: Interactive visualizations for stakeholder insights.  
- **Excel**: Data validation and supplementary reporting.  
- **Jupyter Notebook**: SQL query documentation and organization.  

---

## 📂 **Dataset Overview**  
**Rockbuster’s Relational Database** includes:  
- **Key Tables**: `film`, `inventory`, `customer`, `rental`, `payment`.  
- **Features**: Movie genres, rental duration, customer demographics, payment history.  
- **Size**: 15+ tables with 1M+ rows (cleaned and filtered for analysis).  

---

## 🔍 **Key Steps & Insights**  
### 🧹 **Data Cleaning & Preprocessing**  
- Joined tables (`rental` ↔ `inventory` ↔ `film`) to map rentals to genres.  
- Filtered inactive customers and outdated movie catalogs.  
- Standardized currency and date formats for global analysis.  

### 📊 **Exploratory Data Analysis (EDA)**  
- **Top Genres**: Action (23% of rentals) and Comedy (19%).  
- **Peak Rentals**: 65% of rentals occurred on weekends.  
- **VIP Customers**: Top 10 customers contributed **15% of total revenue**.  

### 🌍 **Market Opportunities**  
- **High-Growth Regions**: Berlin, London, and Hyderabad showed untapped demand.  
- **Revenue Leaders**: USA, India, and China generated 60% of global revenue.  

---

## 📊 **Key Visualizations**  
Explore the Tableau charts for deeper insights:  

### 1. **Descriptive Statistics Overview**  
[![Tableau](https://img.shields.io/badge/View_Chart-E97627)](https://public.tableau.com/views/CF_SQL_Session_Rockbuster_Stealth_LLC_Chapter_10_Visualization1_DescriptiveStatisticsTask3_6Step2/Sheet1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)  
- **Insight**: Global revenue distribution and customer demographics.  

### 2. **Top 10 Countries by Customer Count**  
[![Tableau](https://img.shields.io/badge/View_Bubble_Chart-E97627)](https://public.tableau.com/views/CF_SQL_Session_Chapter_10_Top10CountriesbyCustomerNumbersTask3_7Step1/BubbleChart?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)  
- **Insight**: USA, India, and China dominate customer bases.  

### 3. **Top 10 Cities in Top 10 Countries**  
[![Tableau](https://img.shields.io/badge/View_City_Analysis-E97627)](https://public.tableau.com/views/CF_SQL_Session_Chapter_10_Visualization3_Top10CitiesWithintheTop10CountriesTask3_7Step2/Top10CitiesWithintheTop10CountriesbyCustomerCount?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)  
- **Insight**: Berlin and London lead in European markets.  

### 4. **Top 5 Customers by Total Payment**  
[![Tableau](https://img.shields.io/badge/View_VIP_Customers-E97627)](https://public.tableau.com/views/CF_SQL_Session_Chapter_10_Top5CustomersByTotalAmountPaidTask3_7Step3/Top5CustomersbyTotalAmountPaid?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)  
- **Insight**: VIP customers drive 15% of total revenue.  

---

## 🚀 **Business Impact & Recommendations**  
### **Insights**  
- **Genre Focus**: Action and Comedy films are revenue powerhouses.  
- **Weekend Demand**: 65% of rentals occur on weekends.  
- **Untapped Markets**: Eastern Europe shows rising demand.  

### **Recommendations**  
1. **Inventory Prioritization**: Stock more Action/Comedy films in high-revenue regions.  
2. **Weekend Pricing**: Implement surge pricing for weekend rentals.  
3. **Loyalty Programs**: Reward top customers with exclusive offers.  
4. **Targeted Expansion**: Launch marketing campaigns in Berlin and Hyderabad.  

---

## 📂 **Repository Structure**  
```plaintext
Rockbuster-SQL-Case-Study/  
├── SQL_Queries/           # Jupyter Notebook with SQL scripts  
├── Data_Dictionary/       # Column definitions and metadata  
├── Visualizations/        # Tableau charts (linked above)  
├── Reports/               # PDF summaries and slide decks  
├── README.md              # Project overview  
└── LICENSE                # Usage terms (optional)  
