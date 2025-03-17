# Chipseq

This section contains examples of ChIP-seq analysis scripts.

A typical ChIP-seq experiment has an immunoprecipitated sample and matched input sample used to set a threshold for background binding levels.

The general analysis steps are:
  + alignment of IP and input samples to the same reference genome
  + peak calling to identify statistical enrichment of IP target
  + visualization of binding positions on reference genome

For differential analysis, see RNA-seq section. Differential enrichment tools like DEseq can be applied to ChIP-seq reads. 
