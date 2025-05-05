# HP-Pipeline-Batch

This repository contains the automated Python pipeline for analyzing 1000 human hypothetical proteins (HPs), developed as part of my M.Sc. Bioinformatics thesis work at Jamia Hamdard University.

## Overview

The goal of this project is to design a scalable, efficient, and reproducible workflow to:
- Process and retrieve structural and functional annotations for HPs
- Benchmark and analyze data using tools such as Foldseek
- Automate sequence retrieval and preliminary similarity searches
- Prepare results for downstream visualization and statistical analysis

## Folder Structure
HP-Pipeline-Batch/
├── batch_script_day2.py         # Python pipeline script
├── results/                     # Output files (to be updated)
├── data/                        # Input FASTA files (optional)
├── README.md                    # Project 

## Tools & Libraries

- Python 3.x
- Biopython
- requests
- os, glob, time
- Foldseek (external server)
- Google Colab for execution and logging

## Execution Environment

This pipeline was developed and run in [Google Colab](https://colab.research.google.com/). The Colab notebook with detailed execution steps and outputs can be found here:

[Colab Notebook Link](https://colab.research.google.com/drive/1RfQKdfc7sZXkKX3oVJKsWclYmzQIzKZc?usp=sharing)

## Author

**Bushra Khan**  
M.Sc. Bioinformatics  
Jamia Hamdard University  

## Status

Work in progress — currently building batch-wise automation and expanding output parsing.

---