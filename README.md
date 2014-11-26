SiteSampler
===========

SiteSampler is a Java application that can sample the sites of a sequence alignment to produce replicate data sets. 

Sampling of the sites can be done in two ways:

  1. With replacement. Any particular site in the alignment can be sampled any number of times. This is equivalent to randomly shuffling the sites of the alignment.
  2. Without replacement. Any particular site in the alignment can only be sampled once. This is equivalent to randomly shuffling the sites of the alignment.

Site sampling can be performed within predefined data partitions. This might be useful if you wish to generate bootstrap replicates with the original data partitions preserved. 

Sequence labels (names) can also be randomly reassigned. This might be useful for certain randomisation tests, such as date-randomisation in heterochronous data sets.

Citation
--------

If you use SiteSampler in your research, please cite the following paper.
Ho SYW, and Lanfear R (2010) Improved characterization of among-lineage rate variation in cetacean mitogenomes using codon-partitioned relaxed clocks. *Mitochondrial DNA*, 21: 138-146.
