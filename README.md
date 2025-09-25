# Energy Prediction Project

## Overview
This project aims to predict energy consumption using a Long Short-Term Memory (LSTM) model. The model is trained on synthetic energy consumption data to forecast future energy usage. The project includes data preprocessing, model training, and visualization of the predictions.

## Project Structure
```
energy-prediction-project
├── data
│   └── energy_consumption.csv       # Synthetic energy consumption data
├── notebooks
│   └── LSTM Energy Prediction.ipynb  # Jupyter notebook for model implementation
├── requirements.txt                  # Python dependencies
└── README.md                          # Project documentation
```

## Setup Instructions
1. Clone the repository:
   ```
   git clone <repository-url>
   cd energy-prediction-project
   ```

2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

## Usage Guidelines
1. Open the Jupyter notebook `LSTM Energy Prediction.ipynb` in the `notebooks` directory.
2. Run the cells sequentially to preprocess the data, train the LSTM model, and visualize the predictions.
3. Ensure that the `data/energy_consumption.csv` file is present in the specified directory for the notebook to function correctly.

## License
This project is licensed under the MIT License.