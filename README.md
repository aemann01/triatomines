# Comparison of the bacterial gut microbiome of North American *Triatoma* spp. with and without *Trypanosoma cruzi*

[![DOI](https://zenodo.org/badge/199685121.svg)](https://zenodo.org/badge/latestdoi/199685121)

[Allison E. Mann, Elizabeth A. Mitchell, Yan Zhang, Rachel Curtis-Robles, Santosh Thapa, Sarah A. Hamer, Michael S. Allen. 2020. Frontiers in Microbiology](https://www.frontiersin.org/articles/10.3389/fmicb.2020.00364/full)

[Download raw sequencing files](https://www.ebi.ac.uk/ena/data/view/PRJEB34484)

## Supplementary materials
| File        | Description           |
| ------------- |:-------------|
| map.txt | Full dataset metadata |
| sequence_taxonomy_table.16s.merged.txt | Full ASV frequency table |

## Supplementary tables
| Table        | Description           |
| ------------- |:-------------|
| 1 Metadata | Sample metadata |
| 2 ASV table | ASV frequency table per sample |
| 3 Collapsed taxonomy | ASV frequency table collapsed by taxonomy used for taxonomy barchart |
| 4 Read stats | DADA2 read processing statistics |

## Scripts

| File        | Description           |
| ------------- |:-------------|
| composition_data_analysis.R | Generate PHILR distance, figure 1 dendrogram and taxonomy barchart, PERMANOVA statistics, Figure 2 phylofactor tree and boxplots | 
| dada2.for_16s_data.R | Raw data quality filtering, trimming and merging, ASV cluster, chimera removal, taxonomy assignment |
| placement_tree.sh | Figure 3 *Salmonella* placement tree |
| random_forest.r | R code to run random forest analysis as described in the paper |
