# 🔆 Forecasting Energy Surplus Using Machine Learning
**Project for CE888-7-SP: Data Science and Decision Making**

## 📌 Project Overview
This project aims to **predict energy surplus from solar power** in Brighton to provide **free energy slots** to customers.  
The system forecasts energy production **24 hours in advance** to optimize renewable energy usage and reduce wastage.

## 📊 Data Used
- **Historical weather and energy data** (Brighton, 2010–2023)
- **Key variables**: Solar energy, temperature, wind speed, humidity, etc.
- **Missing values handled using**: Polynomial interpolation

## 🔬 Methodology
1. **Data Preprocessing**:
   - Merging multiple CSV files
   - Handling missing values
   - Feature extraction (solar energy trends)
2. **Model Training**:
   - **Baseline Model**: Previous year's data
   - **SARIMA Model**: Statistical forecasting
   - **LSTM Neural Network**: Deep learning for time-series prediction
3. **Performance Metrics**:
   - **Mean Absolute Error (MAE)**: Measures prediction accuracy
   - **R² Score**: Evaluates model performance over time

## 📈 Results
- **LSTM Model Performance**:
  - **Solar Energy Prediction MAE**: **0.19** (Best Performance)
  - **Highest prediction reliability** in **May, June, and September**
- **SARIMA vs. LSTM Comparison**:
  - LSTM **outperformed** both **SARIMA** and **baseline models**
- **Economic Impact of False Positives**:
  - Incorrect surplus predictions **cost £92,576.63 per year**

## 📂 Files Included
- 📜 **Assignment_1.ipynb** – Jupyter Notebook with full project code
- 📊 **brighton_###.csv** – CSV files containing historical weather data
- 📄 **Project_Energy.pptx** – Project presentation
- 📝 **feedback.xlsx** – Professor's feedback on the project

## 🚀 How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/Perfect-Human007/Data-Science-and-Decision-Making.git
Navigate to the project folder
cd Data-Science-and-Decision-Making/Forecasting-Energy-Surplus
Install dependencies:
pip install pandas matplotlib seaborn tensorflow
Open the Jupyter Notebook
jupyter notebook Assignment_1.ipynb
🔮 Future Work
Extend the model to include wind energy predictions
Deploy the model as an API for real-time forecasting
Optimize predictions for cost-effective energy distribution
🧑‍💻 Author
Name: Abu Junaeid Shoaib
Supervisor: Dr. Ana Matran-Fernandez
Institution: University of Essex
