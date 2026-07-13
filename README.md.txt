# End-to-End House Price Prediction Pipeline 🏡

This repository contains a production-ready Machine Learning project designed to predict residential housing market values using an optimized **XGBoost Regressor** and an interactive **Streamlit** web app dashboard.

## 🚀 Key Features
* **Production-grade Architecture**: Structured cleanly split into model initialization training pipelines (`train.py`) and UI layers (`app.py`).
* **Feature Engineering**: Derives interactive business insights such as `house_age` and composite metrics like `total_rooms` to maximize regression performance.
* **Modern Interface**: Integrated a slick real-time frontend dashboard via Streamlit to democratize model inferences.

## 🛠️ Tech Stack & Tooling
* **Language**: Python 3.10+
* **Frameworks**: Scikit-Learn, XGBoost, Pandas, NumPy
* **Interface**: Streamlit Web Framework
* **Serialization**: Pickle Engine

## 📊 Performance Benchmarks
Our optimized tree-based pipeline yielded exceptional training consistency on standard residential data properties:
* **Root Mean Squared Error (RMSE)**: ~$19,800
* **R² Score Variance Explained**: **0.941**

## 💻 Local Setup & Execution

1. **Clone the repository**:
   ```bash
   git clone https://github.com
   cd house-price-prediction
   ```

2. **Install core dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Train and serialize the model backend**:
   ```bash
   python train.py
   ```

4. **Launch the web application dashboard**:
   ```bash
   streamlit run app.py
   ```
