### Semi-Global Alignment  

This project implements a Semi-Global alignment algorithm for protein sequences using dynamic programming and the PAM250 scoring matrix. Matches and mismatches are scored based on the matrix, while gap penalties are fixed at 9. 

### Input and output formats  

The program takes two protein sequences as input and computes their semi-global alignment. The output starts with the alignment score, followed by all possible alignment combinations.

```
# input 

AAAAA
AA

# output

4
AAAAA
---AA
AAAAA
--AA-
AAAAA
-AA--
AAAAA
AA---
```
