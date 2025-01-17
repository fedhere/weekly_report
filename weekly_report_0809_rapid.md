# Xiaolong - Week of 08/09/2019

## 1. Papers and code

### 1.1 Papers Read

[RAPID](https://arxiv.org/abs/1904.00014): This article present the RAPID, a light curve classification tool able to identify transients from time series infomation. It use the simulated PLAsTicc datasets to train a recurrent neural network model.

### 1.2 Code Written

[rapid.ipynb](https://github.com/xiaolng/weekly_report/blob/master/source/rapid.ipynb): Explore the PLAsTicc dataset and learn to use RAPID to classify light curves.


## 2. Figures

![](https://github.com/xiaolng/weekly_report/blob/master/imgs/0809_rapid_2.png?raw=true)

Figure 1: Architecture of RNN used in RAPID. It includes two GRU layers and 1 FC layer. 

![](https://github.com/xiaolng/weekly_report/blob/master/imgs/0809_rapid_1.png?raw=true)

Figure 2: An example of light curve and the softmax classification probabilities. Created by [rapid.ipynb](https://github.com/xiaolng/weekly_report/blob/master/source/rapid.ipynb).

### 3. Results

I explored the simulated PLAsTicc dataset. PLAsTicc contains the train set (7,848 objects) and test set (3,492,892 objects). Also I learned to use the RAPID which is able to classify transients using RNN. 

