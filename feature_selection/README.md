# All csv files can be downloaded from [here](https://drive.google.com/open?id=1AU0KGgm3-OhYcgtvU_mAIadp9dI9dXlV).<br/>
#### 1) _v10 directory contains all the features (overlap, orf, _v1, _v2...,_v10). THIS IS THE MAIN DIRECTORY FOR ML ANALYSIS!<br/>
#### 2) _v9 directory contains all the features (overlap, orf, _v1, _v2...,_v9), except _v10.<br/>
#### 3) _v8 directory contains all the features (overlap, orf, _v1, _v2...,_v8), except _v9 and _v10.<br/>
#### 4) Similarly, for others. <br/>
<br/>
<br/>
### Details for rest of the features given below: (Thanks a ton for these, [Ruth]() !)
Locus 1 from Gencode has biotype long intergenic RNA

Locus 2 from RefSeq has biotype ncRNA

Neither locus 1 nor locus 2 is associated with an HGNC ID - Ensembl IDs 
must be checked against the current www.genenames.org website as Ensembl 
update cycle is behind HGNC updates

Locus 2 from RefSeq should must have a value in the Gene symbol field 
from the NCBI Gene website in the format LOC# where # is a number (a 
different format suggests the symbol may be from a publication and we 
would want to investigate further)

At least one transcript from locus 1 and one transcript from locus 2 
overlap (by any extent) on same strand

At least one transcript from locus 1 and locus 2 share at least 2 
intron/exon boundaries

No transcript from locus 1 or 2 overlaps a protein coding gene, 
microRNA, snoRNA, pseudogene or second long intergenic RNA/ncRNA 
annotated by Gencode or RefSeq on the same strand (ens-ens and ref-ref overlap)

No transcript from locus 1 or 2 overlaps the genomic span of a protein 
coding gene annotated by Gencode or RefSeq on the opposite strand 
(including UTRs, exons and introns)

No transcript from locus 1 or 2 overlaps the genomic span of a protein 
coding gene annotated by Gencode or RefSeq on the same strand (including 
UTRs, exons and introns) 

No transcript from locus 1 or 2 is within 1 kb of the extent of a 
protein coding gene annotated by Gencode or RefSeq on the same strand

No transcript from locus 1 or 2 is within 1 kb of the extent of a 
protein coding gene annotated by Gencode or RefSeq on the opposite 
strand.

No transcript from locus 1 or 2 is within 500 nucleotides of a second 
lincRNA gene on the SAME strand (opposite stand does not matter)

