# GPT_2
## Overview
This project is aims to recreate the GPT-2, The transformer model is built using PyTorch, and the data preprocessing is handled with scikit-learn.

## Project Structure
```plaintext
car_price_prediction/
│
├── data/
│   └── data.csv                    # Original dataset
│
├── models/
│   ├── GPT_2.pth         	        # Saved GPT-2 model state dictionary
│   └── encoder.pkl              	  # Saved encoder (encoder for text)
│
├── src/
│   ├── train.py                    # Script for training the model
│   ├── predict.py                  # Script for making predictions
│   └── model.py                    # Model definition (PyTorch)
│
├── notebooks/
│   ├── GPT_2_Exploration.ipynb     # Jupyter notebook for GPT_2 structurt exploration 
│   └── GPT_2_Huggingface.ipynb	    # Jupyter notebook for Huggingface GPT_2 structurt exploration
│
└── README.md                       # Project overview and instructions
```
## Requirements

- Python 3.7+
- PyTorch
- scikit-learn
- pandas
- joblib (optional, for saving and loading scalers)
- Jupyter Notebook (optional, for data exploration)

You can install the necessary packages using the following command:

```bash
pip install torch scikit-learn pandas joblib
```
