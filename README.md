# Metabolic-Model

The Metabolic Model iDrosophila2 is an updated version of the iDrosophila1 Model (Cesur et.al; 2022). This model comprises of the curated metabolic genes which were curated using Systematic Curation and Nomenclature protocol. 

The curation includes pipelines for generating Gene-KO relationship using:
1. KEGG - Gene association from KEGG database
2. Orthologous Gene associations from model organisms (Homos sapients, Musmusculus, Caenorhabditis elegans and Saccharomyces cerevisiae)
3. myKEGG algorithm which is based on alignment of the dme protein sequences (13699) to the KEGG database using the online server
4. myTree algorithm which converts the neighbourhood distances to relatedness scores across phylogenetic tree

The scores were further used to train a logistic regression based classifier which would assign Gene-KO assignments based on the prediction scores from the alignment.
