# PELT algorithm - Python implementation

Implementation of PELT algorithm as described here: https://arxiv.org/pdf/1101.1438.pdf

PELT is based on OP algorithm but it includes a pruning system in order to reduce the algorithm complexity.

OP has a complexity O(n^2).

PELt has a linear complexity, because of the pruning.

## There are three functions in the module:

pelt(): Return a vector with the optimal changepoints.

backtracking(): Return the segments to plot, based on a vector built by op().

plot_segments(): Compute the mean of each segment and plot them.
