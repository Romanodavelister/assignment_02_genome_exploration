# Assignment_02_Genome_Exploration_II

# Species: 

**Carcharodon carcharias*

# Accession:

GCA_017639515.1

# Objective:

To analyze the basic characteristics of a genome assembly by examining its genome size, sequence count, N50, L50, GC content, and sequence-length distribution, while applying length filtering and exploring ORFs to distinguish potential coding regions from confirmed genes.

# Tools & Parameters Used:

- **Gfastats**: Evaluated genome assembly quality, sequence continuity, genome size, N50, L50, and GC content.
  
- **Compute Sequence Length**: Determined the length of each genome sequence to assess sequence-size distribution and identify short or long sequences.
  
- **Sort**: Organized genome sequences by length, making it easier to examine sequence-size distribution and identify longer or shorter scaffolds.
  
- **Filter Sequences by Length**: Removed sequences below a selected length threshold to reduce short sequences and evaluate changes in the genome assembly.
  
- **getorf**: Identified potential open reading frames (ORFs) in the genome sequences to explore possible protein-coding regions.

# Biological Interpretation

The genome assembly of **Carcharodon carcharias* has a total length of approximately 4.29 Gb distributed across 719 scaffolds, indicating a relatively large and well-assembled genome dominated by long scaffolds. The high N50 of 169.9 Mb and L50 of 11 show that a small number of very long scaffolds contain a large proportion of the genome, suggesting good genome continuity. The 10 kb filtering experiment further shows that short scaffolds have a minimal contribution to the overall assembly. Although 68 scaffolds were removed, only about 270 kb of sequence was lost, and the N50 and GC content remained unchanged. Biologically, this suggests that most of the genomic information is contained within longer, more continuous scaffolds, while the short sequences represent only a very small portion of the assembly. The ORF analysis identified 253 potential open reading frames, including a longest ORF of 825 bp. However, these ORFs should be considered potential coding regions rather than confirmed genes because additional evidence, such as similarity to known proteins or transcript evidence, is required for reliable gene annotation. Overall, the results provide a basic view of the genome structure and indicate that the **C. carcharias* assembly is largely composed of long, continuous genomic sequences.

# Screenshots

<img width="1340" height="641" alt="771107242_1450431397139812_198106691343060713_n (1)" src="https://github.com/user-attachments/assets/0fc742e4-62d5-4066-ae74-b6825fc626df" />

**Figure 1:** Raw Genome Fasta Preview

<img width="1343" height="612" alt="772792002_1772764317255321_1950728597668521826_n (1)" src="https://github.com/user-attachments/assets/1c181a01-d1f7-40ef-8de8-28dcd0188989" />

**Figure 2:** Original Assembly Statistics Summary

<img width="1340" height="626" alt="772534630_1495120192639606_5857706918921020744_n" src="https://github.com/user-attachments/assets/95b2ede2-5ecd-4bab-9473-42819ca09051" />

**Figure 3:** ORF Prediction Using getorf

# Galaxy Reproducibility & Workflow

**Shared Workflow Link:**

https://usegalaxy.org/u/romano_dave_lister/w/carcharodon-carcharias-genome-exploration-ii

**Platform**

UseGalaxy.org

**Description**

This workflow encapsulates all automated steps executed in Galaxy for the **Carcharodon carcharias* genome assembly exploration, length filtering, and ORF analysis.
