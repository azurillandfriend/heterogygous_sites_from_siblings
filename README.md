# heterogygous_sites_from_siblings
This takes the genotypes of a set of siblings in zarr format and produces a vcf file indicating SNPs that are heterozygous in all of them

The code is in the form of a jupyter notebook and should work in Python 3.8 and above.

The first time the notebook is run it will be necessary to install the packages.

This code has been written for zarr formatted genotypes from the Anopheles gambiae 1000 genomes project.

The outputted VCFs are intended to be used to facilitate detection of SNPs showing allelic imbalance of expression in RNAseq data in the siblings of the genotyped individuals. 
