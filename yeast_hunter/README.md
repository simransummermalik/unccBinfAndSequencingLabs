# BINF 3101 – Yeast Hunter Activity

This folder documents my work for the Yeast Hunter activity in UNC Charlotte’s BINF 3101 course.  
The purpose of this activity was to virtually “hunt” for a species within the SRA dataset, identify its sequencing run, and establish a foundation for downstream computational analysis.

## Objectives
- Explore the diversity of organisms available through the Yeast Hunter dataset.
- Select one species of interest and retrieve its sequencing metadata.
- Connect the chosen dataset to subsequent labs focused on read trimming and assembly.
- Gain experience with SRA identifiers and sequencing metadata management.

## Species Selection
- **Chosen species:** Hibiscus plant  
- **Rationale for selection:** The Hibiscus plant represents a non-model organism with valuable biological and horticultural significance. By working with this dataset, the exercise emphasizes how genomic data can be leveraged from diverse sources beyond commonly studied yeast species.  
- **Sequencing data identifier:** SRR16989221 (NCBI SRA Run ID)  

## Skills and Tools Learned
- Navigating shared class directories on the UNC Charlotte HPC cluster.
- Using **SRA Toolkit** commands (`prefetch`, `fasterq-dump`) to identify and retrieve sequencing runs.
- Interpreting sequencing metadata to link biological samples with computational workflows.
- Establishing reproducible documentation for downstream use in Lab 2 and beyond.

## Workflow Summary
1. **Exploration:** Surveyed the collection of candidate species available for the activity.  
2. **Selection:** Chose the Hibiscus plant as the focal species.  
3. **Metadata retrieval:** Identified the correct SRA Run ID associated with the Hibiscus sequencing dataset.  
4. **Preparation:** Recorded the Run ID for use in Lab 2, where quality trimming and FastQC analysis are performed.  

## Notes
- The Yeast Hunter activity does not produce independent computational outputs; its primary goal is species selection and dataset identification.  
- The selected dataset (Hibiscus plant, SRR16989221) provides the raw sequencing reads analyzed in Lab 2.  
- Large FASTQ files remain on the HPC cluster and are not stored in this repository.
