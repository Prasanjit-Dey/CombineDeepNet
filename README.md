# FuseDeepNet: A Deep Network for Multi-Step Prediction of Near-Surface PM<sub>2.5</sub> Concentration

With the spirit of reproducible research, this repository contains all the codes required to produce the results in the manuscript:

>Prasanjit Dey, Soumyabrata Dev, Bianca Schoen Phelan (2023) "FuseDeepNet: A Deep Network for Multi-Step Prediction of Near-Surface PM<sub>2.5</sub> Concentration" under review in IEEE journal of selected topics in applied earth observations and remote sensing.

### Executive Summary:
Elevated air pollutants concentrations have shown to have a significant impact on human health, ecosystem. In this work, In this paper, we investigate recent deep learning approaches for predicting PM<sub>2.5</sub> concentration at multiple sites using three metrics: root mean square error (RMSE), mean absolute error (MAE), and correlated coefficient (R<sup>2</sup>). In this research we used dataset from six monitoring sattion: Aoti Zhongxin, Dongsi, Shunyicheng, Tiantan, Haidan Wanliu, and Wanshou Xigong from China between March 1, 2013, and February 28, 2017.

### Dataset:
In this study, we looked at pollution data from six monitoring stations in China: Aoti Zhongxin, Dongsi, Shunyicheng, Tiantan, Haidan Wanliu, and Wanshou Xigong. This data contains 12 pollution levels and meteorological parameters. In the folder "datasets," you can find all the datasets.

### Code:
All codes are written in `python3`.

+ `BiLSTM_BiGRU.ipynb`: This file contains the code for the proposed FuseDeepNet model along with model evaluation using three matrixes: RMSE, MAE, and R<sup>2</sup>.
+ Simliarly file `CNN.ipynb`, `LSTM.ipynb`, `GRU.ipynb`, `CNN_LSTM.ipynb`, and 'CNN_GRU.ipynb' contains the code for other five state-of-the-art models like CNN, LSTM, GRU, CNN-LSTM, and CNN-GRU.
+ `Scatter_plot.ipynb`: This file contains the code for degree of fit between the actual and predicted values of the proposed model.
