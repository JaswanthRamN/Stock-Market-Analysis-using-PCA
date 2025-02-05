# Stock-Market-Analysis-using-PCA
## Project Overview  

This project focuses on **Principal Component Analysis (PCA) for Stock Market Data** using **Python, Pandas, NumPy, and Scikit-Learn**. The dataset used in this analysis includes **S&P 500 stock prices and tickers**.

### Key Steps in the Analysis:
- **Loaded the dataset** (`SP500_ticker.csv` and `SP500_close_price_no_missing.csv`) and explored its structure.
- **Computed Log Returns**:
  - Transformed raw stock prices into **log returns** for better analysis.
  - Handled missing values and ensured data consistency.
- **Applied Principal Component Analysis (PCA)**:
  - Standardized log returns before applying PCA.
  - Extracted **8 principal components** to capture variance in stock price movements.
- **Performed Scree Plot Analysis**:
  - Visualized **explained variance ratio** and **eigenvalues** to determine significant components.

This project provides insights into **stock market trends and dimensionality reduction techniques**, helping to identify key factors influencing S&P 500 stock prices.
