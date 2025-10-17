# Deep_Learning

## Optimizer Comparison
Compare SGD, Adagrad, RMSprop, Adam, Adadelta optimizers

## GAN - MNIST
Python program to implement a generative adversarial network using pytorch which generates handwritten digits using mnist dataset.

## Dimensionality Reduction - t-SNE, LLE, UMAP, ISOmap 
Consider a high dim dataset.  
Perform dimensionality reduction using t-SNE, LLE, UMAP, and ISOmap to reduce the data to 2D.   
Visualize the resulting 2D embeddings from each method.

## RBM - Restricted Boltzmann Machine
Implement a simple RBM with binary visible and hidden units.  
Train the RBM on a small dataset such as binarized MNIST or toy(?) dataset.   
Visualize the learned weights (filters) of the RBM after training.  
Use the trained RBM to reconstruct input data and compute the reconstruction error.   
How does this error change as training progresses..?

## Compare PCA, Metric MDS and non metric MDS
Apply all 3 on the wine dataset (13 dim features)   
Plot the 2D embeddings side by side and compare - which method shows clearer separation of clusters and why..?    
### Stress Function Analysis
For the non metric MDS on the Iris dataset, plot the stress value vs number of dimensions.  
Why does stress decrease as dim increases..?
