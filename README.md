# Learning Symmetries with Autoencoders
My final year project in theoretical physics is titled 'Learning Symmetries with Machine Learning', and in this repo I will be dealing with the (suprisingly difficult) problem of teaching the autoencoder to learn features of a triangular molecule in 3D space.

Neural networks in chemical physics struggle with the representation of coordinates in space [see arXiv:2001.11696v2]. The reason for this stems from the NN not knowing that the physics of a molecule is invarient under rotation/translation of the positions of the coordinates, ie: the physics of a H_2 molecule in a certain referance frame is the same as the physics of the molecule in the same reference frame upside down.

For this model I am dealing with a dataset consisting of 3 random points represented by 
- <img src="https://latex.codecogs.com/gif.latex?\vec{r_{1}} = " /> 

## First attempt - Autoencoder_triangle_1.ipynb

