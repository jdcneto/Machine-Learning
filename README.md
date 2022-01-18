# APLICAÇÃO DE APRENDIZAGEM DE MÁQUINA PARA CLASSIFICAÇÃO DE IMAGEM HIPERESPECTRAL NO DOMÍNIO ESPECTRAL.

## Description

The  aim to develop five supervisioned machine learning algorithms to classify the a hyperspectral image objects based on it's spectral reponse or espectral signature.

## Results

### Pavia Centre Scene dataset

Scene acquired by the ROSIS sensor during a flight campaign over Pavia, nothern Italy. The number of spectral bands is 102. The two figures show the it´s pseudocolor and groundtruth

<img src="figures/pavia.png" width="300" height="600"/> <img src="figures/pavia_gt.png" width="300" height="600"/> 

### Results
The table sumarize the accuracy, f1-score and AUC for each method after a nested CV for hyperparamets optimization using GridSearchCV and 10-fold cross-validation

<img src="figures/results.JPG"/>
