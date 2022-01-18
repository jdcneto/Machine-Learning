# APLICAÇÃO DE APRENDIZAGEM DE MÁQUINA PARA CLASSIFICAÇÃO DE IMAGEM HIPERESPECTRAL NO DOMÍNIO ESPECTRAL.

## Description

The  aim to develop five supervisioned machine learning algorithms to classify the a hyperspectral image objects based on it's spectral reponse or espectral signature.

## Results

### Pavia Centre Scene dataset

Scene acquired by the ROSIS sensor during a flight campaign over Pavia, nothern Italy. The number of spectral bands is 102. The two figures show the it´s pseudocolor and groundtruth

<img src="figures/pavia.png"/> <img src="figures/pavia_gt.png"/> <img src="figure/UP-Pr.jpg"/> <img src="figure/UP_legend.jpg" width="200" height="100"/>

Fig.3  The UP dataset classification result (Overall Accuracy 99.99%) of Hybrid-SN using 30% samples for training. (a) False color image. (b) Ground truth labels. (c) Classification map. (d) Class legend.

### Results
The table sumarize the accuracy, f1-score and AUC for each method after a nested CV for hyperparamets optimization using GridSearchCV and 10-fold cross-validation
<img src="figures/results.JPG"/>
