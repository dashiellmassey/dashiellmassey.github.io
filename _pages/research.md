---
layout: post
title: Research Interests
permalink: /research/
---

<h2> DNA replication timing in humans </h2>

Efficient and accurate replication of the genome is a crucial prerequisite to successful cell proliferation, and defects in replication are associated with cancer, premature aging syndromes, and inviability. In eukaryotes, replication initiates at many replication origins across the genome, which fire at different times during the S phase of the cell cycle. This spatiotemporal organization of origin firing is termed the "DNA replication timing program" and has been associated with GC content, gene expression, chromatin structure, and local mutation rate.

<br>
<br>

In my Ph.D. work, I have examined several aspects of the replication timing program, each time with an eye toward method development:
<br>

<h3> Single-cell variation in replication timing </h3>

<p style="text-align:center;"><img src="/images/Single-cell-Figure2a.jpg" width="700"></p>
<i>Top: A replication timing profile inferred from aggregated single-cell data is very similar to a profile inferred from assaying a bulk population of cells. Bottom: Pileups of replicated regions across cells reveal shared, localized positions of replication initiation.</i>

<br>
<br>

Replication timing has been observed to be highly reproducible across assays, yet the underlying mechanism(s) dictating its emergence are incompletely understood. To better understand what <i>kinds</i> of mechanisms might be responsible, we developed an approach to assay replication timing in thousands of single cells. We find that replication timing is remarkably consistent across cells, but nonetheless, cell-to-cell variability is evident. This variability is most compatible with the notion that replication timing arises from disparate origin firing probabilities rather than from some kind of global "metronome". <a href="https://doi.org/10.1101/2021.05.14.443897" target="_blank" rel="noopener noreferrer">Read the manuscript on Biorxiv. <i class='ai ai-biorxiv ai-lg'></i></a>

<h3> Inferring replication timing without cell sorting  </h3>

<p style="text-align:center;"><img src="/images/TIGER-Figure2.jpg" width="500"></p>
<i>An overview of the TIGER pipeline.</i>

<br>
<br>

Replication timing can be inferred from local fluctuations in read depth in whole-genome sequencing. However, a number of other factors (GC content, mappability biases, copy-number variations) can also impact read depth. Traditionally, these factors have been accounted for by sequencing a control sample of non-replicating (G1) cells in addition to a purified replication (S-phase) sample. I contributed to the development of TIGER (Timing Inferred from Genome Replication), a pipeline for simulating a control sample to correct these confounding factors from a single unsorted sample for more accurate replication-timing measurement.
<a href="https://doi.org/10.1093/bioinformatics/btab166" target="_blank" rel="noopener noreferrer">Read the paper in <i>Bioinformatics</i>. <i class='fa fa-link fa-lg'></i></a>

<h3> Replication timing of human centromeres  </h3>

<p style="text-align:center;"><img src="/images/Centromeres-Figure5.jpg" width="400"></p>
<i>An overview of the TIGER pipeline.</i>

<br>
<br>

Centromeres are large, repetitive stretches of DNA that serve a critical structural role during cell division: the centromere is the attachment point for the mitotic spindle, which physically pulls the replicated sister chromatids apart into two daughter cells. Because of their repetitive sequence content, it is difficult to study their replication timing by sequencing. However, in collaboration with the <a href = "https://smolka.wicmb.cornell.edu/">Smolka lab</a>, we showed that the centromeric model sequences included in the hg38 reference genome, coupled with paired-end sequencing, were sufficient to generate provisional replication-timing profiles for the majority of human chromosomes. In contrast to other heterochromatin (which replicates late in S phase), we find the centromeres replicate in mid-S phase and that their replication timing varies more between cell lines than other regions. <a href="https://doi.org/10.3390/genes10040269" target="_blank" rel="noopener noreferrer">Read the paper in <i>Genes</i>. <i class='fa fa-link fa-lg'></i></a>

<hr>
<h2> Previous Research </h2>

