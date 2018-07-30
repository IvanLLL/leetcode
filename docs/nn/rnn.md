<script type="text/javascript" src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=default"></script>
### Recurrent Neural Network
主要特征：使用Hidden Unit to act as memories
主要用于：
1. Model Sequential Data;
2. Model invariance across time (CNN model invariance across space)


- RNN
- LSTM
- GRU


RNN 基本公式：

Equation(1):
$$h_{j}(t)=sigmoid(\sum_{s=0}^{d}w_{js}^{(1)}x_{s}(t)+\sum_{r=0}^{H}w_{jr}^{(R)}h_{r}(t-1)+b_{j})$$

Equation(2):
$$y_{k}(t)=softmax(\sum_{r=0}^{H}w_{kr}^{(2)}h_{r}(t)+b_{k})$$
