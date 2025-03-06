
📜 README.md
# 📊 Trade Data Analysis & Ranking System

## 🚀 Overview
This project analyzes **90-day historical trade data** from **Binance accounts**, calculating **key financial metrics** and ranking accounts based on performance.  

🔹 **Metrics Calculated:**
- ✅ **ROI (Return on Investment)**
- ✅ **PnL (Profit & Loss)**
- ✅ **Sharpe Ratio** (Risk-adjusted returns)
- ✅ **MDD (Maximum Drawdown)** (Largest drop from peak)
- ✅ **Win Rate & Total Positions**
- ✅ **Top 20 Accounts Ranking**

## 📂 Dataset Format
Your CSV should contain the following columns:
```
Port_ID,Timestamp,Price,Quantity,Side,Realized_Profit
ACC_1,2024-01-01,250,2,BUY,30
ACC_1,2024-01-02,260,3,SELL,-20
```
⚙️ Installation

1️⃣ Clone Repository
```bash
git clone https://github.com/your-username/trade-analysis.git
cd trade-analysis
```
2️⃣ Install Dependencies
```bash
pip install pandas numpy streamlit
```
3️⃣ Run the App
```bash
streamlit run trade_analysis.py
```
🔍 Features

✅ Upload your trade data in CSV format  
✅ Automatic calculations of key financial metrics  
✅ Real-time ranking of top-performing accounts  
✅ Download reports as CSV  

🏆 Example Output
📌 Top 5 Accounts (Sample)
```
Rank	Port_ID	ROI (%)	PnL ($)	Win Rate (%)	Sharpe Ratio
1️⃣	ACC_12	55.2	12,500	72.5	1.85
2️⃣	ACC_45	48.7	10,900	70.1	1.62
3️⃣	ACC_78	42.1	9,400	68.9	1.55
```
📌 Contributing
Want to improve this project?

1️⃣ Fork the repo  
2️⃣ Create a branch: git checkout -b feature-xyz  
3️⃣ Commit changes: git commit -m "Added feature XYZ"  
4️⃣ Push to branch: git push origin feature-xyz  
5️⃣ Open a Pull Request! 🚀  

📜 License
This project is licensed under the MIT License.
