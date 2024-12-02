# 📈 Mastercard Stock History - Exploratory Data Analysis (EDA) 📊

![Mastercard Stock History](https://github.com/user-attachments/assets/edc45990-0372-4f0b-a6bb-665f480d6202)

## 🚀 Project Overview

This project dives into **Mastercard's historical stock data**, with the aim of uncovering valuable insights, trends, and patterns. By performing **Exploratory Data Analysis (EDA)**, we aim to understand how Mastercard's stock has behaved over time, identify key characteristics of price fluctuations, and explore the impact of trading volume, dividends, and stock splits on the overall performance.

Through interactive charts and visualizations, we'll analyze the stock’s performance, uncover seasonal trends, and explore correlations between various features.

---

## 📊 Dataset Overview

- **Total Records**: 3872  
- **Date Range**: From **2006-05-25** to the most recent data available.

### **Key Columns in the Dataset**

| **Column**      | **Description**                                                                            |
|-----------------|--------------------------------------------------------------------------------------------|
| `Date`          | The trading day.                                                                           |
| `Open`          | The stock price at market opening.                                                         |
| `High`          | The highest price the stock reached during the day.                                        |
| `Low`           | The lowest price the stock reached during the day.                                         |
| `Close`         | The stock price at market closing.                                                         |
| `Volume`        | Total number of shares traded on that day.                                                 |
| `Dividends`     | The dividend payouts on specific dates.                                                   |
| `Stock Splits`  | Information about stock split events.                                                     |

---

## 🎯 Objectives

### 1. **Preprocessing**
- Convert the **Date** column to the proper datetime format.
- Handle any outliers or anomalous values in numerical fields (e.g., prices, volume).

### 2. **Analysis**
- **Trend Analysis**: Investigate opening and closing price trends over time.
- **Correlation Analysis**: Explore the relationships between **Volume**, **High**, **Low**, and **Close** prices.
- **Impact of Events**: Analyze how **dividends** and **stock splits** influence **prices** and **trading volume**.
- **Seasonality & Periodic Fluctuations**: Identify patterns in stock performance based on time of year or other cyclical events.

### 3. **Visualizations**
- **Line Charts** to visualize price trends (Open, High, Low, Close) over time.
- **Histograms & Box Plots** to visualize price and volume distributions.
- **Heatmaps** to identify correlations between different variables.
- **Event Markers** on price trend charts to highlight stock splits and dividends.

---

## 📦 Dependencies

This project relies on several **Python libraries** for data manipulation, analysis, and visualization:

- **`pandas`**: For data manipulation and analysis.
- **`matplotlib` & `seaborn`**: For creating stunning visualizations.
- **`numpy`**: For numerical computations.
- **`datetime`**: For handling date columns efficiently.

---

## 🔍 Interactive Visuals

The project includes **interactive charts** that allow for an in-depth exploration of the stock data. You'll be able to:

- Zoom in on specific time periods to analyze trends.
- Hover over specific data points to get detailed insights.
- Use event markers to see how key moments, like **stock splits** and **dividend payouts**, affected stock performance.

---

## 💡 Insights and Outcomes

By the end of this analysis, we aim to provide clear insights into Mastercard's stock performance. This will help in:

- Understanding how the stock has evolved over time.
- Gaining insights into market trends and investor behavior.
- Analyzing how corporate actions (like dividends and stock splits) impact stock performance.

---

## 🚀 How to Run This Project

1. **Install Dependencies**: Make sure you have the necessary Python libraries installed using `pip install -r requirements.txt`.
2. **Load the Dataset**: Import the dataset into your notebook and explore the data.
3. **Run the Analysis**: Execute the code blocks to preprocess the data, analyze trends, and create visualizations.
4. **Interact with the Visualizations**: Use the interactive charts to explore the data and uncover new insights!

---

## 🤝 Contributing

Feel free to contribute to this project! If you'd like to make improvements or add new features:

1. **Fork** the repository.
2. Create a **new branch**.
3. Make your changes and **commit** them.
4. Open a **pull request** for review.

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

**Thanks for exploring Mastercard's stock history with us!**  
Dive into the data, interact with the charts, and uncover the hidden stories behind the stock's performance. Let's explore the financial trends together! 🚀📊


