# Cis-regulatory effect of HPV integration is constrained by host chromatin architecture in cervical cancers.
This repository contains the code used to generate the figures, which are provided in the respective notebooks.

The compiled list of HPV integrations (hg19) can be accessed from the Supplementary File 1 of the manuscript.
The TAD coordinates (hg19) for both HeLa and NHEK can be obtained from the Supplementary File 2 of the manuscript. 
Other datasets can be downloaded from the respective sources as mentioned in the manuscript.

Please change the paths in the notebooks accordingly, wherever required.

#### Notebooks
Description of Notebooks and their contents.

1. [Notebook to generate Figure 1, genome-wide enrichment of HPV integrations in different functional regions.](https://github.com/autobot101/cisHPV/blob/main/fig1_github.ipynb) 
2. [Notebook to generate Figure 2, host chromatin state influences HPV integration induced expression dysregulation in its immediate neighbourhood.](https://github.com/autobot101/cisHPV/blob/main/fig2_github.ipynb)
3. [Notebook to generate Figure 3 and Figure 4, related to TADs.](https://github.com/autobot101/cisHPV/blob/main/fig3_fig4_github.ipynb) 


#### <br/>Required Packages

<b>Python 3.6.7</b>

```diff
pandas                        0.25.0
numpy                         1.15.4 
matplotlib                    3.2.1
seaborn                       0.11.2
scipy                         1.5.1
statsmodels                   0.11.1
pybedtools                    0.7.10
```




