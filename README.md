# Enterobacter_prophages
# Enterobacter Prophage Diversity Dataset

This repository contains the dataset and scripts associated with the manuscript:

**“Extensive Hidden Prophage Diversity in Enterobacter Species Reveals Host Specificity and Local Distribution”**  
Danna Paola Bours-Lugo, Juan Manuel Hurtado-Ramírez, Armando Hernández-Mendoza, Ramón González-Conde, Adrian Ochoa-Leyva, and Gamaliel López-Leal*  

---

## 📊 Dataset description
We identified and validated **3,661 high-quality prophage sequences** from 747 *Enterobacter* genomes representing 20 species.  
The dataset includes:

- **`data/prophages.fna`** → FASTA file containing all prophage nucleotide sequences.  
- **`data/prophages_metadata.tsv`** → Metadata table with prophage ID, host species, isolation source, geographic origin, and NCBI accession of the host genome.  


---

## 🔬 Methods summary
- Host genomes: Downloaded from **NCBI GenBank/RefSeq** (October 2024).  
- Genome quality check: **CheckM2**.  
- Prophage detection: **VirSorter2** and validation with **CheckV**.  
- Genome annotation: **Prokka** (bacteria), **Pharokka** (phages).  
- Prophage clustering: **vClust** following ICTV species/genus thresholds.  
- Phylogenies: **IQ-TREE 2** for bacterial hosts and Neighbor-Joining for prophages.  
- Cophylogenetic analyses: **PACo** and **ParaFit**.  
- Rarefaction analyses: **vegan** R package.  

A detailed description of the methods is available in the manuscript.  


