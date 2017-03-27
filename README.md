bio_utilities
==============

My collection of bioinformatics-related utility scripts

Installation
------------
Add the `bin` folder to your `$PATH` variable.

Utilities
---------
 * `bitwise_flag` - Describe bitwise FLAG from SAM file
 * `create_random_reads` - Naively generate *N* random sequences from a
each record in a reference FASTA file (requires Biopython)
 * `find_in_bed` - Find intervals in a BED file given chr, start, and end
 * `split_fasta` - Split large FASTA file into smaller files

Unit tests
----------
    make test
