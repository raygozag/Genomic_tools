Genomic_tools
=============

Provides a  broad set of tools used for processing and quality control of genomic data.

-- Fasta Commands

These are unix like commands for managing fasta files. Up to now the require python 2.6+ and biopython. Soon a c++ implementation will be available.

      * fasta_head: prints to STDOUT the top N fasta records in a fasta file. 
      usage:
         fasta_head <<file.fasta>> N
      
      * fasta_grep: prints to STDOUT the records that contain the query string in the fasta record identifier. As of now it implements exact substring matching but i'm unsure whether it actually supports regex epressions. Will be implemented soon.

      usage:
      fasta_grep <<file.fasta>> <<query string>>

