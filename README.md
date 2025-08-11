🛫 Flight Delays Prediction Using Machine Learning

A deep learning project that proactively predicts flight delays by analyzing historical flight and weather data. Leveraging Recurrent Neural Networks (RNNs), this system learns complex temporal patterns and flight characteristics to forecast delays before they occur, helping airlines and passengers reduce disruption.

📌 Project Overview
This repository demonstrates how to predict flight delays by modeling sequences of past flights and environmental factors. The RNN model ingests data such as carrier code, origin/destination airports, scheduled times, flight distances, and weather conditions to estimate the probability or severity of delays.
.
✨ Innovation and Impact
Proactive Prediction: Unlike traditional reactive airline systems, this project forecasts delays ahead of time using advanced RNN architectures (including LSTM).

Large-scale Data: Trained on a dataset of 1.93 million US flights combined with rich weather and airport metadata.

Open Source: The full code, trained models, and documentation are publicly available to support further research and practical adoption.

Evaluation: Demonstrated strong predictive performance with classification metrics (accuracy, precision, recall, F1-score) and regression (MSE), enabling more reliable operational planning.

⚙️ Installation & Setup

Clone the repository:

git clone https://github.com/tarunabagh19/flightdelays_machine-learning.git
cd flightdelays_machine-learning

Set up a Python virtual environment and install dependencies:
python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install --upgrade pip
pip install numpy pandas scikit-learn matplotlib seaborn

🧭 Workflow Overview
Data Preparation: Clean, merge, encode, and normalize flight and weather features including delay histories.

Model Training: Train RNN models using provided scripts and Jupyter notebooks.

Evaluation: Analyze model results with detailed metrics and visualizations like confusion matrices and ROC/F1 curves.

Prediction: Use trained models to forecast delays for upcoming flights.


✨ Main Features
Temporal Sequence Modeling: Captures delay patterns over time with RNNs.

Feature Engineering: Uses flight and weather data such as airline, airports, schedule, distance, and delay history.

Evaluation: Supports classification or regression with metrics like accuracy, precision, recall, F1-score, or mean squared error.

🔗 References & Resources
Dataset: Historical US flight data & weather info.

Research inspiration: Use of RNN/LSTM models for time series forecasting.
