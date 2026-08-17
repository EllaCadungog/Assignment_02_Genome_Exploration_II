# Assignment_02_Genome_Exploration_II
## Species:
*Canis latrans
## NCBI Accession:
GCA_034620425.1
## Objective
The objective of this study is to describe the basic structural features of a genome assembly, including N50, L50, genome size, sequence count, and GC content; examine sequence length distribution; apply a simple length filter and evaluate its effect on the assembly; explore open reading frames (ORFs) and distinguish predicted ORFs from confirmed genes; and document the Galaxy workflow in GitHub for reproducibility. 
## Galaxy Tools and Important Parameters
FASTA Statistics – Summarizes genome assembly statistics, including sequence count, total length, and GC content. Genome FASTA; default statistics settings.
Compute Sequence Length – Calculates the length of each contig to assess sequence-length distribution. Genome FASTA; sequence-length calculation.
Sort – Orders sequences based on their length. Sequence-length column; descending order.
Filter Sequences by Length – Removes short contigs below the selected length threshold. Minimum sequence-length threshold.
FASTA Statistics – Recalculates assembly statistics after filtering to evaluate changes in the assembly. Filtered FASTA; default statistics settings.
Filter FASTA – Produces a FASTA file containing sequences that meet the length criterion. Length-based filtering condition.
getORF – Identifies potential open reading frames (ORFs) as candidate protein-coding regions. Filtered FASTA; selected reading frames and start/stop codon criteria.
## Biological Interpretation 
The genome analysis of *Canis latrans provided information about its genome structure and sequence characteristics. I learned that the genome has a total length of approximately 2.34 billion base pairs (bp) and is classified at the chromosome level. It contains 213 contigs and 120 scaffolds, with scaffold sequences generally longer than contigs. The scaffold N50 of 64,494,502 bp indicates that a substantial portion of the genome is represented by relatively long assembled sequences. The GC content of 41.18% also describes the overall nucleotide composition of the genome. Application of the ≥10 kb filtering step showed that removing short sequences had little effect on the overall assembly. The total assembly length remained almost unchanged, and the N50 value also showed minimal change, indicating that sequences shorter than 10 kb contributed only a small portion of the genome assembly. The ORF analysis identified potential protein-coding regions; however, these ORFs cannot be directly classified as functional genes. Further evidence such as similarity to known genes, regulatory features, or experimental validation, is required to confirm gene function. The results demonstrate the usefulness of genome assembly statistics and ORF analysis in describing genome organization and identifying potential coding regions in *Canis latrans.
## Screenshots


## Galaxy Reproducibility & Workflow
Galaxy History: https://usegalaxy.org/u/EllaCadungog/w/Canis_latrans_genome_exploration_II 
