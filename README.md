# Clostridium botulinum Group I cgMLST Schema

A standardized core genome multilocus sequence typing (cgMLST) scheme for
**Group I (proteolytic) *Clostridium botulinum***.

This repository provides the cgMLST schema developed for standardized
allele-based genomic comparison of Group I *C. botulinum*. The scheme was
constructed using **chewBBACA v3.5.4** and consists of **2,451 core-genome
loci**.

## Overview

The cgMLST scheme was developed using a collection of **469 quality-controlled
Group I *C. botulinum* genomes**, including:

- 123 RefSeq genomes
- 346 additional publicly available genome assemblies

An initial whole-genome gene-by-gene schema was generated from the 123 RefSeq
genomes. A species-specific Prodigal training file generated from
*C. botulinum* ATCC 3502 (GCA_000063585.1) was used for coding sequence
prediction.

Core-genome loci were defined as loci present in at least **95% of the
genomes**. After evaluation against all 469 genomes, **2,451 loci** were
retained in the final cgMLST scheme.

## Repository contents

The repository contains the files required for allele calling using the
Group I *C. botulinum* cgMLST scheme.

The schema is compatible with **chewBBACA** for gene-by-gene allele calling
and generation of cgMLST profiles.

## Scheme summary

| Feature | Description |
|---|---|
| Organism | *Clostridium botulinum* Group I |
| Typing method | cgMLST |
| Software | chewBBACA v3.5.4 |
| No. of genomes used | 469 |
| RefSeq genomes | 123 |
| Additional assemblies | 346 |
| Core-locus threshold | ≥95% genome presence |
| Final cgMLST loci | 2,451 |
| Reference genome for Prodigal training | ATCC 3502 (GCA_000063585.1) |

## Intended use

The scheme was developed to provide a standardized allele-based framework
for genomic comparison of Group I *C. botulinum* isolates.

Potential applications include:

- genomic surveillance;
- comparison of closely related isolates;
- molecular epidemiological investigations;
- comparison of genomic profiles across datasets and laboratories.

## Usage

The schema can be used with chewBBACA for allele calling.

General information and documentation for chewBBACA are available from the
official chewBBACA project.

Users should ensure that genome assemblies meet appropriate quality criteria
before allele calling and should interpret cgMLST genetic distances together
with relevant epidemiological information.

## Citation

A manuscript describing the development and evaluation of this cgMLST scheme
is currently in preparation.

If you use this schema before publication of the associated manuscript,
please cite this GitHub repository. Citation information for the corresponding
publication will be added once available.

## Availability

The cgMLST scheme is publicly available from:

https://github.com/hbucqp/clostridium_botulinum_cgMLST_schema

## Contact

For questions regarding the cgMLST scheme, please open an issue in this
repository.
