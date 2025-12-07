# 🏦 Bank Loan Analysis Dashboard

![Dashboard Preview](<img width="1496" height="725" alt="Screenshot 2025-12-07 212231" src="https://github.com/user-attachments/assets/b6c155ae-1a7f-4b6d-a983-515c2975159b" />)


## 📊 Project Overview

An interactive **Bank Loan Analysis Dashboard** built to provide comprehensive insights into loan portfolio performance, risk assessment, and lending trends. This project analyzes 38,600+ loan applications totaling $435.8M in funded amounts.

## 🎯 Business Problem

Financial institutions often struggle with:
- Limited visibility into loan portfolio performance
- Difficulty identifying risk patterns in real-time
- Manual and time-consuming reporting processes
- Inability to make data-driven lending decisions quickly

## 💡 Solution

A three-tier interactive dashboard system providing:
- **Executive Summary** - High-level KPIs and performance metrics
- **Trend Analysis** - Temporal and demographic patterns
- **Detailed View** - Loan-level granular analysis

## 📈 Key Metrics & Insights

### Portfolio Performance
- **Total Applications:** 38.6K loans
- **Total Funded Amount:** $435.8M
- **Total Received Amount:** $473.1M
- **Average Interest Rate:** 12.0%
- **Average DTI Rate:** 13.3%

### Loan Quality Analysis
- ✅ **Good Loans:** 86.2% (33K loans, $370.2M funded)
  - Fully Paid: 32,145 loans
  - Current: 1,098 loans
- ❌ **Bad Loans:** 13.8% (5K loans, $65.5M funded)
  - Charged Off: 5,333 loans

### Key Findings
1. **Seasonal Trends:** Peak applications in February (4.3K) and September (4.0K)
2. **Loan Terms:** 73.2% prefer 36-month terms over 60-month terms
3. **Top Purpose:** Debt consolidation dominates (18K applications)
4. **Employment Impact:** 10+ years employment = highest volume (8.9K)
5. **Risk Indicator:** Charged-off loans show higher DTI (14%) and interest rates (13.88%)

## 🛠️ Tools & Technologies

- **Visualization Tool:** Power BI / Tableau / Excel (specify yours)
- **Data Processing:** SQL / Python / Excel
- **Data Source:** Bank loan dataset (CSV/Database)

## 📁 Project Structure

```
bank-loan-analysis/
│
├── data/
│   └── bank_loan_data.csv
│
├── dashboard/
│   ├── Bank_Loan_Dashboard.pbix
│   └── dashboard_screenshots/
│       ├── summary_view.png
│       ├── overview_view.png
│       └── details_view.png
│
│
├── README.md
└── LICENSE
```

## 📊 Dashboard Features

### 1. Summary View
- Total loan applications with MTD and MoM growth
- Funded vs. Received amount tracking
- Good loan vs. Bad loan segmentation
- Key performance indicators (KPIs)

### 2. Overview View
- Monthly application trends
- State-wise distribution
- Loan term analysis
- Employee length segmentation
- Purpose-based breakdown
- Home ownership analysis

### 3. Details View
- Loan-level granular data
- Individual loan tracking
- Grade and sub-grade analysis
- Issue date and collection tracking

## 🚀 Getting Started

### Prerequisites
- Power BI Desktop (or your tool)
- Basic understanding of financial metrics

### Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/bank-loan-analysis.git
cd bank-loan-analysis
```

2. Open the dashboard file
```bash
# For Power BI
open dashboard/Bank_Loan_Dashboard.pbix

# For Tableau
open dashboard/Bank_Loan_Dashboard.twbx
```

3. Refresh data connections if needed

## 📸 Dashboard Screenshots

### Summary Dashboard
![Summary View](<img width="1496" height="725" alt="Screenshot 2025-12-07 212231" src="https://github.com/user-attachments/assets/cfd70056-01b5-47cd-91be-996cff0a58bf" />)


### Overview Dashboard
![Overview View](<img width="1174" height="667" alt="Screenshot 2025-12-07 212317" src="https://github.com/user-attachments/assets/3c7d0e2b-7166-4a35-bce2-009d20264b81" />)

### Details Dashboard
![Details View](<img width="1235" height="680" alt="Screenshot 2025-12-07 212351" src="https://github.com/user-attachments/assets/4bfe0079-379f-40d1-8676-043a8fdacb8e" />)


## 💼 Business Impact

- ✅ Reduced reporting time from days to seconds
- ✅ Enabled proactive risk management
- ✅ Identified 13.8% portfolio at risk (Charged Off)
- ✅ 15.8% MoM growth in received amounts
- ✅ Real-time visibility into $473.1M portfolio

## 📚 Learning Outcomes

- Financial metrics analysis (DTI, Interest Rates, Default Rates)
- Data visualization best practices
- Dashboard design principles
- KPI tracking and monitoring
- Risk assessment methodologies

## 🔮 Future Enhancements

- [ ] Predictive modeling for loan default risk
- [ ] Machine learning integration for credit scoring
- [ ] Real-time data pipeline integration
- [ ] Mobile-responsive dashboard version
- [ ] Automated email reporting system

## 👤 Author

**Miraj Kazi**
- LinkedIn: [linkedin.com/in/mirajkazi](https://linkedin.com/in/mirajkazi)
- GitHub: [@yourusername](https://github.com/yourusername)

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Inspiration: Financial analytics best practices
- Tools: Power BI Community, MySQL, Power Bi Services

## 📞 Contact

Feel free to reach out for:
- Collaboration opportunities
- Questions about the project
- Feedback and suggestions

---

⭐ **If you found this project helpful, please give it a star!** ⭐

![GitHub stars](https://img.shields.io/github/stars/yourusername/bank-loan-analysis?style=social)
![GitHub forks](https://img.shields.io/github/forks/yourusername/bank-loan-analysis?style=social)
