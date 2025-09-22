# NGS Analysis Pipeline for Triple-Negative Breast Cancer Thesis

This repository contains scripts used in the Next-Generation Sequencing (NGS) analysis pipeline for my thesis titled:  
**Differential Gene Expression Analysis of Triple-Negative Breast Cancer Cells Treated with Pure Gallic Acid and Mangifera foetida Leaf Extract**.

The scripts automate key parts of the pipeline, including pre-processing and differential gene expression (DEG) analysis. The codebase has been refactored and commented with the help of OpenAI o1.

## Repository Contents

- **`ngsAutomation.sh`**: A Bash shell script that automates the pre-processing steps of the NGS pipeline, including:
  - Alignment
  - File format conversion
  - Sorting
  - Indexing
  - Verification

- **`degScript.R`**: An R script for performing the actual differential gene expression (DEG) analysis.

## Prerequisites and Dependencies

To run these scripts, you'll need:
- **Bash-compatible environment** (e.g., Linux, macOS, or WSL on Windows) for `ngsAutomation.sh`.
- **R** (version 4.0 or later) for `degScript.R`, along with required packages (please see the code for the packages used).
- Common NGS tools like SAMtools, Bowtie2, and HISAT2.
- Access to raw NGS data (e.g., FASTQ files) and reference genomes.

Install dependencies via your package manager (e.g., `apt`, `brew`, or `conda` for a virtual environment).

## Contributing

This is a personal thesis project, but feel free to inquire about it.

## Acknowledgments

- Refactored and commented with assistance from OpenAI o1.
- Thanks to my thesis supervisors Prof. Ade Arsianti, Aryo Tejo M.Si, Linda Erlina M. Farm

## License

This project is licensed under the MIT License
