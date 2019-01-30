# Keras implementation of CLARINET
CLARINET is an attention based neural network that predicts transcription factor-DNA binding from a given DNA sequence.
CLARINET is built upon keras implementation of DanQ*.
*Daniel Quang, Xiaohui Xie; DanQ: a hybrid convolutional and recurrent deep neural network for quantifying the function of DNA sequences, Nucleic Acids Research, Volume 44, Issue 11, 20 June 2016, Pages e107

![model image](overview.PNG)

  Overview of CLARINET

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

### Training CLARINET
`train.ipynb`

### Testing CLARINET
`test.ipynb`
