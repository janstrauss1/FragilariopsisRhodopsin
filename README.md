# Data for Fragilariopsis Rhodopsin Project
The repository contains supplementary data and metadata for the Nature Microbiology research paper.

## A phylogenetic tree of representative microbial rhodopsins
The tree is based on eukaryotic rhodopsin sequences.

## Files in the repository
+ `data/Xanthorhodopsins_Strauss_et_al2023_AlignmentWithGaps.fasta` - raw alignment
+ `data/Xanthorhodopsins_Strauss_et_al2023_MaskedAlignment.fasta` - masked alignment done with positions with 25% gaps
+ `data/Xanthorhodopsins_Strauss_et_al2023_RAxML.tree` - Newick tree file
+ `metadata/Xanthorhodopsins_Strauss_et_al2023_metadata.csv` - metadata

## Metadata structure
| Column | Description |
| --- | --- |
| Name | Sequence ID/accession |
| Accession | NCBI  accession version |
| Description | Sequence/NCBI definition line |
| Organism | Organism |
| Sequence | Amino acid sequence |
| Taxonomy | Taxonomic lineage |
| db_xref | NCBI taxonomy ID |
| protein_family | Rhodopsin clade/family |
| taxon_group | Taxonomic group |
