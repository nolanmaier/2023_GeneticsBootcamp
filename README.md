# CRISPR screens in mammalian cells

This repository contains material for the HMS Genetics Bootcamp.

## Rationale
CRISPR-based technologies have revolutionized biology. These tools enable scalable perturbations of gene function, such as knockout, knockdown, and overexpression, and combined with advances in sequencing and nucleotide synthesis, enable genome-wide screens, previously restricted to non-mammalian model organisms, directly in mammalian cells. This enables rapid generation of insights into biology relevant to human biology and disease. The goal of this lab is to provide students an overview of the logic, benefits, and limitations of CRISPR screens as well as hands-on experience in analyzing screen data and then generating testable hypotheses, such that students can deploy screens for their own research.

## Objectives
To become acquainted with CRISPR screens in mammalian cells. Students will be introduced to different screening technologies, learn the advantages and challenges of performing and interpreting these types of experiments, and gain hands-on experience in analyzing the resulting data.

## Suggested Reading
[Przybyla L and Gilbert LA. A new era in functional genomics. Nature Reviews Genetics 2021](https://doi.org/10.1038/s41576-021-00409-w)


## Course overview
9:30-10:30  Lecture on CRISPR screening technologies

10:30-11:00 Examples of CRISPR screens to explore host-microbiome interactions

11:00-12:00 Processing sequencing data into CRISPR phenotype scores

12:00-1:00  Break for lunch

1:00-3:00   Analyzing and exploring CRISPR screen data for hypothesis generation

## Materials
[CRISPR_Screen_Introduction.pptx](CRISPR_Screen_Introduction.pptx) contains general background on CRISPR screening technology. [CRISPR_Screen_Analysis.pptx](CRISPR_Screen_Analysis.pptx) contains information on the screen data analysed in the Jupyter notebook. 

The sequencing data processing section of the course will use [sample_illumina_data.fastq](sample_illumina_data.fastq) and [hCRISPRiv2_sgRNA_list.xlsx](hCRISPRiv2_sgRNA_list.xlsx).

The CRISPR screen analysis section of the course will use the Jupyter notebook [CRISPR_screen_analysis.ipynb](CRISPR_screen_analysis.ipynb) and the datasets in [CRISPR_screendata](CRISPR_screendata). The conda requirements are in [environment.yml](environment.yml). The notebook can be run directly in your browser using Binder through this link: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/nolanmaier/2023_GeneticsBootcamp/HEAD?labpath=CRISPR_screen_analysis.ipynb)
(you may need to disable ad blockers on your browser).
