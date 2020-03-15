# LSTM-Stock-Prediction
LSTM和BP神经网络实现对股票开盘价的预测。  
其中BP神经网络的输入是前一天的开盘价、收盘价、最高价、最低价等特征，label为当日的开盘价。  
其中LSTM的输入是前五天（参数window=5）的开盘价开盘价、收盘价、最高价、最低价等特征，abel为当日的开盘价。  
从MAE和MSE看出LSTM的预测效果明显好于BP神经网络。  
****
BP NN:
![Image text](https://github.com/stxupengyu/LSTM-Stock-Prediction/blob/master/img-folder/3.png) 
![Image text](https://github.com/stxupengyu/LSTM-Stock-Prediction/blob/master/img-folder/4.png) 
LSTM:
![Image text](https://github.com/stxupengyu/LSTM-Stock-Prediction/blob/master/img-folder/1.png)  
![Image text](https://github.com/stxupengyu/LSTM-Stock-Prediction/blob/master/img-folder/2.png)  
****
