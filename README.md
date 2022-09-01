# primer-assignment
This tool allows you to assign `n_primers` to `n_tcrs`*`n_replicates` (does not have to be TCRs). The goal is to have a unique primer combination for each to assess the efficiency of each primer. The output is 
1. A layout where each row and column is a primer number, and each number in this grid is a number of `n_tcrs`, this number is repeated `n_replicate` times.
2. A layout where each row is a number from the `n_tcrs` list, and `n_replicates` columns that contain sets of primers.
