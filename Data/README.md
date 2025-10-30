# Data Source

The data used in this project is downloaded directly from Yahoo Finance using the `yfinance` library.

Example:

```python
import yfinance as yf

# Download BMW.DE daily data from 2015 to 2024
data = yf.download("BMW.DE", start="2015-01-01", end="2024-12-31")
data.to_csv("data/BMW.DE_2015_2024.csv")  # Optional: Save for reuse
