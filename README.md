## **⚓ Multimodal Energy Risk & Hedging Engine (2026 OIL Crisis Simulation Due TO Iran WAR)**

## 📊 Project Overview
This project is a production-grade risk management system designed to navigate a simulated energy crisis in the Strait of Hormuz. It utilizes **Multimodal AI** by fusing physical telemetry (AIS vessel tracking) with unstructured NLP signals (FinBERT sentiment analysis) to quantify geopolitical risk and automate financial hedging strategies.

### 🚀 Key Features
- **Multimodal Fusion**: Integrates Brent prices, vessel counts, and news sentiment into a unified feature vector ($X_t$).
- **GERI Index**: A custom-calibrated Geopolitical Energy Risk Index that weights physical deficits (65%) and sentiment stress (35%).
- **GRU Forecasting**: Uses a Gated Recurrent Unit (GRU) neural network for sequence-based risk prediction.
- **Interactive 3D Dashboard**: Built with Streamlit and Plotly to visualize crisis trajectories and dynamic stress surfaces.
- **Algorithmic Hedging**: Automated Order Execution Gateway for Crude Oil Futures (CL).
- **Production Ready**: Includes FastAPI backend, SQL (SQLite) storage, and Docker containerization.

## 🛠️ Tech Stack
- **Languages**: Python (Pandas, NumPy, SQLAlchemy)
- **AI/ML**: PyTorch (GRU), Transformers (FinBERT), Scikit-Learn
- **Visualization**: Plotly, Streamlit
- **DevOps/Backend**: FastAPI, Docker, Uvicorn, LocalTunnel
- **Database**: SQLite / PostgreSQL (pgvector simulation)
- **Visualization**: Power BI, Julius
- **SQL**: postgresql
- 

## 🏗️ Architecture
1. **Data Ingestion**: Mocks 2026 crisis data including AIS telemetry and news headlines.
2. **NLP Engine**: Processes headlines through FinBERT for sentiment polarity.
3. **Risk Engine**: Calculates GERI scores and Optimal Hedge Ratios.
4. **Execution Layer**: Simulates sending SELL orders to an exchange based on risk thresholds.

## 📈 Results (Backtest)
- **Scenario**: 2021 Suez Canal Obstruction Analog.
- **Calibration Accuracy**: Achieved a calibration error of only **2.75 units** against historical price volatility.
- **Simulated Crisis (2026)**: Identified a 91.79/100 risk score, triggering a 0.92 hedge ratio during a 92% tanker deficit.

## 💻 How to Run
1. Clone the repo.
2. Install dependencies: `pip install -r requirements.txt`
3. Run the dashboard: `streamlit run dashboard.py`

<img width="1837" height="827" alt="Screenshot 2026-08-07 010853" src="https://github.com/user-attachments/assets/2a18f3da-690e-4d13-86df-09cbde15ddec" />
<img width="1485" height="827" alt="Screenshot 2026-08-07 010906" src="https://github.com/user-attachments/assets/de94cca7-8c21-4034-986f-5a0dafffda02" />
<img width="1517" height="642" alt="Screenshot 2026-08-07 010916" src="https://github.com/user-attachments/assets/2c4c55f7-424d-49e0-8f3b-59010ca5b79b" />

 **FastAPI Engine & Interactive Dashboard 2D & 3D Image**
 <img width="891" height="497" alt="image" src="https://github.com/user-attachments/assets/b8ec4338-596d-4e80-81d6-a12b5820d7d0" />
 
 <img width="942" height="498" alt="image" src="https://github.com/user-attachments/assets/2d6e444f-7ef3-4302-a7c1-29e33a6b1e0c" />
 <img width="1295" height="565" alt="image" src="https://github.com/user-attachments/assets/3a10ba9a-9f33-46b6-b9db-75e70e8f7afa" />
 <img width="1255" height="502" alt="image" src="https://github.com/user-attachments/assets/52588030-db46-4881-a280-f193bfdc1966" />
 


**Power BI with the Integration of Julius**
<img width="1897" height="898" alt="image" src="https://github.com/user-attachments/assets/5d751ca2-4fda-45f3-9bcc-94ee0aa9dbc9" />
<img width="1892" height="717" alt="image" src="https://github.com/user-attachments/assets/6b04fd96-e10c-4647-8572-5a0cb9b20549" />
<img width="1912" height="833" alt="image" src="https://github.com/user-attachments/assets/428fbe16-31e1-47cc-96f3-85f60e378710" />
<img width="1917" height="807" alt="image" src="https://github.com/user-attachments/assets/ebc3cc6a-5242-41f5-b078-fe83dadd0a6d" />
<img width="1885" height="827" alt="image" src="https://github.com/user-attachments/assets/e430987c-7349-4a26-b163-6092a2b5deac" />







