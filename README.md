# NVIDIA Stock Trends and Volatility Analysis (2023-2024)

![image](https://github.com/user-attachments/assets/b73bcaf3-607e-4d92-96c9-4a71618e556f)



## Project Description
This project conducts a comprehensive analysis of NVIDIA's stock trends and volatility from 2023 to 2024. Using Python and key financial metrics like Bollinger Bands, Average True Range (ATR), and moving averages, the analysis uncovers patterns in stock price movements, volatility characteristics, and trading volume correlations. The findings highlight NVIDIA's strong growth trajectory alongside its inherent market volatility, providing valuable insights for investors.

## Key Features
- **Data Exploration**: Analysis of daily stock prices (Open, High, Low, Close, Volume) from Kaggle.
- **Feature Engineering**: Added metrics like Daily Returns, Moving Averages, ATR, and Bollinger Bands.
- **Visualizations**: Interactive plots showing price trends, volatility, and volume-price relationships.
- **Trend Identification**: Seasonal patterns and residual volatility analysis using decomposition techniques.

## Insights
1. **Strong Growth**: NVIDIA's stock price surged from $25 to over $120 (March 2023–September 2024).
2. **High Volatility**: Increased volatility in 2024, with Bollinger Bands and ATR indicating wider price swings.
3. **Volume-Price Correlation**: Volume spikes often coincided with significant price movements.
4. **Technical Indicators**: Bullish momentum confirmed by moving averages and Bollinger Bands analysis.

## Tools & Technologies
- **Python Libraries**: Pandas, NumPy, Matplotlib, Seaborn
- **Data Source**: [NVIDIA Stock Dataset (2023-2024)](https://www.kaggle.com/datasets/syedfaizanalii/nividia-stock-dataset-2023-2024) (Kaggle)
- **Environment**: Google Colab (Jupyter Notebook)

## Project Structure
    nvidia-stock-analysis/                    # Project Repository
    ├── data/                  
      ├── nvidia_stock_data.csv               # Dataset (CSV file)
    ├── report/
      ├── Nvidia's Stock Analysis.pdf         # Project Report
    ├── src/                                  
      ├── Nvidia_Stock_Price_Analysis.ipynb   # Jupyter Notebook for analysis
    └── README.md                             # Project documentation

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/nvidia-stock-analysis.git
2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn
3. Run the Jupyter Notebook (nvidia_stock_analysis.ipynb) to reproduce the analysis.
