GHKNN
The identification of protein-nucleotide binding
residues is crucial for the annotation of protein functions and
the design of structure-based drugs. Traditional experimental
methods to identify protein-nucleotide binding residues are timeconsuming
and expensive. Therefore, many computational methods
have emerged to effectively solve this problem during the past
decade. Recently, many methods have been used to build models
based on structure information, but this approach is flawed
because the 3D structure information of some proteins is insufficient
and unavailable. Therefore, sequence-based computational
methods are easier to implement for protein-nucleotide binding
residue identification. In this paper, we use protein sequences
to develop a novel computational method to identify proteinnucleotide
binding residues. We apply sliding window and Discrete
Cosine Transform (DCT) to extract features and compress
features of Position-Specific Score Matrix (PSSM). In addition,
we also apply Predicted Relative Solvent Accessibility (PRSA)
to further improve performance. The predictor of proteinnucleotide
binding residues is constructed by Graph Regularized
k-local Hyperplane Distance Nearest Neighbor (GHKNN). To
evaluate our method, we test it on five independent test sets.
Compared with other advanced methods, our method achieves
Mathews correlation coefficient (MCC) of 0.537 (ATP), 0.514
(ADP), 0.396 (AMP), 0.610 (GDP) and 0.687 (GTP), respectively.
The above independent test set results show that our
method is feasible and effective for the identification of proteinnucleotide
binding residues. Our data and code are available at
https://github.com/guofei-tju/GHKNN.
[DATA](http://yhpjc.vip/download/GHKNN/)
