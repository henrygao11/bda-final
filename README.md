# bda-final

## RUL Prediction with Random Forest Regression on CMAPSS FD004 dataset
- Piecewise RUL degeneration function with early RUL = 125
- Classification of operating conditions
- K-Means for fault modes target of the train set and SVM for fault modes classification of the test set
- Random forest regression for RUL prediction
- 2 baseline models:
  - RF regression with raw sensors' signal
  - Decision tree regression with the same feature engineering

## Fault Classification with SVM on CWRU dataset
- Wavelet packet decomposition for signal processing and energy for featuring engineering
- SVM for classification
