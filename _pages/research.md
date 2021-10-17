---
layout: post
title: Current Research Interests
subtitle: <a href="/past-research">To read about my previous research, click <u>here</u></a>.
permalink: /research/
---

<h2> DNA replication timing in humans </h2>

Accurate and efficient replication of the genome is a crucial prerequisite to successful cell proliferation, and defects in replication are associated with cancer, premature aging syndromes, and cell death. In eukaryotes, replication initiates at many replication origins across the genome, which fire at different times during the S phase of the cell cycle. This spatiotemporal organization of origin firing is termed the "DNA replication timing program" and has been associated with GC content, gene expression, chromatin structure, and local mutation rate.

<br>
<br>

In my Ph.D. work, I have examined several aspects of the replication timing program, each time with an eye toward method development:
<br>

<h3> Single-cell variation in replication timing </h3>

<p style="text-align:center;"><img src="/images/Single-cell-Figure2a.jpg" width="700"></p>
<i>Top: A replication timing profile inferred from aggregated single-cell data is very similar to a profile inferred from assaying a bulk population of cells. Bottom: Pileups of replicated regions across cells reveal shared, localized positions of replication initiation.</i>

<br>
<br>

Replication timing has been observed to be highly reproducible across assays, yet the underlying mechanism(s) dictating its emergence are incompletely understood. To better parse out what <i>kinds</i> of mechanisms might be responsible, we developed an approach to assay replication timing in thousands of single cells. We find that replication timing is remarkably consistent across cells, but nonetheless, cell-to-cell variability is evident. This variability is most compatible with the notion that replication timing arises from disparate origin firing probabilities rather than from some kind of global "metronome". 
<a href="https://doi.org/10.1101/2021.05.14.443897" target="_blank" rel="noopener noreferrer">Read the manuscript on Biorxiv. <i class='ai ai-biorxiv ai-lg'></i></a>

<hr style="height:1px; border:none; color:#4A1486; background-color:#4A1486;">
<h3> Inferring replication timing without cell sorting  </h3>

<p style="text-align:center;"><img src="/images/TIGER-Figure2.jpg" width="500"></p>
<i>An overview of the TIGER pipeline.</i>

<br>
<br>

Replication timing can be inferred from local fluctuations in read depth in whole-genome sequencing. However, a number of other factors (GC content, mappability biases, copy-number variations) can also impact read depth. Traditionally, these factors have been accounted for by sequencing a control sample of non-replicating (G1) cells in addition to a replicating (S-phase) sample. I contributed to the development of TIGER (<i>T</i>iming <i>I<i>nferred from <i>Ge</i>nome <i>R</i>eplication), a pipeline for simulating a control sample to correct these confounding factors in a single unsorted sample. 
<a href="https://doi.org/10.1093/bioinformatics/btab166" target="_blank" rel="noopener noreferrer">Read the paper in <i>Bioinformatics</i>. <i class='fa fa-link fa-lg'></i></a>

<hr style="height:1px; border:none; color:#4A1486; background-color:#4A1486;">
<h3> Replication timing of human centromeres  </h3>

<p style="text-align:center;"><img src="/images/Centromeres-Figure5.jpg" width="400"></p>
<i>Average replication timing of centromeres for five cell lines.</i>

<br>
<br>

Centromeres are large, repetitive stretches of DNA that serve a critical structural role during cell division: the centromere is the attachment point for the mitotic spindle, which physically pulls the replicated sister chromatids apart into two daughter cells. Because of this repetitive sequence content, it is difficult to study centromere replication timing by sequencing. However, in collaboration with the <a href = "https://smolka.wicmb.cornell.edu/" target="_blank" rel="noopener noreferrer">Smolka lab</a>, we showed that the centromeric model sequences included in the hg38 reference genome, coupled with paired-end sequencing, were sufficient to generate provisional replication-timing profiles for the majority of human chromosomes. In contrast to other heterochromatin (which replicates late in S phase), we find the centromeres replicate in mid-S phase and that centromeric replication timing is hyper-variable between cell lines, relative to 
  other genomic regions. 
<a href="https://doi.org/10.3390/genes10040269" target="_blank" rel="noopener noreferrer">Read the paper in <i>Genes</i>. <i class='fa fa-link fa-lg'></i></a>
