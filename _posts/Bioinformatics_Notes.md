---
layout: post
title: Bioinformatics Running Notes
categories: Log
tags: Bioinformatics
---

# Illumina Sequencing (Next Gen)
- Steps: 
    1. DNA fragmented into small pieces 
    2. Adapters attached to ends 
    3. DNA denatured through ligation --> 2 strands
    4. Loaded onto chip or flow cell
    5. Complements generated through PCR
    6. Original strand is washed away
    7. Segment bends and attaches to a new adapter stuck to the flow cell
    8. Segment is amplified via PCR --> denatured so 2 strands --> repeat the process over and over 
    9. Flourescent labeled nucleotides added and pair with the nucleotide in the strand. Lasers are used to identify diff wave lenghts = diff nucleotides
    10. Reads are aligned and compared to reference genome
# lcWGS
- [Data Carpentry command line processing tutorial](https://datacarpentry.org/wrangling-genomics/01-background.html)
    - Workflow: Sequence reads --> Quality control using FASTQ --> Alignment to a genome --> Alignment cleanup --> Variant calling using BAM 
    - A FASTQ file contains the sequence, the identifier for the DNA, And a quality score for each nucleotide = probability that the wrong nucleotide was called

- [Using DDocent](http://www.ddocent.com)
