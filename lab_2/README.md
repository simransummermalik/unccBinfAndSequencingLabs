# BINF 3101 – Lab 2: De novo Assembly (Part 1)

This folder documents my work for Lab 2 of UNC Charlotte’s BINF 3101 course.  
The focus of this lab was preprocessing raw sequencing reads from the NCBI Sequence Read Archive (SRA) to ensure quality prior to de novo genome assembly.

## Objectives
- Retrieve raw Illumina sequencing reads from the SRA using the UNC Charlotte HPC cluster.
- Convert `.sra` files into paired-end FASTQ files.
- Perform adapter trimming and quality filtering using **Trimmomatic**.
- Evaluate read quality before and after trimming with **FastQC**.
- Interpret quality metrics and summarize the effects of trimming.

## Skills and Tools Learned
- **HPC navigation**: logging in with SSH, creating directories, managing files.
- **SRA Toolkit**: `prefetch` and `fasterq-dump` for downloading and converting raw sequencing data.
- **Slurm workload manager**: creating and submitting job scripts with `sbatch`, monitoring with `squeue`, and extracting results from `.out` logs.
- **Trimmomatic**: applying quality trimming filters including HEADCROP, TRAILING, SLIDINGWINDOW, and MINLEN.
- **FastQC**: generating quality reports for paired FASTQ files and interpreting QC modules (Basic Statistics, GC Content, Duplication Levels).
- **Reproducible workflows**: documenting computational steps, results, and parameters in a structured, transparent manner.

## Workflow Summary
1. **Data Retrieval**  
   - Used `prefetch` to download the assigned SRA dataset.  
   - Converted `.sra` to paired-end FASTQ files using `fasterq-dump`.  

2. **Read Trimming**  
   - Implemented **Trimmomatic** with a provided Slurm script to remove low-quality bases and adapters.  
   - Applied trimming filters for leading and trailing low-quality bases, sliding-window filtering, and minimum length requirements.  
   - Recorded trimming statistics from the Slurm output logs.  

3. **Post-trimming Quality Control**  
   - Ran **FastQC** on trimmed paired-end FASTQ files.  
   - Examined summary reports for overall sequence quality, GC content, and duplication levels.  

## Notes
- Large raw FASTQ files, trimmed outputs, and `.zip` quality reports are not included here due to storage limits on GitHub.  
- This folder is intended to document workflow and reproducibility, not to host raw sequencing datasets.  
- Results are summarized for instructional purposes in BINF 3101.
