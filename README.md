# Stock Prediction

## Project Overview
This project aims to predict stock prices using Long Short-Term Memory (LSTM) neural networks. LSTM networks are well-suited for time-series forecasting tasks like stock price prediction due to their ability to capture long-term dependencies in sequential data.

## Technologies Used
* **Python:** Core programming language.
* **Keras/TensorFlow:** For building and training the Siamese network.
* **OpenCV:** For face detection and preprocessing.
* **NumPy/Pandas:** Data manipulation and handling.
* **Matplotlib:** Visualization of loss curves and training progress.

## Project Structure
```
.
├── dataset/                # CSV files for NIFTY50 dataset
│   ├── stock1.csv
│   ├── stock2.csv
│   └── ...
├── models/                 # Trained model weights
├── Model.ipynb             # Jupyter Notebook for model
├── requirements.txt        # Python dependencies
└── README.md               # Project documentation
```

## Installation
1. **Clone Repository**
   ```
   git clone https://github.com/Blaze-DSP/Stock-Prediction.git
   cd Stock-Prediction
   ```
2. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

## Dataset
The dataset used for training and evaluation consists of historical stock prices of the NIFTY-50 stocks. This dataset is used for training the LSTM network with Mean-Squrared Loss for stock prediction.

## Usage
**Prediction & Inference:** Provide instructions on how to use the trained model for making predictions.

## Future Enhancements
**Enhancements:** List potential improvements or optimizations that could be implemented to enhance the model's performance.
**Extensions:** Discuss possible extensions to the current project, such as integrating with real-time data sources or applying ensemble techniques.
