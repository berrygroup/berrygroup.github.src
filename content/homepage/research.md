---
title: "Research"
weight: 3
header_menu: true
---

We are interested in the mechanisms used by cells to regulate gene-specific and global RNA abundance -- ranging from **epigenetic memory** and cellular decision-making to **global RNA metabolism** in the context of cellular physiology. We seek to generate a *quantitative* understanding of these processes. 

Our research methodology is a combination of 'top-down' (data-driven) and 'bottom-up' (hypothesis-driven) approaches. We make extensive use of **high-throughput microscopy** and automated image analysis, which enables measurement of detailed quantitative cellular phenotypes (for example, the abundance of specific proteins or RNAs) across large cell populations. Resulting datasets are then analysed using a variety of methods from **data science**. We complement these image-based approaches with **functional genomics** experiments, based on next-generation sequencing, which provide exquisite genomic resolution, and perform perturbation experiments including **genome and epigenome-editing** to test specific hypotheses.

Projects in the lab are often underpinned by construction of minimal mathematical models at the molecular level, which we use as a tool for exploring possible explanations of experimental results and prioritising future experiments.

We believe that the best science happens in the overlap between fields. We strive to build a diverse team and foster collaborations across fields and disciplines.

![Effects on gene expression of CRISPR-KO using smFISH](images/FISHquant-01.png)
{{< figurecaption >}}
Cell-to-cell variability in gene expression, quantified using single molecule FISH.
{{< /figurecaption >}}

#### Stability and plasticity of epigenetic memory

The chromatin of individual genetic loci can be set into molecular 'states' that control the expression of the underlying genes, and in some cases even instruct their own inheritance -- acting as local epigenetic memory elements. When necessary, however, chromatin can also be reliably switched from one state to another -- by processes that involve coordinated changes to the histone modifications, accessibility of regulatory sequences, and expression states of the underlying genes.

We are interested in the interplay between gene-specific diffusible regulatory factors (e.g. transcription factors), which tend to have continuous (analogue) control over gene expression, and heritable chromatin states (e.g. Polycomb-repressed chromatin), which tend to promote bi-modal (digital) stable expression states. To study these processes we use in vitro differentiation of epithelial cells from human induced pluripotent stem cells.

**Further reading:**  
[Yang, Berry *et al.*, Science, 2017](http://dx.doi.org/10.1126/science.aan1121)  
[Berry *et al.*, Cell Systems, 2017](http://dx.doi.org/10.1016/j.cels.2017.02.013)

![Integrating local and diffusible signals at chromatin](images/Modelling-01.png)
{{< figurecaption >}}
Mechanistic model of self-perpetuating active and repressed chromatin states. 
{{< /figurecaption >}}

#### Global control of RNA metabolism

Mammalian cells coordinate RNA production rates with cell size to ensure RNA concentration homeostasis. We discovered that this process relies on adapting transcription rates according to nuclear mRNA concentration, so that overabundance of nuclear mRNA leads to transcriptional repression. This mechanism involves mRNA-based regulation of the activity of RNA Polymerase II, which in turn determines polymerase abundance. We are interested in further dissecting the interplay between the transcriptional machinery, nuclear RNA export and RNA degradation that act in concert to ensure robust mRNA concentration homeostasis.

**Further reading:**  
[Berry *et al.*, bioRxiv, 2021](https://doi.org/10.1101/2021.05.17.444432)  

![Feedback from RNA production](images/transcription_feedback.png)

#### High-dimensional cellular phenotyping

![4i](images/4i.gif#floatrighthalf)
In recent years, technological advances have made it possible to visualise tens to hundreds of proteins in single cells. This has brought with it the ability to accurately quantify the high-dimensional relationships between protein abundances and their modification states, as well as the cell-to-cell variability of their subcellular localisation and co-localisation.

We use [Iterative Indirect Immunofluorescence Imaging](https://doi.org/10.1126/science.aar7042) (4i) throughout our research as a method to reveal the high-dimensional stucture of cellular heterogeneity present in populations, and also to the comprehensively evaluate changes to cellular phenotypes that occur in the context of cellular differentiation and upon changes to gene expression -- both for individual genes and also more global changes to RNA production rates.

High-dimensional datasets with spatial resolution are extraordinarily rich in information, however much of this information is not easy to interpret using existing approaches. In collaboration with [Lucas Pelkmans](https://www.pelkmanslab.org) and [Fabian Theis](https://www.helmholtz-muenchen.de/icb/research/groups/theis-lab/overview/index.html), we are also currently developing new computational image analysis workflows to facilitate analysis of these data at the subcellular, cellular and population scales.

**Further reading:**  
[Gut *et al.*, Science, 2019](https://doi.org/10.1126/science.aar7042)  

![Multiplexed Cell Units](images/MCU.001.jpg)

{{< figurecaption >}}
Applying pixel-clustering approaches to highly-multiplexed 4i image data identifies subcellular structures in an unbiased manner. In this case, we focused on the nucleus: revealing organelles such as nuclear speckles, Cajal bodies, PML bodies and the nucleolus.
{{< /figurecaption >}}
