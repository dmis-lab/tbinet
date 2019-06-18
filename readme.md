# CABiNet: A deep neural network for predicting transcription factor binding sites using attention mechanism
CABiNet is an attention-based neural network that predicts transcription factor-DNA binding in a given DNA sequence.

- Overview of CABiNet
![model image](cabinet_overview.PNG)

## Requirements
- Python (version 3.6.6, recommend installing Anaconda3)
- Numpy (version 1.14.6)
- H5py (version 2.8.0)
- Scipy (version 1.1.0)
- Sklearn (version 0.20.1)
- Theano (version 1.0.3)
- Keras (version 2.2.4, backend:theano)

## Usage
### Data
The ChIP-seq data used in this work can be downloaded from <http://deepsea.princeton.edu/media/code/deepsea_train_bundle.v0.9.tar.gz>.

### Training CABiNet
`train.ipynb`

### Testing CABiNet
`test.ipynb`

