Algotithm:

- Mean normalize the data
- Compute [[Covariance Matrix]]
- Compute [[Singular value decomposition]] which returns:
	- $U$: labelled with [[eigenvector]]
	- $S$: labelled with [[eigenvalue]]
	- $V$
- We obtain PCA of $n$ dimensions by doing $XU[:,0:n]$