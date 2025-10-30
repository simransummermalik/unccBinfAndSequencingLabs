# BINF 3101 – Lab 9: Comparative Genomics

This folder documents my work for Lab 9 of UNC Charlotte’s BINF 3101 course.  
The focus of this lab was comparative phylogenetic analysis using protein-coding sequences to evaluate the relationship between gene-level and species-level evolution.

## Overview
In this lab, I analyzed the **HXK2** gene (hexokinase 2) across multiple yeast taxa to explore evolutionary divergence at the molecular level.  
Using multiple sequence alignment and phylogenetic reconstruction, I compared the topology of the **HXK2 gene tree** with the provided **reference species tree**, assessing whether gene evolution reflected overall organismal relationships.

## Objectives
- Perform comparative genomics analysis using amino acid sequences of HXK2.  
- Construct a gene-based phylogeny and evaluate its statistical model of evolution.  
- Compare the resulting topology to the canonical species tree to identify concordant and discordant nodes.  
- Interpret the implications of model fit, sequence variation, and clade formation on evolutionary inference.

## Summary of Work
Protein sequences corresponding to HXK2 from diverse yeast species were aligned to a common reference frame using a high-accuracy multiple alignment algorithm.  
A maximum likelihood tree was then inferred from the aligned dataset, with the **best-fit substitution model** automatically selected by a model optimization framework.  
The resulting phylogeny was visualized and rooted with a designated outgroup to ensure directional evolutionary interpretation.  
The structure of the HXK2 gene tree was subsequently compared to a curated species-level tree to identify any topological discrepancies, which may reflect lineage-specific rate variation or gene-level evolutionary pressures.

## Skills and Techniques
- **Comparative Phylogenomics**: Evaluating gene-to-species tree congruence.  
- **Multiple Sequence Alignment**: Translating sequence data into homologous positions suitable for evolutionary inference.  
- **Model Selection**: Applying statistical model testing to identify the most appropriate amino acid substitution framework.  
- **Maximum Likelihood Estimation**: Building optimized phylogenies with branch support metrics.  
- **Computational Reproducibility**: Maintaining organized directory structure, reproducible output logs, and version-controlled documentation.

## Interpretation
The HXK2 gene-based phylogeny revealed that while broad lineage relationships paralleled the expected species-level topology, minor rearrangements occurred within specific clades.  
These shifts likely represent subtle differences in selective constraints acting on HXK2 orthologs.  
Such differences underscore how molecular evolution at the gene level can deviate from macroevolutionary species divergence, providing insight into functional adaptation and evolutionary rate heterogeneity among yeasts.

## Deliverables
- `hxk2.class.fasta` — Input protein sequences for all taxa.  
- `hxk2.align.fasta` — Aligned sequences used for phylogenetic reconstruction.  
- `hxk2.align.fasta.treefile` — Maximum likelihood tree file (Newick format).  
- `hxk2.align.fasta.log` and `.iqtree` — Computational logs and model statistics.  
- `hxk2_tree_colored.png` — Visualization of the rooted and annotated tree.  
- `README.md` — Workflow documentation and interpretive summary.

## Notes
All computational analyses were performed on the **UNC Charlotte HPC (Gal-i9)** environment using module-managed software for reproducibility.  
Tree visualization and annotation were completed using **iTOL (Interactive Tree of Life)**.  
Raw data are stored securely within the HPC environment; only derived and documentation files are included in this repository.

