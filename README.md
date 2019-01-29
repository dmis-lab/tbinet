# CLARINET

![model image](CLARINET_fig.PNG)

This code is implementation of our paper [CLARINET].  
CLARINET is an attention based deep learning model that predicts whether a TF binds to a given DNA sequence.  
CLARINET takes DNA sequence as one-hot vector and predicts 690 TF binding tasks.  
The above picture is an overview of our model.  


## Requirements
- pytorch
- keras

## Usage
### Training model
0. Download data (<http://deepsea.princeton.edu/media/code/deepsea_train_bundle.v0.9.tar.gz>)  
    - Data includes `train.mat`, `valid.mat`, and `test.mat`
    - Place that data at the `./data` folder
1. Train model and save trained model to ./model folder  
    - `python clarinet.py train ./data ./model/[model_name]`
2. Evaluate trained model
    - `python clarinet.py eval ./data ./model/[model_name]`
### Attention analysis
`python attn/analysis.py [] []`
### SNP prioritization
`python snp/analysis.py [] []`
## Result
### Model prediction result
ROC AUC scatter plot

### Attention analysis result
Heatmap plot

### SNP prioritization result
ROC AUC plot
