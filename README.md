# AMP-for-mismatched-matrix-estimation

The scripts implements the AMP for the mismatched estimation, for two cases of the true prior of generated vector: Gaussian, and Bernoulli-Rademacher.

The algorithm is based on the equations derived in https://arxiv.org/pdf/2107.08927, which is the scenario in which the statitician assumes a Gaussian prior with mismatched variance.

The performance of AMP is compared with the prediction of state evolution (SE). The mean squared error (MSE) of the AMP estimate is also compared with the best possible minimum MSE (MMSE).
