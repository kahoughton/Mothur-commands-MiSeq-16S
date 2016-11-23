# Mothur-commands-MiSeq-16S

These commands will process MiSeq 16S rDNA amplicon data from Argonne National Laboratories. 
Samples were amplified using 515f-806r updated primers (Caporaso et al. 2012 & Apprill et al. 2015) for paired-end (251x251bp MiSeq) 16S 
rDNA sequencing. Sample data were received in four files 1) R1.fastq (forward reads) 2) R2.fastq (reverse reads) 3) I1.fastq (index file) 
and 4) *.txt file (mapping file). All samples are included in the files (i.e. they are not demultiplexed) with the primer's removed, but 
the barcodes are still emedded in the index file. The forward primers were barcoded for this approach.  

The commands follow the mothur MiSeq Sop at https://www.mothur.org/wiki/MiSeq_SOP (Schloss et al. 2013). 

Files required in the folder containing the mothur.exe: 

1) R1.fastq
2) R2.fastq
3) I1.fastq
4) Oligos file (will need to be generated from the mapping file)
5) Silva alignment file "silva.nr_v123.align" http://www.mothur.org/wiki/Silva_reference_files 
6) Silva taxonomy file "silva.nr_v123.tax" http://www.mothur.org/wiki/Silva_reference_files 
7) Mock community alignment file "HMP_MOCK.v35.align" http://www.mothur.org/wiki/454_SOP#Removing_.22contaminants.22




References 

Apprill A, McNally S, Parsons R, Weber L. 2015. Minor revision to V4 region of SSU rRNA 806R gene primer greatly increases detection 
of SAR11 bacterioplankton. Aquatic Microbial Ecology. 75:129-137

Caporaso JG, Lauber CL, Walters WA, Berg-Lyons D, Huntley J, Fierer N, Owens SM, Betley J, Fraser L, Bauer M, Gormley N, Gilbert JA, 
Smith G, Knight R. 2012. Ultra-high-throughput microbial community analysis on the Illumina HiSeq and MiSeq platforms. ISME J.

Kozich JJ, Westcott SL, Baxter NT, Highlander SK, Schloss PD. (2013): Development of a dual-index sequencing strategy and curation 
pipeline for analyzing amplicon sequence data on the MiSeq Illumina sequencing platform. Applied and Environmental Microbiology. 
79(17):5112-20
