Here, you will find folders of my projects for BIOMI6300 that I took in Spring 2025.

# MyProject

# I will re-running analyses by using the published data in this paper:
Cao, Qin, Xiaochuan Li, Huier Jiang, Han Wu, Zhijie Xie, Xiaoyi Zhang, Na Li, et al. “Ammonia Removal through Combined Methane Oxidation and Nitrification-Denitrification and the Interactions among Functional Microorganisms.” Water Research 188 (January 1, 2021): 116555. https://doi.org/10.1016/j.watres.2020.116555.
BioProject ID: PRJNA669203

# The goals of the project:
In the hollow-fiber membrane biofilm reactor with a coupling system, including methane oxidation coupled to nitrate denitrification (AME-D3), nitrite denitrification (AME-D2), and simultaneous nitrification and denitrification (ME-SND), analyzing microbial communities and functional bacteria based on high-throughput sequencing of the 16S rRNA and functional genes.

# Background:
1. The PCR primer set and procedures are shown in Table S1.
2. Purified amplicons were pooled at equimolar concentrations and paired-end sequenced (2 × 300 bp) on an Illumina MiSeq platform.
3. The processing of sequencing data was conducted using the Majorbio I-Sanger Cloud Platform (www.i-sanger.com). The raw 16S rRNA gene sequencing reads were demultiplexed, quality-filtered by fastp (v0.20.0) and merged by FLASH (v1.2.7) with the following criteria: 1) the 300 bp reads were truncated at any site receiving an average quality score of <20 over a 50 bp sliding window, and the truncated reads shorter than 50 bp were discarded, reads containing ambiguous characters were also discarded; 2) only overlapping sequences longer than 10 bp were assembled according to their overlapped sequence. The maximum mismatch ratio of overlap region is 0.2. Reads that could not be assembled were discarded; 3) samples were distinguished according to the barcode and primers, and the sequence direction was adjusted.
4. Operational taxonomic units (OTUs) with 97% similarity cutoff were clustered using UPARSE (v7.1), and chimeric sequences were identified and removed. For 16S rRNA gene sequences, the taxonomic lineage of each OTU representative sequence was assessed using the RDP Classifier algorithm against the Silva (release132, http://www.arb-silva.de) 16S rRNA database. For functional gene sequences, the taxonomic lineage was assessed against the NCBI RefSeq representative genome database.

# The region of the 16S gene that was used:
??? (cannot find it in the paper)
# The name and sequence of the primers:
515F (5'- GTGCCAGCMGCCGCGG - 3')
907R (5'- CCGTCAATTCMTTTRAGTTT - 3')

