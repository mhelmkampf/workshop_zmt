*** This is an example readme file for the DatAlumni workshop data ***



0_metadata
----------

Basic sample metadata (sample id, collection date, species, coordinates)
* does not represent sequenced specimen(s) below *



1_rawdata
---------

WGS raw read data of Hypoplectrus puella (barred hamlet), sequenced on Illumina HiSeq 2500 from paired-end 2 × 151-base pair (bp) library with 300 bp insert size

Hpue_raw300_F.fastq.gz   # first 75000 forward reads
Hpue_raw300_R.fastq.gz   # first 75000 reverse reads

md5/   # checksums of above raw read files



2_processed
-----------

Quality- and adapter-trimmed reads from 1_rawdata, using cutadapt v3.4

Hpue_raw300_F_trim.fastq.gz
Hpue_raw300_R_trim.fastq.gz

qc/   # read QC reports obtained with FastQC v0.11.9, raw and trimmed (_trim) data



3_assembly
----------

Hpue_assembly_01_LG12.fas.gz   # Hypoplectrus puella genome assembly, linkage group (chromosome 12), soft-masked, Genbank accession GCA_900610375.1

Mcap_assembly_v4_10ln.fas      # Montipora capitata (brown rice coral) genome assembly (version 4), first 10000 lines



4_annotation
------------

Mcap_genes_v7_1000.gff   # Montipora capitata gene models (AUGUSTUS annotation run 7), first 1000 genes
