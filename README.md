# psysoc-importance-hf
Python code (in Jupyter notebooks/NBs with sample outputs) to reproduce results in article.

The data-processing NB shows how the data was randomly split in 3 datasets: training, validation and testing.

The ML-permutations NB shows how these sets were used to first train the ML models (decision tree, random forest, adaboost), and then how the validation and test sets were used to determine the permutation importances of the input variables.

The article only shows the permutation importances based on the test set. The permutation importances on the validation set is provided only for completeness.

The data is not publicly available, and so the lines related to the reading and writing of the files will have to be adapted accordingly.
