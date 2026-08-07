# ⚓ Multimodal Energy Risk & Hedging Engine (2026 Crisis Simulation Due TO Iran WAR)

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
