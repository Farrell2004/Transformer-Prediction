# Weather Prediction with Transformer Model
📌 Overview
Prediksi cuaca di Jakarta menggunakan model Transformer untuk time series forecasting.

📊 Dataset
- Sumber: https://open-meteo.com/
- Periode: 2023–2024
- Fitur: suhu, kelembaban, curah hujan, kecepatan angin, dll.

🧠 Model
- Arsitektur: Transformer (Encoder-only)
- Framework: TensorFlow/Keras
- Metrik: MAE, RMSE, MAPE

🚀 Cara Menjalankan
1. Clone repositori
2. Install dependencies: `pip install -r requirements.txt`
3. Buka notebook: `jupyter notebook transformer-prediction-weather.ipynb`

📁 Struktur File
- `jakarta_weather_2023_2024.csv` : dataset mentah
- `weather_preprocessed.csv` : data setelah preprocessing
- `best_transformer.keras` : model terlatih
- `forecast_next_24_hours.csv` : prediksi 24 jam ke depan
- `transformer-prediction-weather.ipynb` : notebook utama

## 📜 Lisensi
MIT License
