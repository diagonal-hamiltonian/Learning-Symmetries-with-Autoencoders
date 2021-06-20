# Learning Symmetries with Machine Learning
My final year project in theoretical physics is titled 'Learning Symmetries with Machine Learning'. To explore the (suprisingly difficult) problem, I use a toy model and try of teach an autoencoder to learn features of a triangular molecule in 3D space. Euclidean symmetries are explored and understood in basic shallow NNs, and I shed some light on why NNs struggle dealing with euclidean coordinates. I include the full report in the pdf titled 'writeup', and to give a breif overview of what the thesis entails I leave you with the abstract.


## Abstract
Machine learning methods (MLMs) [1] are rapidly becoming an alternative means of describing chemical environments. Choosing the representation of the geometric data used is an important design decision for MLMs and for physical systems,invariant representations that respect symmetry are desired. Current work achieves this using atomic descriptors [2], however questions have been raised on the completeness of this representation [3]. This thesis has investigated how neural networks (NNs) can extract invariant representations and has explored ways NNs adapt to symmetries of Euclidean coordinates. To learn invariant representations, a custom loss function based on the distance between points was introduced and invariant representations of Euclidean triangles were successfully produced. The extracted representations were found to outperform Euclidean representations in predicting the Leonard-Jones potential for a toy triangular molecule. Constrained representations of triangles with symmetries were extracted and investigated. Future work was discussed, and a new model was proposed.

