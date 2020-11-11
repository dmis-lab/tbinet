# TBiNet: A deep neural network for predicting transcription factor binding sites using attention mechanism
TBiNet is an attention-based neural network that predicts transcription factor-DNA binding in a given DNA sequence.

Paper information: Park, S., Koh, Y., Jeon, H. et al. "Enhancing the interpretability of transcription factor binding site prediction using attention mechanism", Scientific Reports (2020).

- Overview of TBiNet
![model image](TBiNet_overview.png)

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

### Training TBiNet
`train.ipynb`

### Testing TBiNet
`test.ipynb`

## Contact information
For help or issues using TBiNet, please submit a GitHub issue. Please contact Sungjoon Park (sungjoonopark@korea.ac.kr) for communication related to TBiNet.
