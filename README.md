# Skyscraper: Fast Hashing on Big Primes

This repository contains a Sage reference implementation for the $\textsf{Skyscraper}$ permutation.

Files:
- [skyscraper.sage](skyscraper.sage): Sage implementation of $\textsf{Skyscraper} : \mathbb F_{p^n}^2 \to \mathbb F_{p^n}^2$.
- [Skyscraper.ipynb](Skyscraper.ipynb): Example usage of `skyscraper.sage` (with debug output) for $n \in \{1,2,3\}$. Chosen exampels correspond to the ones presented in the paper (Table 3).
- [SkyscraperTestvectors.ipynb](SkyscraperTestvectors.ipynb): Test vectors hashing zero inputs and random inputs for a selection of primes and extensions $\mathbb F_{p^n}$ with $n = 1,2,3$
