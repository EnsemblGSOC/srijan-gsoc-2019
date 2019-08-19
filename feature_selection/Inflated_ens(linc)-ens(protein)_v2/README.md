### csv file can be found [here](https://drive.google.com/drive/folders/1PmOZzZxoxe6JSzei_XGgtfo2MfPi21t4?usp=sharing).<br/>
#### Approach/ Logic :-<br/>
a) Locus 1 from Gencode has biotype long intergenic RNA

b) Locus 2 from RefSeq has biotype ncRNA<br/>
 
c) "No transcript from locus 1 or 2 is within 1 kb of the extent of a <br/>
protein coding gene annotated by Gencode or RefSeq on the same strand<br/>

d) No transcript from locus 1 or 2 is within 1 kb of the extent of a <br/>
protein coding gene annotated by Gencode or RefSeq on the opposite <br/>
strand."<br/>
1) If the above statements are true, save 1. Else, save 0. <br/>
2) True meaning - there is no transcript from locus1/2 which is within 1kb of extent of a protein coding gene.<br/>
### Work to be done further:<br/>
1) Protein coding genes which overlapped with ens (lincrna) / ref (lncrna) were only inflated by 1000 (substract 1000 from start and 1000 to end of protein coding and then check if it overlaps a locus 1/2 gene). <br/>
2) Inflation of all protein-coding genes from sorted_gene.csv to be done and to be checked with locus1/2 gene.

