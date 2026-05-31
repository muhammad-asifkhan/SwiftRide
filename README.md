# SwiftRide Analytics

A Streamlit analytics dashboard for ride data, backed by SQLite. It explores ride
trends with interactive Plotly charts and trains a Random Forest model to predict
ride metrics (with R², MAE, and RMSE evaluation).

## Stack
Python · Streamlit · pandas · NumPy · Plotly · scikit-learn · SQLite

## Run
```bash
pip install streamlit pandas numpy plotly scikit-learn
python generate_data.py   # seed swiftride.db with sample data
streamlit run app.py
```
