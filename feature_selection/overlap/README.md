## Following are the main directories which need to be referred : - </br>
1. ensembl-ensembl : where ensembl (all_gene) to ensembl (lincRNA) overlap analysis have been done. </br>
2. refseq-refseq : where refseq (all_gene) to refseq (lncRNA) overlap analysis have been done. </br>
3. ens-ref : where ensembl (lincRNA) to refseq (lncRNA) overlap analysis have been done. </br>
### Overlap function main approach/logic:</br>
a) Clean data (arrange in ascending chr region and remove NW, NT for refseq and M, K, G for ensembl)</br>
b) Overlap to be found between genes lying in the same chr regions.</br>
c) For gene1 lying in chr1, find all overlaps of gene2...geneN lying in chr1. </br>
d) Repeate point c) for all genes in all chr regions. </br>
