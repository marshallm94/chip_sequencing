# ChIP-Sequencing

My Capstone Project will utilize the [chipseq Data set](https://archive.ics.uci.edu/ml/datasets/chipseq) from the UCI Machine Learning Repository.


            chr1	33111786	33114894	noPeaks
            chr1	33114941	33116174	peakStart
            chr1	33116183	33116620	peakEnd
            chr1	33116633	33116755	noPeaks
            chr1	33116834	33118135	peaks


Each attribute is a non-negative integer representing the number of DNA sequence reads that has aligned at that particular region of the genome. Larger values are more likely to be peaks / positive, smaller values are more likely to be noise / negative.

## Questions

1. Are "Peaks" (protein - DNA interactions) more prevalent in certain chromosomes that others? If so, is this difference statistically significant?

    * ANOVA

2. How accurately can I predict the presence/absence of a Peak in a genomic position within a chromosome?

3. Is there a correlation between genomic position and Peak presence across chromosomes? (i.e. if there is a peak in chromosome 1, genomic position x to genomic position x + y, will there be a peak in chromosome Z, genomic position x to genomic position x + y)?
