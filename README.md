# GiantVirusEvoGenome

## Figure 3

The code would generate scatter plots for figure 3.

### required files

- pangenome of lineages: pangenome0807lineage.tsv
- virus list with pangenome of genomes: viruslist-single-pan0807_plus2.tsv
- tree file: iq2-allmaf_og.fasta.treefile
- host taxonomy: euktax.tsv

### required packages

 - ape
 - ggplot2


## Figure 4

The code would do pair comparison among viruses in Iridoviridae/Poxviridae that infect insect or vertebrate hosts and Mimiviridae/Pycodnaviridae that infect amoeba or alga hosts and generate violin plots for figure 4.

### required files

- list of number of orthogroups shared between genomes normalized by geometric mean of their respective total numbers of orthogroups shared with any taxon: cnt-sp-norm-0808.csv
- virus list with pangenome of genomes: viruslist-single-pan0807.tsv

### required packages

- stringr
- ggplot2
- ggpubr
