# Stock Market Prediction Using a Diverse Set of Variables 📈

Accurately predicting the future behaviours of stock markets would be extremely valuable for traders. However, the task is challenging, as financial markets can be dynamic, non-stationary, and noisy. Above all, the *efficient market hypothesis* states that current stock prices reflect all available knowledge, indicating the futility of using past historical data and financial new to forecast the future prices of stocks.

In this project, we exhaustively investigates the performance of various machine learning algorithms, including standard, ensemble, and neural networks, for predicting the daily movement of stock markets conditioned on historical data of diverse market-specific, general economic and other relevant financial variables. We focus on predicting the next day’s direction of movements for the indices of DJI, NASDAQ, NYSE, RUSSELL 2000, and S&P 500 markets. Our best model – fine-tuned 2D CNNpred achieved higher accuracy and macro-average F1 than existing methods.

## Requirements:
- Python 3.6+
- numpy
- scipy
- pandas
- matplotlib
- seaborn
- TensorFlow 2.0
- Scikit-learn 
- plotly

### scripts and notebooks
- jupyter
- tqdm

## Folder Structure:
- *report.pdf*: our report describing the methods and results.
- *Datasets*: contains the shell dataset
- *Utilities.ipynb*: contains utility codes; various classes and functions shared in the experiments.
- *Data Exploration.ipynb*: contains standard and time-series exploratory data analysis.
- *Dimensionality Reduction.ipynb*: contains dimensionality reduction analysis, whether applying t-SNE and PCA help to make a robust model for predicting trend of stock market.
- *Standard ML Analysis.ipynb*: experimentation results using standard machine learning models (e.g., logistic regression, SVC, k-NN, decision tree).
- *Ensemble ML Analysis.ipynb*: experimentation results using ensemble machine learning models (e.g., voting, stacking, bagging, pasting, random forest).
- *Neural Network Analysis.ipynb*: experimentation results using neural networks (e.g., feedforward neural network, 2D-CNNpred, 3D-CNNpred, and LSTM-based networks).
- *Evaluation.ipynb*: further evaluation using best models.

 ## Author:
- Maleakhi Wijaya: maw219@cam.ac.uk

## Acknowledgements:
- The stock dataset is provided by [Hoseinzade and Haratizadeh (2019)](https://www.sciencedirect.com/science/article/pii/S0957417419301915).
- The 2D- and 3D-CNNpred evaluated were proposed by Hoseinzade and Haratizadeh (2019).