Our project's code is in two files: 
- Demo_NoiseModel.ipynb
- QAENoiseModelTests.nb
These files are placed inside the examples folder (so that they have access to all of the required QCompress dependencies).
All of the other files are part of the QCompress Project (https://github.com/hsim13372/QCompress) by Hannah Sim, which was used to help test our noise model simulation library.

(Demo_NoiseModel.ipynb):
This file contains our Noise Model Library. By running this notebook, the user will be able to train the autoencoder (qCompress), and then output a formula which encodes the noisy version of the circuit. The user must copy and paste this 'mathematica_str' into the Mathematica notebook in order to obtain the error analysis. This notebook also contains code from Hannah Sim's QCompress project which was used to test our Noise Model Library.  

(QAENoiseModelTests.nb):
The user must copy and paste the 'mathematica_str'into this notebook. Note the v1 string at the top of the notebook is just given as an example of a wave function input. Currently our notebook creates 3 graphs. The first graph results in a noiseless Cz graph, the second results in a noiseless Rx graph, and the last results in a noiseless Ry graph. The fixed parameters in these graphs can vary up to the user. 
