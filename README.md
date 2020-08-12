# supplementary-Rhamnaceae
This repository contains supplementary materials relating to the manuscript "Comprehensive mass spectrometry‐guided phenotyping of plant specialized metabolites reveals metabolic diversity in the cosmopolitan plant family Rhamnaceae".

The data analysis workflow described in this paper is now available through a [MolNetEhnacer module in GNPS web platform](https://gnps.ucsd.edu/ProteoSAFe/index.jsp?params=%7B%22workflow%22:%22MOLNETENHANCER%22%7D). Relevant information can be found in [Metabolites 2019, 9, 144](https://doi.org/10.3390/metabo9070144).

# Citation

[Kyo Bin Kang, Madeleine Ernst, Justin J. J. van der Hooft, Ricardo R. da Silva, Junha Park, Marnix H. Medema, Sang Hyun Sung, Pieter C. Dorrestein. Comprehensive mass spectrometry‐guided phenotyping of plant specialized metabolites reveals metabolic diversity in the cosmopolitan plant family Rhamnaceae. Plant J 2019, 98, 1134-1144](https://doi.org/10.1111/tpj.14292). 

# Jupyter notebooks

### MZmine_GroupMapping.ipynb

Jupyter notebook used to map metadata onto the mass spectral molecular network in Cytoscape version 3.4.0 ([Shannon et al., 2003](https://genome.cshlp.org/content/13/11/2498.full)) for the MZmine 2 ([Pluskal et al., 2010](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/1471-2105-11-395)) preprocessed dataset.

# Folders

## ClassyFire

The folder called **ClassyFire** contains R scripts and data files used for performing automated chemical classification of the <i>in silico</i> annotated structures using ClassyFire ([Djoumbou Feunang et al., 2016](https://jcheminf.springeropen.com/articles/10.1186/s13321-016-0174-y)).

## Mass2Motifs_2_MolecularNetwork

The folder called **Mass2Motifs_2_MolecularNetwork** contains R scripts and data files used for mapping Mass2Motifs ([Van der Hooft et al., 2016](http://www.pnas.org/content/113/48/13738.full); [Wandy et al., 2018](https://academic.oup.com/bioinformatics/article/34/2/317/4158166)) on the mass spectral molecular networks ([Wang et al., 2016](https://www.nature.com/articles/nbt.3597); [Watrous et al., 2012](http://www.pnas.org/content/109/26/E1743)). 

## ChemicalClass_DistanceMetric

The folder called **ChemicalClass_DistanceMetric** contains python and R scripts as well as data files used for calculating a  chemically informed distance metric based on ClassyFire chemical ontology inspired by the metric proposed by [Junker, 2018](https://link.springer.com/article/10.1007/s00049-017-0250-4).

## CSCD

The folder called **CSCD** contains jupyter notebooks and data files used for calculating the chemical structural and compositional dissimilarity (CSCD) proposed by [Sedio et al., 2017](https://esajournals.onlinelibrary.wiley.com/doi/full/10.1002/ecy.1689).
