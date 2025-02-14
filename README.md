# 📈 Stock Price Predictor App

🚀 **Predict future stock prices with AI!** This project uses **deep learning (LSTM)** to analyze historical stock data and forecast future trends. With **Streamlit & Yahoo Finance**, you can interactively predict stock prices. Plus, it runs **seamlessly on Google Colab**—no powerful hardware needed! 🎯

---

## 🚀 Features
✅ **Real-time stock data** fetching from Yahoo Finance 📊  
✅ **Deep Learning (LSTM)** based stock price prediction 🤖  
✅ **Interactive moving average (100, 200, 250 days) visualization** 📈  
✅ **Easy deployment & access** with Streamlit 🌐  
✅ **Google Colab support**—run it anywhere, no setup required! 💻  

---

## 📌 Steps to Run the Project

### 1️⃣ Upload Files to Google Colab 📂
Follow these steps to upload the required files:
1. Open **Google Colab** ([Click Here](https://colab.research.google.com/))
2. Click on the **folder icon** 📁 in the left sidebar
3. Click the **Upload button** ⬆️ and select these two files:
   - `stock_price.ipynb` (Jupyter Notebook)
   - `web_stock_price_predictor.py` (Streamlit App)

### 2️⃣ Run the Jupyter Notebook ▶️
Just **click** on **Run All Cells** in `stock_price.ipynb`. The model will train, and the server will start.

### 3️⃣ Get Your App Link 🔗
Once the notebook runs successfully, you’ll see a **Streamlit App link** in the last output cell. **Click on it!** 🎯

### 4️⃣ Enter the Password 🔑
The app will ask for a **password**. Run the command below in **Cell 2** of the notebook:
```bash
!wget -q -O - ipv4.icanhazip.com
```
Copy the **output** and enter it as your **password**.

### 5️⃣ Start Using Your Stock Predictor 📈
You’re in! **Congrats! 🎉**

---

## 📊 How to Use the App

### 🔍 Step 1: Find Stock Ticker Symbol
Go to **[Yahoo Finance](https://finance.yahoo.com/)** 🔗 and **search for a stock**. Find the **short form (ticker)** inside **parentheses**:
- **Example:** Microsoft Corporation (**MSFT**), Apple (**AAPL**), Tesla (**TSLA**).

### ⌨️ Step 2: Enter Stock Code
In the app, **type** the **company code** (e.g., **MSFT** for Microsoft) and **hit Enter**! 🚀

### 🖨️ Step 3: Print the Results
Click on the **three dots** in the top-right corner of the app and **select Print** to save your predictions. 🖨️

---

## 🔧 Installation & Running Locally (Optional)

Want to run it on your **local machine** instead of Google Colab? Follow these steps:

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/stock-price-predictor.git
cd stock-price-predictor
```

### 2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 3️⃣ Run the App
```bash
streamlit run web_stock_price_predictor.py
```

---

## 🎯 Technologies Used
- **Python** 🐍
- **Streamlit** 🚀
- **Keras / TensorFlow** 🧠
- **Yahoo Finance API** 📊
- **Pandas, NumPy, Matplotlib** 🔬

---

## 🤝 Contributing
Love this project? **Fork it, improve it, and send a Pull Request!** 🚀

---

## 📧 Contact
For questions or feedback, **open a GitHub Issue** or reach out via email. 💌

---

🎯 **Start predicting stock trends with AI! Happy Trading! 💹📊**
