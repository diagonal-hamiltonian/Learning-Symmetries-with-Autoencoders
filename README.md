# Learning Symmetries with Autoencoders
My final year project in theoretical physics is titled 'Learning Symmetries with Machine Learning'. This is the starting point of my thesis, and I will be dealing with the (suprisingly difficult) problem of teaching an autoencoder to learn features of a triangular molecule in 3D space.

Neural networks struggle with understanding symmetries representation of coordinates in space [see arXiv:2001.11696v2]. The reason for this stems from the NN not knowing that the physics of a molecule is invarient under rotation/translation of the positions of the coordinates, ie: the physics of a H_2 molecule in a certain referance frame is the same as the physics of the molecule in the same reference frame upside down. For instance in the context of this problem, given the two identical triangles below, the model should consider them the same.

![alt text](https://github.com/diagonal-hamiltonian/Learning-Symmetries-with-Autoencoders/blob/main/images/two_triangles.png)

For this model I am dealing with a dataset consisting of 3 random points represented by 
<p align="center">
   <img src="https://latex.codecogs.com/gif.latex?\vec{r_{1}}=(x_{1},y_{1},z_{1})" />, 
   <img src="https://latex.codecogs.com/gif.latex?\vec{r_{2}}=(x_{2},y_{2},z_{2})" />, 
   <img src="https://latex.codecogs.com/gif.latex?\vec{r_{3}}=(x_{2},y_{2},z_{3})" />,
</p>
for a total of 9 coordinates representing the triangle. Ideally our model should be able to learn the features (side lenghts, angles,...) that represent what the triangle 'actually' is and it can forget useless information such as the exact coordinates. 


## First attempt - Autoencoder_triangle_1.ipynb
In this notebook I experiment with reducing the latent space size of the autoencoder down from 9 in order to try condense the features in a smaller latent space. 
