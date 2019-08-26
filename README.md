# Google Summer of Code-2019 : Srijan Verma
### Mentors : [Daniel Zerbino](https://www.ebi.ac.uk/about/people/daniel-zerbino), [Elspeth Bruford](https://www.ebi.ac.uk/about/people/elspeth-bruford), [Ruth Seal](https://www.ebi.ac.uk/about/people/ruth-seal)

### Project Title  
Applying machine learning techniques to characterising and naming lncRNA genes

![](https://media1.tenor.com/images/8ab51cca650124bdbd211ce2e8fb0714/tenor.gif?itemid=10625836)

## Brief Description
Advances in RNA sequencing technologies have revealed the complexity of our genome.
Long non-coding RNAs (lncRNAs) make up the majority of the non-coding transcriptome.
Understanding the significance of this RNA world is one of the most important challenges
faced in biology today, and the lncRNAs within it represent a gold mine of potential new
biomarkers and drug targets. Its discovery is still at a preliminary stage.

<img src="https://www.researchgate.net/profile/Sayantan_Maji/publication/299381675/figure/fig1/AS:347583198318593@1459881700776/Non-coding-RNA-Non-coding-RNA-comprise-a-much-larger-portion-of-the-human-genome-than.png" width="600" height="300" />

To date, very few lncRNAs have been characterized in detail. However, it is clear that
lncRNAs are important regulators of gene expression, and lncRNAs are thought to have a
wide range of functions in cellular and developmental processes. There are many
specialized lncRNA databases (like RefSeq, GENCODE, Ensembl, SGD, tair). We will use
Machine Learning techniques to highlight and compare two sets of calls (of Ensembl /
GENCODE and RefSeq) and determine which calls are incorrect.

## Specifications of the parent directory (srijan-gsoc-2019)
Contains 4 folders namely: <br/>
1. Ensembl-analysis - Where scripts for making analysis and data collected from Ensembl can be found.<br/>
2. RefSeq-analysis - Where scripts for making analysis and data collected from RefSeq can be found.<br/>
3. feature_selection - Where scripts for creating features can be found.<br/>
4. ML - Where scripts for making ML analysis on data collected (with their features) can be found.<br/>
## Dependencies
### Python 3.6
json<br/>
Pandas<br/>
Numpy<br/>
Biopython<br/>
Pyfasta<br/>
gffpandas<br/>
sklearn<br/>

## Data
1. Data obtained from Ensembl can be found [here](https://github.com/EnsemblGSOC/srijan-gsoc-2019/tree/master/Ensembl-analysis). <br/>

2. Data obtained from RefSeq can be found [here](https://github.com/EnsemblGSOC/srijan-gsoc-2019/tree/master/RefSeq-analysis). <br/>



## Research papers / References
#### Some of the papers which have been published in the similar domain are given below: <br/>
1. [A Deep Learning Framework for Robust and Accurate Prediction of ncRNA-Protein](https://drive.google.com/file/d/1dNlT_ed3bXUwNlfDRM8BmV4bGduzgLEc/view?usp=sharing)<br/>

2. [Accurate prediction of protein lncRNA interactions by diffusion and HeteSim features](https://drive.google.com/file/d/11Bqi1AdLIKPDWxeHIvURuyX-nN3kwZOj/view?usp=sharing)<br/>

3. [CRlncRC: a machine learning-based method for cancer-related Lnc RNA identification using integrated features](https://drive.google.com/file/d/1ggXskSpbneFSw76R7T5giPW6PiwuyJMw/view?usp=sharing)<br/>

4. [LncADeep](https://drive.google.com/file/d/1DWC2s4rQulZQUPQFU7yhPtQtfgOvnELg/view?usp=sharing)<br/>

5. [lncRNAnet: Long Non-coding RNA Identification using Deep Learning](https://drive.google.com/file/d/1-4eDyLmFit0NODxf-TWwLpyLY2gcL3HI/view?usp=sharing)<br/>

6. [Long Noncoding RNA Identification: Comparing Machine Learning Based Tools for Lnc Transcripts Discrimination](https://drive.google.com/file/d/15kOvyRAbIqDzwD6G9rqJMO-J3GW-pyRm/view?usp=sharing)<br/>

7. [Machine Learning Based LncRNA Function Prediction](https://drive.google.com/file/d/1GybUbLfF5U1bf9-J4YOoOxoqyn7whIm3/view?usp=sharing)<br/>

8. [Prediction of LncRNA Subcellular Localization with Deep Learning from Sequence Features](https://drive.google.com/file/d/11Mi3UnXAc1PUWNQW1RXVDdQIqQnXi_dD/view?usp=sharing)<br/>

## Medium blogs
1. [GSoC Journey Part 1](https://medium.com/@verma.srijan/gsoc-journey-part-1-ba251b69bede)<br/>

2. [GSoC Journey Part 2- The Problem Statement](https://medium.com/@verma.srijan/gsoc-journey-part-2-the-problem-statement-55a2293678d0)<br/>

3. [GSoC Journey Part 3- Data Analysis](https://medium.com/@verma.srijan/gsoc-journey-part-3-data-analysis-d9c1873703fc)<br/>

4. [GSoC Journey Part 4- Final Report and Summary](https://medium.com/@verma.srijan/gsoc-journey-part-4-final-report-and-summary-ae9c4e4c7718)<br/>

## Acknowledgements
1. I would like to thank [Daniel Zerbino](https://www.ebi.ac.uk/about/people/daniel-zerbino) for taking the time to mentor me and for providing invaluable suggestions. I truly appreciate his constant trust and encouragement!<br/>

2. [Elspeth Bruford](https://www.ebi.ac.uk/about/people/elspeth-bruford)<br/>

3. [Ruth Seal](https://www.ebi.ac.uk/about/people/ruth-seal)<br/>

4. [Ensembl](https://asia.ensembl.org/index.html) admins, helpdesk and the whole community <br/>

5. [GSoC](https://summerofcode.withgoogle.com/) organizers, managers and Google 
