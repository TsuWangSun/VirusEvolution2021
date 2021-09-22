# VirusEvolution2021

This document is the R code used in Sun, T.-W. and C. Ku (2021) Unraveling gene content variation across eukaryotic giant viruses based on network analyses and host associations. Virus Evolution, veab081, https://doi.org/10.1093/ve/veab081. The code performs the analyses for figure 3 and 4 that calculate and visualize 1) the correlations between genome variation and host diversity, and 2) the comparisons of gene sharing among two sets of NCLDV family with similar and dissimilar hosts.


## Figure 3

The code would calculate and visualize the genome variations and host diversity of NCLDV families with scatter plots, including supergroup-level host diversity, protein and singleton number diversity, and core-gene tree divergence (avereage relative distance on tree) (see Figure 3 of Sun & Ku, 2021). 

R code: fig3/R_0607fig3.ipynb

### required datasets

- pangenome of lineages: pangenome0807lineage.tsv
- virus list with pangenome of genomes: viruslist-single-pan0807_plus2.tsv
- tree file: iq2-allmaf_og.fasta.treefile
- host taxonomy: euktax.tsv

All datasets are available in "fig3/" directory.

### required packages

 - ape
 - ggplot2


## Figure 4

The code would do pair comparison among viruses in Iridoviridae/Poxviridae that infect insect or vertebrate hosts and Mimiviridae/Pycodnaviridae that infect amoeba or alga hosts and generate violin plots for figure 4.

R code: fig4/R_0807fig4.ipynb

### required datasets

- list of number of orthogroups shared between genomes normalized by geometric mean of their respective total numbers of orthogroups shared with any taxon: cnt-sp-norm-0808.csv
- virus list with pangenome of genomes: viruslist-single-pan0807.tsv

All datasets are available in "fig4/" directory.

### required packages

- stringr
- ggplot2
- ggpubr
