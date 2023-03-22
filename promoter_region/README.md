
This folder contains the supplementary data for the paper "Using knowledge graphs to infer gene expression in plants" DOI:XXXXXXX. 

drought_expression.tsv: Three columns, one header row, and 67 data rows. Tab-delimited. First column header is "exposure". In this file there is only one exposure "drought treatment". Second column header is "expression" and can be either "decreases expression of" or "increases expression of". Third column header is "gene_id". This column contains gene identifiers for sorghum (Sobic), maize (Zm00001eb), Arabidopsis (AT), and poplar (POPTR_). These data are from the EMBL-EBI Expression Atlas and were downloaded on XXXXXXXX.

drought_genes.txt: Two columns, one header row, and 73 data rows. Tab-delimited. First column header is "GENE_ID". This column contains gene identifiers for sorghum (Sobic), maize (Zm00001eb), Arabidopsis (AT), and poplar (POPTR_). Second column header is "Taxon". This column contains one of four Latin binomials representing the taxon the gene belongs to: Sorghum bicolor, Arabidopsis thaliana, Zea mays, and Populus trichocarpa. These data are from the EMBL-EBI Expression Atlas and were downloaded on XXXXXXXX.

GO_annotations.txt: Four columns, one header row, and 230 data rows. Tab-delimited. First column header is "gene_id". This column contains gene identifiers for sorghum (Sobic), maize (Zm00001eb), Arabidopsis (AT), and poplar (POPTR_). Second column header is "predicate". This column contains one of three predicates that correspond to the Relation Ontology and to Biolink model predicates: "active in", "regulates", and "enables". Third column header is "GO_label". It contains the English label for the GO class that was applied to the gene in column 1. Fourth column header is "GO_CURIE". This is the CURIE for the GO class that was applied to the gene in column 1. These data were downloaded from GO Annotations on XXXXXXXX.

orthologous_genes.txt
