## Understanding_Sectral_Inference
This is a workflow to recreate and understand Doran et al 2024's method called Spectral Inference. 

(https://doi.org/10.1101/2023.12.04.569969)

This contains the following:
### 1. Construction of Dataset
  Some random mutation of a sequence at random spots in the "genes" creates different "species.
  Of course, all of this can be done with a real dataset

## 2. Singular Value Decomposition
  SVD decomposition is performed and we show that it is lossless (This we know to be true, this is just a demonstration). We can reconstruct the original dataset using the U, S, and V matrices.

## 3. Partition of singular values:
 This is done with respect to the median drop in subsequent singular values

## 4. Distance calculation within each partition and final distance summation:
  This gives us a distance matrix between the species.

## 5. Phylogenetic Tree Construction
Finally, a Phylogenetic tree based on this distance matric is created:

## 6. Then we verify this against Doran et al's code.
 (Link to the paper: https://doi.org/10.1101/2023.12.04.569969)
