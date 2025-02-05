# ADNOC Project - Predictive Model for Average Price

## Overview
This project builds a predictive model for estimating the average price using machine learning techniques. It leverages deep learning frameworks such as **Keras** along with data preprocessing tools from **Scikit-learn** and visualization libraries like **Seaborn** and **Matplotlib**.

## Features
- Data preprocessing using **Pandas** and **Scikit-learn**
- Feature scaling with **MinMaxScaler**
- Machine learning model implemented using **Keras (Sequential Model)**
- Model evaluation using **Mean Squared Error (MSE)**
- Data visualization with **Seaborn** and **Matplotlib**

## Technologies Used
- Python
- Keras
- Scikit-learn
- Pandas
- Matplotlib
- Seaborn
- NumPy

## Installation
To set up this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/adnoc-predictive-model.git
   cd adnoc-predictive-model
   ```

2. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Load and preprocess the dataset.
2. Split data into training and testing sets.
3. Train the model using Keras Sequential API.
4. Evaluate model performance using Mean Squared Error (MSE).
5. Visualize results with Seaborn and Matplotlib.

To run the Jupyter Notebook:
```bash
jupyter notebook ADNOC_Project.ipynb
```

## Dataset
Ensure that your dataset is properly formatted as a CSV file before running the notebook. The dataset should include relevant features required for predicting the average price.

## Acknowledgments
- Inspired by predictive analytics in the oil and gas industry.
- Special thanks to open-source contributors and the ML community!
