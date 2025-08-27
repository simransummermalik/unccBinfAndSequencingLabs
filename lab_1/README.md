# BINF 3101 – Lab 1: Computational Skills

This folder contains my work for **Lab 1: Introductory Computational Skills** in UNC Charlotte’s BINF 3101 course.  
The focus of this lab was learning how to use the **UNCC HPC (High-Performance Computing cluster)** to handle large genomic data.

---

## 🔹 Skills Learned
- Connecting to the HPC via SSH (with VPN + DUO)
- Navigating the cluster file system (`cd`, `pwd`, `ls`)
- Creating and organizing directories (`mkdir`)
- Copying shared files and uncompressing data (`cp`, `gunzip`)
- Viewing and exploring FASTA files (`less`, `head`)
- Using `grep` to search/count patterns in large files
- Running EMBOSS tools (`geecee`, `getorf`) for sequence analysis
- Writing and editing **Slurm batch scripts**
- Submitting jobs with `sbatch` and monitoring them with `squeue`
- Extracting ORFs and working with contig-specific subsets

---

## 🔹 Repository Contents
- `emboss_candida_auris.slurm` – Example Slurm script used to run ORF finding
- `Lab1_Instructions.md` – Lab outline and provided directions (optional)
- `results/` – Example output snippets (not full files)

---

## 🔹 Notes
- Large raw outputs (FASTA, ORF results, `.out` logs) are not included here due to file size.  
- Answers to Canvas questions (LQ1–LQ5) are **not provided here**. This repo is only for documenting workflow and reproducibility.