<h3> Double-strand break repair in Drosophila melanogaster </h3>
<b> PI: Jan LaRocque, Ph.D. (Georgetown University) </b><br>
The frequency of DNA double-strand breaks (DSBs) occurring from stalled replication forks alone is estimated to be ~50 breaks per cell per cell division. Each such event can give rise to large-scale mutation events that must be triaged into a repair pathway or the apoptotic pathway to maintain genomic stability. Under the guidance of Dr. Jan LaRocque at Georgetown University, I investigated the relationship between DSB repair genes and aging in a fruit fly model. The model allowed us to study this process in vivo, which is unusual in the field. Rad51 plays an essential role early in homologous recombination-mediated (HR) repair of DSBs, coating the resected free ends of the break and promoting the invasion of a homologous template for repair synthesis. We hypothesized that diminished Rad51 transcript levels might explain the decreased frequency of HR that had been previously measured in older flies. To test this, I induced DSBs in male flies at several ages via a heat-inducible endonuclease transgene. I isolated mRNA at multiple time points after DSB induction, reverse-transcribed to cDNA, and analyzed transcript levels of Rad51 relative to two housekeeping genes by quantitative PCR. Contrary to our expectations, Rad51 expression increases with advancing age, even prior to DSB formation. Based on my protocol, other members of the lab were able to show similar results for other mRNA transcripts encoding repair proteins in the same pathway, suggesting that the HR machinery is upregulated in older age. I was actively involved throughout the project in designing experiments, selecting and troubleshooting protocols, performing fly genetics and molecular assays, analyzing the data, and writing the manuscript, now published in Aging Cell.

<h3> Predicting failed sternal re-approximation in neonates </h3>
<b> PI: Catherine Allan, M.D. (Boston Children's Hospital) </b><br>
Swelling of the heart and lungs is a common, but often dangerous, occurrence in the aftermath of open-heart surgery. Due to their small size, neonates are particularly vulnerable to such swelling and its consequences. Therefore, it is common practice to leave the chest cavity open in the immediate post-operative period to allow swelling to reduce and permit direct monitoring of the heart. However, the consequences of delayed sternal re-approximation on infection and mortality are a matter of debate among cardiac intensivists. As an undergraduate, I worked under the guidance of Dr. Catherine Allan, a pediatric cardiologist in the Cardiac ICU at Boston Children’s Hospital, to investigate predictors of negative outcomes from this procedure. I reviewed relevant medical literature to generate a list of variables that might influence outcomes and wrote research proposals to the hospital Scientific Review Committee and Institutional Review Board. Once approved, I compiled retrospective data from medical records for the previous five years (~300 patients). We found that patients requiring lower levels of mechanical ventilation had significantly lower odds of poor outcome, whereas hemodynamic parameters were not predictive of outcome. This work was presented as a poster at the American Heart Association Scientific Sessions in 2014 and a first-author manuscript is being prepared for submission.

<h3> Peripheral nerve regeneration in aging mice </h3>
<b> PI: Clifford Woolf, M.B. B.Ch. Ph.D (Harvard Medical School) </b><br>
Injuries to the nervous system are estimated to impact 90,000 people every year. In the peripheral nervous system, the axons of injured neurons undergo a process known as Wallerian degeneration, wherein they lose their myelin sheath and are recycled by macrophages. As an undergraduate, I spent a summer in the lab of Dr. Clifford Woolf at Harvard’s F.M. Kirby Neurobiology Center, studying a mouse model of sciatic nerve injury. Specifically, I worked with a graduate student to explain why axon regeneration declines with advancing age. I approached this question within biochemical and behavioral frameworks. Using an anti-neurofilament antibody, I stained sections of sciatic nerves harvested from mice five days after a surgically induced sciatic nerve injury. I demonstrated that incompletely degenerated axons persisted at sites more distal to the injury in two-year-old mice than in eight-week-old mice. I also assayed the recovery of sensation in the hindpaw following sciatic nerve injury in two transgenic mouse lines with enhanced axon regenerative capacity. In the pilot study, we found no improvement in recovery in these two-year-old mice relative to wild-type mice of the same age. Both experiments supported further investigation of the hypothesis that the aging phenotype results from impaired clearance of the injured tissue rather than a decline in regenerative capacity per se.
