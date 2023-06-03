This directory contains benchmarks using non-linear integer arithmetic (subdirectories `*NIA`), and their overapproximations using linear integer arithmethic (`*LIA`) and non-linear real arithmetic (`*NRA`).
Each benchmark has two versions: one using datatypes (`QF_UFDT*`) and one not using datatypes (`QF_UF{NIA,LIA,NRA}`).

The overapproximation transformations guarantee that if the overapproximation is unsatisfiable, so was the original benchmark.
Therefore we only include overapproximations of benchmarks that were not proved satisfiable in either version of the original `*NIA` encoding.

These benchmarks were used for experiments in the paper [Overapproximation of Non-Linear Integer Arithmetic for Smart Contract Verification](https://easychair.org/publications/paper/BlrQ).
