# Insulin Conservation Study

## Overview

This project investigates the evolutionary conservation of insulin across vertebrate species commonly used in biological and diabetes research.

## Research Question

How conserved is insulin among different vertebrate species, and which organisms possess insulin proteins most similar to humans?

## Species Included

* Homo sapiens (Human)
* Mus musculus (Mouse)
* Rattus norvegicus (Rat)
* Sus scrofa (Pig)
* Bos taurus (Cow)
* Danio rerio (Zebrafish)

## Methods

### Sequence Retrieval

Protein sequences were obtained from the NCBI Protein database.

### Multiple Sequence Alignment

All insulin protein sequences were aligned using Clustal Omega.

### Pairwise Sequence Comparison

Pairwise alignments were performed using EMBOSS Needle to calculate sequence identity and similarity.

## Results

| Species   | Identity (%) |
| --------- | ------------ |
| Mouse     | 81.8         |
| Rat       | 82.7         |
| Pig       | 85.5         |
| Cow       | 80.0         |
| Zebrafish | 40.9         |

### Key Findings

* Pig insulin showed the highest similarity to human insulin.
* Mammalian insulin sequences displayed strong conservation.
* Zebrafish insulin was substantially more divergent.
* Critical cysteine residues involved in disulfide bond formation were conserved across species.

## Conclusion

Insulin is highly conserved across vertebrates, particularly among mammals. The conservation of critical functional residues suggests strong evolutionary pressure to maintain insulin structure and function.

## Skills Learned

* Sequence retrieval
* FASTA format
* Multiple Sequence Alignment
* Pairwise Alignment
* Evolutionary interpretation
* Scientific documentation

## Author

Dharmarajan Selvaraj

MSc Bioinformatics, REVA University




## Repository Structure

data/
- Raw insulin FASTA sequences

results/
- Multiple sequence alignment
- Pairwise alignment results

figures/
- Alignment screenshots

docs/
- Project report




## Future Work

This project focused on insulin sequence conservation across vertebrate species.

Future extensions could include:

* Construction of phylogenetic trees
* Structural comparison of insulin proteins
* Analysis of disease-associated insulin mutations
* Investigation of insulin receptor conservation
* Comparative analysis of other metabolic hormones

