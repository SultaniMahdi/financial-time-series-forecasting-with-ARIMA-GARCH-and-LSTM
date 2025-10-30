# Financial Time Series Forecasting: LSTM vs ARIMA and GARCH

This project compares **LSTM neural networks** with traditional econometric models — **ARIMA** and **DCC-GARCH** — in forecasting financial time series and estimating **Value-at-Risk (VaR)** using **BMW.DE** daily stock data (2015–2024).

---

## 📊 Project Files

### Folder: `LSTM/`
| File | Description |
|------|--------------|
| `ARIMA.ipynb` | Compares ARIMA with LSTM for price and return forecasting |
| `DCCGarch.ipynb` | Implements DCC-GARCH model for volatility and correlation estimation |
| `VaR.ipynb` | Compares Value-at-Risk (VaR) estimation between LSTM and GARCH models |

---

## 🧠 Research Summary
The results show:
- **LSTM models** outperform ARIMA and GARCH in forecasting accuracy, particularly with nonlinear or non-stationary data.  
- **ARIMA** performs adequately on stationary data but struggles with nonlinear dynamics.  
- **GARCH** models volatility well but tends to slightly underestimate risk.  
- **LSTM** gives better **VaR** estimation and adapts more effectively to changing market conditions.

---

## 🧰 Requirements
Install dependencies before running the notebooks:

```bash
pip install -r requirements.txt
