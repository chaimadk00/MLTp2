# Machine Learning – Practical Session 2: Standardized PCA

National Higher School of Advanced Technologies – 2026/2027 

Name:dokkar chaima  Group:1


## Comparison of the numerical results

**Eigenvalues and explained variance**

| | Eigenvalue | Explained ratio | Cumulative |
|---|---|---|---|
| PC1 (scratch = sklearn) | 3.7397 | 93.49 % | 93.49 % |
| PC2 (scratch = sklearn) | 0.2402 | 6.01 % | 99.50 % |
| PC3 (scratch only) | 0.0191 | 0.48 % | 99.98 % |
| PC4 (scratch only) | 0.0009 | 0.02 % | 100.00 % |

**Coordinates of the students**

| Student | PC1 scratch | PC1 sklearn | PC2 scratch | PC2 sklearn |
|---|---|---|---|---|
| S1 | 0.3803 | -0.3803 | -0.6153 | -0.6153 |
| S2 | -1.2930 | 1.2930 | -0.2166 | -0.2166 |
| S3 | 2.6935 | -2.6935 | -0.2080 | -0.2080 |
| S4 | -2.6304 | 2.6304 | -0.1239 | -0.1239 |
| S5 | 1.5081 | -1.5081 | 0.4407 | 0.4407 |
| S6 | -0.6585 | 0.6585 | 0.7231 | 0.7231 |

Eigenvalues and explained variance are identical. The coordinates are identical except for the sign of PC1 (maximum difference after sign correction: about 1e-15).


