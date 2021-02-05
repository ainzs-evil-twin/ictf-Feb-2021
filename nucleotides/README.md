# nucleotides

## Description

**Nucleotides** are the subunits which make up the DNA. The 4 kinds of nucleotides in the DNA are distinguished by their nitrogen heterocycle substituents: **adenine(A), cytosine(C), guanine(G), and thymine(T)**.  

## Problem

In a parallel universe, the DNA is composed of 8 kinds of nucleotides instead of 4: **A, C, G, K, M, R, T, and U**. Find out how many unique strands of length 8 (may contain repeated nucleotides) are possible in this universe. Also, find the 250th strand (counting starts from 1) in this set, after this set is sorted alphabetically.  

## Flag format

`ictf{[0-9]+_[A, C, G, K, M, R, T, U]{8}}`  

i.e. `ictf{` followed by `total number of possible strands of length 8` followed by an `underscore` followed by `250th strand in this set` followed by `}`  
An example would be `ictf{256216_TUKCCAGG}`  

## Example

If the allowed number of nucleotides was only 4 (A, C, G, and T) and we were asked to find all possible strands of length 4, we would get a set containing these strings:  
```
 AAAA,  
 AAAC,  
 AAAG,  
 AAAT,  
 AACA,  
 AACC,  
 AACG,  
 AACT,  
 AAGA,  
 AAGC,  
 AAGG,  
 AAGT,  
 AATA,  
 AATC,  
 AATG,  
 AATT,  
 ACAA,  
 ACAC,  
 ACAG,  
 ACAT,  
  ...  
 TTTA,  
 TTTC,  
 TTTG,  
 TTTT  
```

The total number of strings in this set would be 256 with 250th position taken by `TTGC`, resulting in the flag: `ictf{256_TTGC}`

## Attachments
 
https://github.com/ainzs-evil-twin/ictf-Feb-2021/blob/main/nucleotides/README.md

## Category

Misc (Programming)
