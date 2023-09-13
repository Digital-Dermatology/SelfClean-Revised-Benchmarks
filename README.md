# Revised Benchmarks using SelfClean

<p align="center">
  <img  src="http://fabiangroeger.com/wp-content/uploads/2023/09/SelfClean_Teaser_Image.png">
</p>

This repository contains revised versions of benchmark datasets created using the SelfClean data cleaning protocol and expert annotators.
These revised file lists should be used for model evaluation and pave the way for more trustworthy performance assessment across domains. 

## Dermatology

The expert-confirmed data quality issues found in six dermatology benchmarks for all three noise types obtained by unanimous expert agreement.

| Dataset | Size  | Irrelevant Samples | Near Duplicates | Label Errors |
| :---: | :---: | :---: | :---: | :---: | 
| MED-NODE | 170  | 3 (1.8%) | 1 (0.6%) | 2 (1.2%) |
| PH2 | 200 | 0 (0.0%) | 0 (0.0%) | 0 (0.0%) |
| DDI | 656 | 3 (0.5%) | 6 (0.9%) | 8 (1.2%) |
| Derm7pt | 2,022 | 1 (0.1%) | 9 (0.5%) | 2 (0.1%) |
| PAD-UFES-20 | 2,298 | 2 (0.1%) | 56 (2.4%) | 3 (0.1%) |
| SD-128 | 5,619 | 3 (0.1%) | 156 (2.8%) | 4 (0.1%) |

## References

Please cite the following work if you find this repository useful for your research or use one of the revised file lists.

```bib
@misc{groger_selfclean_2023,
  title        = {{SelfClean}: {A} {Self}-{Supervised} {Data} {Cleaning} {Strategy}},
  shorttitle   = {{SelfClean}},
  author       = {Gröger, Fabian and Lionetti, Simone and Gottfrois, Philippe and Gonzalez-Jimenez, Alvaro and Amruthalingam, Ludovic and Consortium, Labelling and Groh, Matthew and Navarini, Alexander A. and Pouly, Marc},
  year         = 2023,
}
```