# Data for "Plastid-localized xanthorhodopsin increases diatom biomass and ecosystem productivity in iron-limited surface oceans"
The repository contains supplementary data and metadata used in the Nature Microbiology research paper [https://www.nature.com/nmicrobiol/](Plastid-localized xanthorhodopsin increases diatom biomass and ecosystem productivity in iron-limited surface oceans).

## A phylogenetic tree of representative microbial rhodopsins
The tree is based on eukaryotic rhodopsin sequences.

## Files in the repository
+ `data/Xanthorhodopsins_Strauss_et_al2023_AlignmentWithGaps.fasta` - raw alignment
+ `data/Xanthorhodopsins_Strauss_et_al2023_MaskedAlignment.fasta` - masked alignment done with positions with 25% gaps
+ `data/Xanthorhodopsins_Strauss_et_al2023_RAxML.tree` - Newick tree file
+ `data/FcR1_A0A1E7EXA4.cif` - AlphaFold2 structure prediction of Fragilariopsis cylindrus rhodopsin 1 (FcR1; UniProt: A0A1E7EXA4) with retinal in crystallographic information file (CIF) format
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
