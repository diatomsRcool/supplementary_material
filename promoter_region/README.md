
This folder contains the supplementary data for the paper "Using knowledge graphs to infer gene expression in plants" DOI:XXXXXXX. 

The files are referred to in the paper as Supplementary Data 1-6 in the following order.

1) drought_expression.tsv
2) drought_genes.tsv
3) GO_annotations.tsv
4) panther_results folder
5) promoter_region_clustvis_data0.tsv
6) orthologous_genes.tsv

drought_expression.tsv: Three columns, one header row, and 67 data rows. Tab-delimited. First column header is "exposure". In this file there is only one exposure "drought treatment". Second column header is "expression" and can be either "decreases expression of" or "increases expression of". Third column header is "gene_id". This column contains gene identifiers for sorghum (Sobic), maize (Zm00001eb), Arabidopsis (AT), and poplar (POPTR_). These data are from the EMBL-EBI Expression Atlas and were downloaded in April 2022.

drought_genes.txt: Two columns, one header row, and 73 data rows. Tab-delimited. First column header is "GENE_ID". This column contains gene identifiers for sorghum (Sobic), maize (Zm00001eb), Arabidopsis (AT), and poplar (POPTR_). Second column header is "Taxon". This column contains one of four Latin binomials representing the taxon the gene belongs to: Sorghum bicolor, Arabidopsis thaliana, Zea mays, and Populus trichocarpa. These data are from the EMBL-EBI Expression Atlas and were downloaded in April 2022.

GO_annotations.txt: Four columns, one header row, and 230 data rows. Tab-delimited. First column header is "gene_id". This column contains gene identifiers for sorghum (Sobic), maize (Zm00001eb), Arabidopsis (AT), and poplar (POPTR_). Second column header is "predicate". This column contains one of three predicates that correspond to the Relation Ontology and to Biolink model predicates: "active in", "regulates", and "enables". Third column header is "GO_label". It contains the English label for the GO class that was applied to the gene in column 1. Fourth column header is "GO_CURIE". This is the CURIE for the GO class that was applied to the gene in column 1. These data were downloaded from the Gene Ontology website in April 2022.

orthologous_genes.txt: Two columns, one header row, and 62 data rows. Tab-delimited. First column header is "orthologous_gene_1". Second column header is "orthologous_gene_2". Both columns contain gene identifiers for sorghum (Sobic), maize (Zm00001eb), Arabidopsis (AT), and poplar (POPTR_). Each row lists two gene identifiers that are orthologous according to InParanoid in Planteome.

promoter_region_clustvis_data0.tsv: 29 data columns, first column is row labels (30 columns total). First row is header row. Rows 2, 3, and 4 are annotation rows. Columns are gene identifiers (either poplar POPTR_ or Arabidopsis AT). Rows are transcription factors. There are 70 data rows. Row 2 label is "Homolog" and indicates which Arabidopsis and poplar genes are homologous. Each of 14 pairs are labeled with an integer, 1 through 14. Row 3 label is "Taxon" and indicates which species the gene is from using "Poplar" or "Arabidopsis". Row 4 label is "Expression" and indicates which genes had their expression increased or decreased during a drought exposure using "Decreased" or "Increased". The following 70 data rows have either 0 or 1 to indicate presence or absence of each transcription factor (rows) in the promoter region of each gene (columns). The promoter regions were obtained using the BioMart function in Gramene. The list of transcription factors in each gene's promoter region was obtained from PlantPAN. These data retrievals and analyses were performed in May of 2022.

panther_results folder: This folder contains nine json files representing the only statistically significant results from PANTHER (accessed through the Gene Ontology website). We performed an enrichment analysis using PANTHER for the genes that were affected by drought. We did a separate analysis for each taxon (Sorghum bicolor, Arabidopsis thaliana, Zea mays, and Populus trichocarpa) and for each available annotation data set. Most of these results were not statistically signficant. The significant results are in this folder. This analysis was performed in July 2022.

clustalvis folder: This folder contains the data and metadata from the ClustVis website that describes the PCA analysis and heatmap. This can also be viewed (here)[https://biit.cs.ut.ee/clustvis/?s=IWJNurmUtGWZoMt]. 
