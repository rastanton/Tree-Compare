# Tree-Compare
Executable R script to determine P-value of similarity between two trees using treespace library.
Usage:
> Tree_Compare.R -q <query> -s <subject> -n <ncomparisons> -o <output>
Defaults:
  -n: 10,000 random trees for comparison
  -o: Tree_Compare.txt
Output:
Tab-delimited text file with 7 columns (query tree, subject tree, similarity score, average similarity score of n random trees to the query tree, P-value of Q-S similarity versus query mean, average similarity score of n random trees to the subject tree, P-value of Q-S similarity versus subject mean).
