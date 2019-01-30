# Keras implementation of CLARINET.
CLARINET is an attention based neural network that predicts transcription factor-DNA binding from a given DNA sequence.

![model image](CLARINET_fig.PNG)

  Overview of CLARINET

## Requirements
- python (version 3.6.6)
- numpy (version 1.14.6)
- h5py (version 2.8.0)
- scipy (version 1.1.0)
- sklearn (version 0.20.1)
- theano (version 1.0.3)
- keras (version 2.2.4, backend:theano)

## Usage
### Data
The ChIP-seq data used in this work can be downloaded from <http://deepsea.princeton.edu/media/code/deepsea_train_bundle.v0.9.tar.gz>.

### Training CLARINET
`CLARINET.ipynb`

### Testing CLARINET
`CLARINET-test.ipynb`
