# variable-length-image-classification-lstm

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1NvZ5tlnsmRtUoHu6HIM7UbkgpalC8YYQ?usp=sharing)

Using recurrent neural nets (RNNs) for a slightly non-standard application: image classification, because it will be capable of handling variable length input ie. you could just input 1/5th of the image and the model would still provide accurate classifications.

The architecture is an RNN with an LSTM cell, including an input layer, an LSTM layer, and a fully connected layer. It takes input data and produces the final output. 

