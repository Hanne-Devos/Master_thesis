# An analysis of a tissue-specific phosphorylation and phosphosite mutation map of the human proteome


This repository contains the code used for my master thesis, titled an analysis of a tissue-specific phosphorylation and phospho-site mutation map of the human proteome, carried out under supervision of Prof. Dr. Lennart Martens and Dr. Pathmanaban Ramasamy. RAW MS data was retrieved from PRIDE repository (https://www.ebi.ac.uk/pride/archive/) and reprocessed using ionbot (( https://www.biorxiv.org/content/10.1101/2021.07.02.450686v2) & (https://ionbot.cloud)) from the CompOmics group (https://www.compomics.com). Manual tissue annotation was retrieved by Tine Claeys.

I'm gratefull to the entire CompOmics group as part of the VIB-UGent Centre for Medical Biotechnology, Ghent University and Prof. Dr. Lennart Martens and Dr. Pathmanaban Ramasamy in particular, for their assitance during this project.

This project consists of multiple steps. The way the large datafiles "phospho_data" and "all modifications data" were generated, is shown in the files "data" and "data_WP3". A first exploration of the data was performed in "data_eploration". Identifying interesting phosphoproteins and phosphosites was done in "WP1". Tissue-based phosphorylation patterns were investigated in "WP1_patterns".

In silico functional annotation (WP2) was studied on both the phosphoprotein and phosphosite level, for GO-terms, functional domain annotation and disordered region information. In addition, a mutational analysis with data from Humsavar and TCGA was carried out.

In WP3, we considered other modifications identified in the 150 projects considered for the previous analyses.

Folders are organised as follows:
- Data contains all files required for this work
- data_exploration_WP1: contains notebooks centering around first eploration and identifying tissue-specificness
- WP2: in silico functional annotation
- preparation defence: generating some extra plots, comparison with other modifications (=WP3)

More in detail explanations are in the folders themselves.
