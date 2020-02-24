# "Humanization of yeast genes with multiple human orthologs reveals functional divergence between paralogs" Figure 6 rendering script and data.

This repository contains the data and figure rendering script (written in R) to generate figure 6 for the manscript "Humanization of yeast genes with multiple human orthologs reveals functional divergence between paralogs", Laurent et al. 2020. A preprint of the manscript can be found here: https://www.biorxiv.org/content/biorxiv/early/2019/06/13/668335.full.pdf

The data used to render figure 6 was generated using simulation and analysis tools that can be found here: https://github.com/a-teufel/Protein_Duplication This simulation platform was originally described in "The Many Nuanced Evolutionary Consequences of Duplicated Genes", Teufel et al. 2019, which can be found here: https://doi.org/10.1093/molbev/msy210

The naming of the files included in the data folder works as follows: SIM1 is bind both, SIM2 is bind B and not B', SIM3 is bind max, SIM4 is no bind, and SIM5 is bind B. The two WT experiments do not include duplicates.   

# Dependencies

The figure script is written in R and depends on the R libraries survival, survminer, latticeExtra, ggfortify, ggrepel, ggplot2, GGally, scales, cowplot, ggrepel, reshape2, and ggforce.
