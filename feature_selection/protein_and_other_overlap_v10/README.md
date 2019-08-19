### csv file found [here](https://drive.google.com/drive/folders/1rUvFyQc_Qv8cfNafaIE2Z0hOpLgwWd4C?usp=sharing).<br/>
Logic: - <br/>
1) No transcript from locus 1 or 2 overlaps a protein coding gene, <br/>
microRNA, snoRNA, pseudogene or second long intergenic RNA/ncRNA <br/>
annotated by Gencode or RefSeq on the same strand (ens-ens and ref-ref overlap)<br/>

2) No transcript from locus 1 or 2 overlaps the genomic span of a protein <br/>
coding gene annotated by Gencode or RefSeq on the opposite strand <br/>
(including UTRs, exons and introns)<br/>
3) if above two statements are true, save 1. Else, save 0.

