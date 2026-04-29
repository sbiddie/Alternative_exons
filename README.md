# Alternative_exons

This repository is linked to the Manuscript by Weykopf et al., "Disease-associated genetic variants can cause missense effects in tissue-specific protein isoforms"

This repository contains 4 files. 
3 files are the exon classes:
Reference exons - derived from MANE select transcripts (File name:MANE_select_exons_merged.bed.gz)
Alternative exons - Exons in catalogue - Exons that are in Ensembl but which are not ref exons (File name:Ensembl_EIC_non_canonical_coding_merged.bed.gz)
Alternative exons - Exons NOT in catalogue - from FLIbase (Shi et al., 2023 NAR https://academic.oup.com/nar/article/52/D1/D124/7269180), which are exons not falling in the above two categories. (File name:FLIbase_ENIC_non_canonical_coding_merged.bed.gz)

GWAS catalog and ClinVar variants mapped to Alternative exon in catalogue, as described in Weykopf et al., were annoated to transcripts derived from FLIbase (Shi et al., 2023), and computated for variant effect scores using ESM-1v and Alphafold3 isoform structures using FoldX to determine ddG (free energy change) scores, as decribed in Weykopf et al. (File name:genesis_missense.tsv.gz)

