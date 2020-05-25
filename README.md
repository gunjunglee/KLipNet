# KLipNet
=======================
### LipNet: End-to-End Sentence-level Lipreading
Keras implementation of the method described in the paper 'LipNet: End-to-End Sentence-level Lipreading' by Yannis M. Assael, Brendan Shillingford, Shimon Whiteson, and Nando de Freitas (https://arxiv.org/abs/1611.01599).


## Dependencies
Keras 2.0+
Tensorflow 1.0+
PIP (for package installation)
Plus several other libraries listed on setup.py

## Usage
To use the model, first you need to clone the repository:

git clone https://github.com/rizkiarm/LipNet
Then you can install the package:

cd LipNet/
pip install -e .
Note: if you don't want to use CUDA, you need to edit the setup.py and change tensorflow-gpu to tensorflow

You're done!

Here is some ideas on what you can do next:

Modify the package and make some improvements to it.
Train the model using predefined training scenarios.
Make your own training scenarios.
Use pre-trained weights to do lipreading.
Go crazy and experiment on other dataset! by changing some hyperparameters or modify the model.

## Dataset
This model uses GRID corpus (http://spandh.dcs.shef.ac.uk/gridcorpus/)
준비중

### Pre-trained weights
For those of you who are having difficulties in training the model (or just want to see the end results), you can download and use the weights provided here: https://github.com/rizkiarm/LipNet/tree/master/evaluation/models.

More detail on saving and loading weights can be found in Keras FAQ.
