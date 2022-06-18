# Master_thesis
An analysis of a tissue-specific phosphorylation and phosphosite mutation map of the human proteome

This repository contains the code used for my master thesis, titled an analysis of a tissue-specific phosphorylation and phospho-site mutation map of the human proteome. RAW MS data was retrieved from PRIDE repository (https://www.ebi.ac.uk/pride/archive/) and reprocessed using ionbot (https://www.biorxiv.org/content/10.1101/2021.07.02.450686v2) (https://ionbot.cloud) from the CompOmics group (https://www.compomics.com), under supervision of prof. dr. Lennart Martens and Pathmanaban Ramasamy. Manutal tissue annotation was retrieved by Tine Claeys.

I'm gratefull to the entire CompOmics group as part of the VIB-UGent Centre for Medical Biotechnology, Ghent University and prof. dr. Lennart Martens and Pathmanaban Ramasamy in particular.

This project consists of multiple steps. The way the large datafiles "phospho_data" and all modications data was generated, is shown in the files "data" and "data_WP3".

A first exploration of the data was performed in "data_eploration".

Identifying itneresting phosphoproteins and phosphosites was done in "WP1". Tissue-based phosphorylation patterns were investigated in "WP1_patterns".

In silico functional annotation was studied on both the phosphoprotein and phosphosite level, for GO-terms, functional domain annotation and disordered region information. In addition, a mutational analysis with data from Humsavar and TCGA was carried out.

In WP3, we considered other modifications identified in the 150 projects considered for the previous analyses.
