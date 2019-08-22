Our project's code is in two files: 
- Demo_NoiseModel.ipynb
- QAENoiseModelTests.nb

These files are placed inside the examples folder (so that they have access to all of the required QCompress dependencies).
All of the other files are part of the QCompress Project (https://github.com/hsim13372/QCompress) by Hannah Sim, which was used to help test our noise model simulation library.

(Demo_NoiseModel.ipynb):
This file contains our Noise Model Library. By running this notebook, the user will be able to train an autoencoder (qCompress) and output a formula which encodes the noisy version of the autoencoder circuit. The user must then copy and paste this 'mathematica_str' into the Mathematica notebook in order to analyze the simulated error caused by the noise model. This notebook also contains code from Hannah Sim's QCompress project which was used to test our Noise Model Library.  

(QAENoiseModelTests.nb):
The user must copy and paste the 'mathematica_str'into this notebook. Note the v1 string at the top of the notebook is just given as an example of a wave function input. Currently, our notebook creates 3 graphs. The first graph results in a noiseless Cz gate graph, the second results in a noiseless Rx gate graph, and the last results in a noiseless Ry gate graph (in all graphs, one gate is noiseless while noise is simulated for the other two gates). The fixed parameters in these graphs can vary up to the user. 
