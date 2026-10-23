8# SWYNEX Biological Dataset Selection Project Title 

Selection and Exploration of the Mycobacterium tuberculosis H37Rv Genome Using NCBI
# Project Overview 

This project focuses on selecting a biological dataset from the National Center for Biotechnology Information (NCBI) database. The selected dataset is the complete reference genome of Mycobacterium tuberculosis strain H37Rv.

The project introduces biological database searching, genome sequence retrieval, accession numbers, and sequence comparison using BLAST.

# Objective To identify a suitable biological dataset using NCBI.

# Organism Information 

Organism name: Mycobacterium tuberculosis H37Rv

Organism type: Bacterium

Biological significance: It is a reference strain of the bacterium that causes tuberculosis (TB).

NCBI Genome Details Parameter Information Database NCBI Nucleotide / RefSeq Reference sequence accession NC_000962.3 Assembly name ASM19595v2 Assembly accession (GenBank) GCA_000195955.2 Assembly accession (RefSeq) GCF_000195955.2 Genome size 4,411,532 base pairs (bp) Genome type Double-stranded DNA (dsDNA) Chromosome structure One circular chromosome GC content Approximately 65.6% 

Official NCBI links:

Reference genome: https://www.ncbi.nlm.nih.gov/nuccore/NC_000962.3 Genome assembly: https://www.ncbi.nlm.nih.gov/datasets/genome/GCA_000195955.2/ 5. Dataset Selection Rationale 

Mycobacterium tuberculosis H37Rv was selected because it is a well-studied reference strain with an available, annotated genome sequence. Its genome can be explored using bioinformatics databases and sequence-analysis tools.

This dataset is suitable for learning about genome organization, nucleotide sequences, genomic annotations, and sequence similarity.

# Methodology 
Step 1: Open NCBI 

The National Center for Biotechnology Information (NCBI) website was opened to search for biological genome data.

Step 2: Search for the Organism 

The name Mycobacterium tuberculosis was entered in the NCBI Genome database.

Step 3: Select the Genome Assembly 

The reference genome assembly for strain H37Rv was selected.

Step 4: Open the Reference Sequence 

The RefSeq accession NC_000962.3 was opened to examine the complete genome record.

Step 5: View the FASTA Sequence 

The FASTA format was used to view the nucleotide sequence. FASTA represents biological sequences using a header and a sequence written in nucleotide letters.

Step 6: Perform BLAST 

The BLAST tool was used to compare the selected sequence with sequences available in the database.

Step 7: Examine a BLAST Match 

A result for Mycobacterium tuberculosis strain CT2018-00091, chromosome complete genome, was opened for further examination.

Step 8: View the Graphics 

The Graphics view was opened to explore the sequence record and its annotated genomic features.

Note: H37Rv is the reference genome selected for this project. CT2018-00091 is a separate strain record viewed during BLAST analysis.

# Results and Observations 

The NCBI reference record provides access to the complete H37Rv genome sequence and its associated genomic annotations.

The genome has a length of 4,411,532 base pairs and contains double-stranded DNA arranged as one circular chromosome. Its GC content is approximately 65.6%.

The BLAST search provided a sequence match associated with another Mycobacterium tuberculosis strain. The result can be examined using alignment statistics, including percentage identity, query coverage, and E-value.

BLAST result details: Add the actual percentage identity, query coverage, E-value, and alignment length from your BLAST results page. Do not estimate these values.

# Conclusion 

This project provided an introduction to biological dataset selection and genome exploration using NCBI. The H37Rv reference genome was identified, its basic genomic characteristics were recorded, and its nucleotide sequence was explored in FASTA format. BLAST was used to investigate sequence similarity with another strain record.

The project demonstrates the usefulness of biological databases and bioinformatics tools in accessing and exploring genomic information.

# References 
National Center for Biotechnology Information (NCBI). Mycobacterium tuberculosis H37Rv, complete genome. RefSeq accession NC_000962.3. NCBI Genome Assembly Database. Mycobacterium tuberculosis H37Rv, assembly ASM19595v2. NCBI BLAST: https://blast.ncbi.nlm.nih.gov/Blast.cgi 

# SWYNEX Task 2: Data Cleaning and Basic Analysis

# Project Title

Basic Genome Analysis of Mycobacterium tuberculosis H37Rv Using Python

# Objective

To analyze the reference genome sequence obtained from NCBI using Python in Google Colab.

# Dataset Information

- **Organism:** Mycobacterium tuberculosis H37Rv
- **Accession Number:** NC_000962.3
- **Genome Size:** 4,411,532 base pairs
- **Genome Type:** Double-stranded DNA
- **Source:** NCBI Nucleotide Database

# Tools Used

- NCBI Nucleotide Database
- Google Colab
- Python

# Methodology

1. Retrieved the H37Rv reference genome from NCBI in FASTA format.
2. Uploaded the FASTA file into Google Colab.
3. Used Python to read and analyze the nucleotide sequence.
4. Counted the A, T, G and C nucleotide bases.
5. Calculated the genome length and GC content.
6. Checked for ambiguous bases represented by N.

# Results

The genome sequence was analyzed using Python. The genome length was checked, nucleotide counts were calculated, and GC content was estimated from the uploaded sequence.

**Note:** Insert your actual nucleotide counts, GC content and ambiguous-base count from your Colab output here.

# Conclusion

This task provided practical experience in retrieving biological data, processing FASTA sequences, and performing basic genome analysis using Python. These methods are useful in bioinformatics and genomic research.

# References

- NCBI Reference Genome: https://www.ncbi.nlm.nih.gov/nuccore/NC_000962.3
- Google Colab: https://colab.research.google.com/

