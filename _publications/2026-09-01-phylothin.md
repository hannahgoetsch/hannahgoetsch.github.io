---
title: "Hidden but expanding sampling bias distorts prokaryotic genome collections"
collection: publications
category: preprints
permalink: /publication/2026-phylothin
excerpt: 'This paper reveals and quantifies sampling bias in 402 prokaryotic species represented in NCBI and introduces a statistical tool to detect and assess this bias, with implications for the robustness of comparative genomic analyses.'
date: 2026-09-01
venue: 'bioRxiv'
softwareurl: 'https://github.com/fbaumdicker/phylothin'
paperurl:  'https://doi.org/10.64898/2026.09.29.755372'
citation: 'Götsch H and Baumdicker F. Hidden but expanding sampling bias distorts prokaryotic genome collections. Preprint on bioRxiv (September 2026)'
---

**Abstract**

Public genome collections underpin our understanding of bacterial diversity and the distribution of traits such as antibiotic resistance, and increasingly serve as training data for genomic foundation models. Their growing size promises an increasingly complete view of microbial genetic variation. However, these collections combine studies with different sampling priorities, often overrepresenting subgroups of closely related strains of particular interest. The resulting bias reduces effective information, and its consequences for diversity estimates and the value of further sequencing remain insufficiently quantified.
Here we show that accounting for this escalating sampling bias is essential for accurate gene frequency estimates and hints at greater genomic diversity than current data suggest. We propose to detect and reduce sampling bias based on phylogenetic relationships compared to expectations under random sampling, which, in contrast to dereplication and data reduction methods, preserves fine-scale diversity in large samples. Applied to 402 prokaryotic species in the NCBI genome database, our method PhyloThin indicates that the effective number of samples is 41% lower than the actual number but retains more than twice as many genomes as dereplication. Sampling bias varies substantially among species, showing that genome counts alone provide an incomplete measure of how well a species has already been characterized. PhyloThin thus turns biased, expanding genome collections into more representative samples for studying genome evolution and population genetic inference with implications for training genomic foundation models, pathogen surveillance, and the discovery of novel genetic functions.
