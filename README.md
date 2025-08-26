# 🚀 Live Cryptocurrency Data Fetching & Analysis

This project provides a **real-time cryptocurrency data dashboard** 🌐 and analysis tool. It fetches the top 50 live cryptocurrency data from the CoinGecko API, performs analysis, and saves the results to an Excel file for further exploration. 📊

---

## 💡 Features
- **Live Data Fetching**: Continuously fetches the top 50 cryptocurrencies by market cap. 📈
- **Data Analysis**:
  - Identifies the **Top 5 cryptocurrencies by market cap**. 🥇
  - Calculates the **average price** of cryptocurrencies. 💰
  - Highlights the coins with the **highest and lowest 24-hour price changes**. 🔼🔽
- **Excel Export**: Saves all processed data and analysis results to a downloadable Excel file. 📄
- **Interactive Dashboard**: Real-time data display using **Gradio**. 🖥️

---

## 🛠️ Tech Stack
- **Python** 🐍
- **APIs**: CoinGecko API for live cryptocurrency data 🌍
- **Libraries**:
  - `requests` for API integration 🔗
  - `pandas` for data manipulation 📑
  - `openpyxl` for Excel file generation 📘
  - `gradio` for creating an interactive interface 🖱️

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/crypto-analysis.git
cd crypto-analysis
```

### 2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Project
```bash
python fetching_and_analyzing_top_50_live_cryptocurrency_data.py
```

---

## 🎨 How It Works
1. **Fetch Live Data**:
   - Retrieves the top 50 cryptocurrencies by market cap from CoinGecko in USD. 💵
2. **Process Data**:
   - Cleans and analyzes the data:
     - Ranks cryptocurrencies by market cap.
     - Calculates average price, maximum, and minimum 24-hour price changes.
3. **Save to Excel**:
   - Exports:
     - Full dataset.
     - Top 5 cryptocurrencies by market cap.
     - Summary analysis (average price, top gainers, and losers).
4. **Interactive Display**:
   - Continuously updates live data in a Gradio interface for users. 🔄
5. **Excel Download**:
   - Provides the latest processed data as a downloadable Excel file.

---

## 📊 Example Outputs
- **Top 5 Cryptocurrencies by Market Cap**:
  | Cryptocurrency | Symbol | Market Cap (USD) |
  |----------------|--------|------------------|
  | Bitcoin        | BTC    | $1 Trillion      |
  | Ethereum       | ETH    | $500 Billion     |

- **Analysis Summary**:
  - Average Price: `$4,000`
  - Max 24-hour Change: `Dogecoin (12.5%)`
  - Min 24-hour Change: `Litecoin (-8.3%)`

---

## 🔮 Future Enhancements
- Support for multiple currencies (e.g., EUR, GBP). 💱
- Visualizations for market trends and performance. 📈
- Historical data analysis for insights over time. ⏳
- Deployment as a web application. 🌐

---

## 🤝 Contributing
Contributions are welcome! Feel free to fork the repository and submit a pull request. 💡

---

## 📜 License
This project is licensed under the MIT License. Feel free to use and share it! 📄

---

### ✨ Created by(https://github.com/nikhil07897)
```
