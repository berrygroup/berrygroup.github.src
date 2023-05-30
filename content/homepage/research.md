---
title: "Research"
weight: 3
header_menu: true
---

We are interested in the mechanisms used by cells to regulate gene-specific and global RNA abundance -- ranging from **epigenetic memory** and cellular decision-making to **global RNA metabolism** in the context of cellular physiology. We seek to generate a *quantitative* understanding of these processes. 

Our research methodology is a combination of 'top-down' (data-driven) and 'bottom-up' (hypothesis-driven) approaches. We make extensive use of **high-throughput microscopy** and automated image analysis, which enables detailed measurement of quantitative cellular phenotypes (for example, the abundance and localisations of specific proteins or RNAs) across large cell populations. Resulting datasets are then analysed using a variety of methods from **data science**. We complement these image-based approaches with **functional genomics** experiments, based on next-generation sequencing -- providing exquisite genomic resolution, and use perturbation experiments including **genome and epigenome-editing** to test specific hypotheses.

![Effects on gene expression of CRISPR-KO using smFISH](images/methodology_schematic-01.png)

Projects in the lab are often underpinned by construction of minimal **mathematical models** at the molecular level, which we use as a tool for exploring possible explanations of experimental results and prioritising future experiments.

We believe that the best science happens in the overlap between fields. We strive to build a diverse team and foster collaborations across fields and disciplines.

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

Mammalian cells coordinate RNA production rates with cell size to ensure RNA concentration homeostasis. We discovered that this process relies on adapting transcription rates according to nuclear mRNA concentration, so that overabundance of nuclear mRNA leads to transcriptional repression. This mechanism involves mRNA-based regulation of the activity of RNA Polymerase II, which in turn determines polymerase abundance. We are interested in further dissecting the interplay between the transcriptional machinery, nuclear RNA export and RNA degradation factors that act in concert to ensure robust mRNA concentration homeostasis.

**Further reading:**  
[Berry *et al.*, Cell Systems, 2022](https://doi.org/10.1016/j.cels.2022.04.005)  

![Feedback from RNA production](images/transcription_feedback.png)

#### High-dimensional cellular phenotyping

![4i](images/4i.gif#floatrighthalf)
In recent years, technological advances have made it possible to visualise tens to hundreds of proteins in single cells. This has brought with it the ability to accurately quantify the high-dimensional relationships between protein abundances and their modification states, as well as the cell-to-cell variability of their subcellular localisation and co-localisation.

We use [Iterative Indirect Immunofluorescence Imaging](https://doi.org/10.1126/science.aar7042) (4i) throughout our research to comprehensively evaluate changes to cellular phenotypes in the context of cellular differentiation and upon perturbation of RNA metabolism. These datasets are extraordinarily rich in information, however much of this information is not easy to interpret using existing approaches. In collaboration with [Lucas Pelkmans'](https://www.pelkmanslab.org) and [Fabian Theis'](https://www.helmholtz-muenchen.de/icb/research/groups/theis-lab/overview/index.html) research groups, we have developed a new computational image analysis workflow called CAMPA to facilitate analysis of these data across different perturbations, at the subcellular, cellular and population scales.

**Further reading:**  
[Spitzer, Berry *et al.*, Nat Methods, 2023](https://doi.org/10.1038/s41592-023-01894-z)  
[CAMPA on GitHub](https://github.com/theislab/campa)

![Consistent subcellular landmarks](images/CSL-01.jpg)

{{< figurecaption >}}
Applying pixel-clustering approaches to highly-multiplexed 4i image data identifies subcellular structures in an unbiased manner. In this case, we focused on the nucleus: revealing organelles such as nuclear speckles, Cajal bodies, PML bodies and the nucleolus.
{{< /figurecaption >}}
