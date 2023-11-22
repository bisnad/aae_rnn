# Machine Learning for Movement Transformation #

Daniel Bisig - Instituto Stocos, Spain - daniel@stocos.com, Zurich University of the Arts, Switzerland - daniel.bisig@zhdk.ch

## Overview

This repository provides the source code to train a machine learning model on recorded dance movements in the form of motion capture  data. This model can be used to generate new variations of dance movements. The model is an autoencoder that is implemented using the Pytorch development framework. An autoencoder belongs to a class of models that encode and decode data into and from low dimensional representations. When trained on data in the form of motion capture recordings, these representations can be manipulated to obtain diverse and potentially original dance movements. 

Apart from source code, the repository also includes the weights of a model that was pretrained on two different motion capture recordings. The code has been tested on Windows and MacOS. Anaconda environments for these two operating systems are provided as part of this repository. 

For more information about the model's functioning and its potential use for choreography and live performance, see:

[Bisig, Daniel. "Granular Dance." In Ninth Conference on Computation,  Communication, Aesthetics & X, pp. 176-195. i2ADS, 2021.](https://www.researchgate.net/publication/353447100_Granular_Dance) 

[Bisig, Daniel, and Ephraim Wegner. "Puppeteering an AI-Interactive  Control of a Machine-Learning based Artificial Dancer." In Proceedings  of the XXIII conference on Generative Art. Rome, Italy, pp. 315-332. 2021.](https://www.researchgate.net/publication/360950859_Puppeteering_AI_-Interactive_Control_of_an_Artificial_Dancer) 