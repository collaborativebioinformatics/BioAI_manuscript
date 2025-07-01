---
title: 'Artificial Intelligence Approaches for Computational Biology: Highlights from the first BioAI Hackathon at University of Warsaw'
tags:
  - biohackathon
  - deep learning
  - graph neural networks
  - large language models
  - biological networks
  - splicing, microbiome
  - drug discovery
  - chromatin organisation
  - multi-omics
  - single-cell

authors:
  - name: Rahaf M. Ahmad*
    orcid: 0000-0002-7531-5264
    affiliation: 10
  - name: Michał Denkiewicz*
    orcid: 0000-0001-8890-9988
    affiliation: 14
  - name: Rishika Gupta*
    orcid: 0000-0001-6246-3906
    affiliation: 27
  - name: Sachin Gadakh*
    orcid: 0000-0002-7524-7898
    affiliation: 2
  - name: Jędrzej Kubica*
    orcid: 0000-0001-7037-3900
    affiliation: 6
  - name: Alishba Nadeem*
    orcid: 0000-0003-4194-5337
    affiliation: 18
  - name: Alicja M. Olszewska*
    orcid: 0000-0002-3995-8166
    affiliation: 3
  - name: Federico Rossi*
    orcid: 0000-0002-3058-9448
    affiliation: 8
  - name: John Adedeji
    orcid: 00009-0004-1257-4551
    affiliation: 19
  - name: Abolhassan Bahari
    orcid: 0009-0003-8417-2327
    affiliation: 4
  - name: Krzysztof H. Banecki
    orcid: 0000-0001-9573-0804
    affiliation: 1, 2
  - name: Nilabja Bhattacharjee 
    orcid: 0009-0007-7752-6990
    affiliation: 22
  - name: Joanna Borkowska
    orcid: 0009-0003-5503-1314
    affiliation: 2
  - name: Jacob R. Bumgarner
    orcid: 0000-0002-0387-9263
    affiliation: 13
  - name: Kirtan Dave
    orcid: 0000-0003-3886-8895
    affiliation: 32
  - name: German Demidov
    orcid: 0000-0001-9075-4276
    affiliation: 5
  - name: Konrad Józef Dębski
    orcid: 0000-0001-5949-9211
    affiliation: 23
  - name: Ritwik Ganguly
    orcid: 0009-0000-4626-3760
    affiliation: 22
  - name: Radosław Gersz
    affiliation: 37
  - name: Paulina Kaczyńska
    orcid: 0000-0002-8690-8436
    affiliation: 16
  - name: Pu Kao
    affiliation: 36
  - name: Fahad Ali Khan
    affiliation: 26
  - name: Mikolaj Kocikowski
    orcid: 0000-0001-7396-9005
    affiliation: 7
  - name: Maciej Kowalski 
    orcid: 0009-0005-1155-197X
    affiliation: 24
  - name: Halina Krzystek
    orcid: 0009-0004-8363-0039
    affiliation: 35
  - name: Sabrina Kwak
    orcid: 0009-0007-9588-4513
    affiliation: 17
  - name: David Liu
    orcid: 00000-0000-0000-0000
    affiliation: 20
  - name: Pranjul Mishra
    orcid: 0009-0003-5503-1314
    affiliation: 1
  - name: Diya Patidar
    orcid: 0009-0007-0238-2363
    affiliation: 34
  - name: Sreeram Chandra Murthy Peela
    orcid: 0000-0003-3379-6263
    affiliation: 22
  - name: Aung Myat Phyo
    orcid: 0009-0009-2893-3631
    affiliation : 29
  - name: Weronika Plichta
    affiliation: 25
  - name: Ammara Saleem
    orcid: 0009-0004-3754-8907
    affiliation: 9
  - name: Palash Sethi
    orcid: 0009-0003-5423-8313
    affiliation: 15
  - name: Mukul Sherekar
    orcid: 0000-0002-3638-9420
    affiliation : 28
  - name: Jatin Shrinet
    orcid: 0000-0002-4274-613X
    affiliation: 33
  - name: Anna Simonyan
    orcid: 0000-0001-8760-2298
    affiliation: 21 
  - name: Asha Ajithakumari Sobhanakumar
    orcid: 0000-0000-0000-0000
    affiliation: 11 
  - name: Aleksandra Sobieska
    affiliation: 39, 40, 41
  - name: Marek Sokołowski
    orcid: 0009-0009-3958-3526
    affiliation: 1, 24
  - name: Gobikrishnan Subramaniam
    orcid: 0009-0001-4118-7591
    affiliation: 12
  - name: Rafał Kazimierz Wóycicki
    orcid: 0000-0001-7991-7150
    affiliation: 30
  - name: Dariusz Plewczynski
    orcid: 0000-0002-3840-7610
    affiliation: 1, 2
  - name: Ben Busby
    orcid: 0000-0001-5267-4988
    affiliation: 38
    
affiliations:
  - name: Laboratory of Bioinformatics and Computational Genomics, Faculty of Mathematics and Information Science, Warsaw University of Technology, Koszykowa 75, 00-662, Warsaw, Poland
    index: 1
  - name: Laboratory of Functional and Structural Genomics, Centre of New Technologies, University of Warsaw, Stefana Banacha 2c, 02-097, Warsaw, Poland
    index: 2
  - name: Laboratory of Brain Imaging, Nencki Institute of Experimental Biology of the Polish Academy of Sciences, Pasteur 3 Str, Warsaw, Poland
    index: 3
  - name: High Institute for Research and Education in Transfusion Medicine, Iranian Blood Transfusion Organization, Tehran, Iran
    index: 4
  - name: Institute of Medical Genetics and Applied Genomics, University of Tübingen, Tübingen, Germany
    index: 5
  - name: Univ.‬ ‭Grenoble‬ ‭Alpes,‬ ‭CNRS,‬ ‭UMR‬ ‭5525,‬ ‭TIMC / BCM,‬ ‭38000‬ ‭Grenoble,‬ ‭France
    index: 6
  - name: kocikowski.com
    index: 7
  - name: SOPHiA GENETICS, Rolle, Switzerland
    index: 8
  - name: Department of Biochemistry, Quaid-I-Azam University, Islamabad, Pakistan
    index: 9
  - name: Department of Genetics and Genomics, College of Medicine and Health Sciences, United Arab Emirates University
    index: 10
  - name: jacobbumgarner.com
    index: 13
  - name: Warsaw University of Technology, Warsaw, Poland 
    index: 14
  - name: Department of Biology, University of Florida, Florida, USA
    index: 15
  - name: Institute of Fundamental Technological Research, Polish Academy of Sciences, Warsaw, Poland
    index: 16
  - name: Linear Diagnostics Ltd. , Birmingham, UK
    index: 17
  - name: School of Medical Science, Zhengzhou University, China
    index: 18
  - name: College of Health Sciences, Osun State University, Nigeria
    index: 19
  - name: CareDx, Brisbane, California, USA
    index: 20
  - name: Laboratory of biotesting and biomarkers, A.V. Dumansky Institute of Colloid and Water Chemistry, NAS of Ukraine 
    index: 21
  - name: Department of Computational Biology, IIITD, New Delhi, India 
    index: 22
  - name: FORK SYSTEMS Konrad Dębski, Duchnice, Poland
    index: 23
  - name: Inter-faculty Individual Studies in Mathematics and Natural Sciences, University of Warsaw, Poland
    index: 24
  - name: Warsaw University of Technology, Poland
    index: 25
  - name: IISER - Kolkata, India
    index: 26
  - name: CiTIUS ~ Centro Singular de Investigación en Tecnoloxías Intelixentes, Spain
    index: 27
  - name: Johns Hopkins University
    index: 28
  - name: Family Genomics Research Group, Department of Biology, Maynooth University, Ireland
    index: 29
  - name: Institute of Zoology and Biomedical Research, Faculty of Biology, Jagiellonian University, Kraków, Poland
    index: 30
  - name: Institute of Zoology and Biomedical Research, Faculty of Biology, Jagiellonian University, Kraków, Poland
    index: 31
  - name: Bioinformatics Laboratory, Research and Development cell & Parul Institute of Applied Sciences, Parul University, India
    index: 32
  - name: International Centre for Genetic Engineering and Biotechnology (ICGEB), New Delhi, India
    index: 33
  - name: Carnegie Mellon University , USA
    index: 34
  - name: IQVIA Laboratories, Durham, North Carolina, USA
    index: 35
  - name: Graduate Institute of Biomedical Electronics and Bioinformatics, National Taiwan University, Taiwan
    index: 36
  - name: University of Warsaw MISMaP College, Warsaw, Poland
    index: 37
  - name: NVIDIA, Santa Clara, CA USA
    index: 38
  - name: School of Informatics, University of Edinburgh, Edinburgh, UK
    index: 39
  - name: School of Physics and Astronomy, University of Edinburgh, Edinburgh, UK
    index: 40
  - name: Institute of Epigenetics and Stem Cells, Helmholtz Center Munich, Munich, Germany
    index: 41
   
date: May 15, 2025
bibliography: paper.bib
authors_short: Ahmad R. M., Denkiewicz M., Gupta R., Gadakh S., Kubica J., Nadeem A., Olszewska A. M., Rossi F. \emph{et al.}
event: BioAI Hackathon at the University of Warsaw 2025
git_url: https://github.com/SFGLab
---

#### \* These authors contributed equally

# Abstract

The BioAI Hackathon at the Centre of New Technologies at the University of Warsaw convened 43 international researchers to collaboratively explore artificial intelligence (AI) approaches for solving complex challenges in computational biology. Nine interdisciplinary and multi-institutional teams addressed the following problems: disease-gene prioritization, microbiome analysis, drug-protein interactions, alternative splicing prediction, chromatin architecture study and toxicological profiling. Using cutting-edge tools such as graph neural networks (GNNs), large language models (LLMs), and multi-omics integration frameworks, participants developed scalable and reproducible analytical pipelines. The results include a disease gene prioritization framework using GNNs, a microbiome dynamics analysis for poultry health prediction and the construction of chromatin structure-aware regulatory networks leveraging Hi-C and scRNA-seq data. All projects follow the open science principles and display translational potential. This hackathon underscores the transformative role of AI in biomedicine and the value of collaborative, time-bounded innovation for accelerating discovery in life sciences.

# Introduction

Recent advances in genomics, transcriptomics, epigenetics and systems biology have enabled an unprecedented capacity to collect and analyze biological data. These high-throughput technologies generate vast datasets that hold the key to understanding human health and disease. However, the volume, complexity, and heterogeneity of biomedical data pose significant challenges. To address them, artificial intelligence (AI), particularly machine learning (ML) and deep learning (DL) algorithms, have become increasingly useful in extracting meaningful biological insights.

During the BioAI Hackathon at the University of Warsaw, participants explored novel AI-based solutions, including graph neural networks and large language models, for the following challenges: disease-gene prioritization, microbiome dynamics analysis, drug discovery for rare disease, study of splicing regulation, epigenomics data harmonization, investigation of chromatin reorganization and toxicological profiling. All projects are publicly available on GitHub: https://github.com/SFGLab 

## Code Availability

Team 1: Prioritizing disease-associated genes using graph neural networks: https://github.com/SFGLab/Team1_Gene_Prioritization_GNN 

Team 2: AI-Driven Microbiome Analysis for Predicting Poultry Health and Performance: https://github.com/SFGLab/Team2_AI_Microbiome_Poultry

Team 4: AI-Driven Prediction of Drug-Protein Interactions for Rare Diseases: https://github.com/SFGLab/Team4_AI_Drug_Targets_Rare_Diseases

Team 5: Phasing structural variants using phased aligned data: https://github.com/SFGLab/SvPhaser

Team 6: Leveraging LLMs for alternative splicing studies: https://github.com/SFGLab/Team6_LLM_Splicing_Studies

Team 7: Harmonization and imputation of epigenomics data – exposome: https://github.com/SFGLab/EpiXposome

Team 8: Discovering cell cycle phase-specific chromatin conformation changes based on single cell Hi-C and multi-omics data: https://github.com/SFGLab/Team8_PhaseSpecific_Chromatin_Changes

Team 9: Advanced Modeling of Toxicological Profiles: https://github.com/SFGLab/Team9_Toxicological_Profiles

Team 10: Developing graph neural networks for gene regulation discovery: https://github.com/SFGLab/GNN4GRN-3D 

## Team 1: Prioritizing disease-associated genes using graph neural networks

Medical genomics aims at finding genes related to diseases. Experimental studies are often laborious and expensive, therefore bioinformatics methods are useful in the prioritization of candidate disease-associated genes (Shi et al. 2020). Recent bioinformatics methods based on machine learning, such as graph neural networks (GNNs), are increasingly popular (Ata et al. 2021; Zitnik et al. 2024). GNNs are expected to offer improved performance by recognizing complex network patterns and leveraging additional biological information. The increasing number of GNN-based methods requires further understanding of how they compare to the state-of-the-art network propagation methods such as Random Walk with Restart (Baptista et al. 2022; Köhler et al. 2008) or PageRank (Page et al. 1999; Chung and Zhao 2010). Compared to network propagation, the usability of GNNs is often limited due to high computational requirements and issues with interpretability. During the hackathon, we aimed at comparing the performance of graph neural networks with network propagation methods (Cowen et al. 2017). As for the use case, we focused on genes involved in hereditary ataxia, a group of rare neurodegenerative disorders characterized by progressive loss of coordination and balance (Perlman 1993; Park et al. 2022).

## Team 2: AI-Driven Microbiome Analysis for Predicting Poultry Health and Performance

The gut microbiome plays a critical role in shaping poultry growth, nutrient absorption, immune function, and disease resistance, making it a promising target for data-driven performance optimization strategies in livestock production (Kogut and Arsenault 2016). Traditional microbiome analyses, however, often fall short in capturing the high-dimensional complexity and dynamic variability of microbial ecosystems. To address this, Team 2 developed an AI-powered pipeline that integrates next-generation sequencing data with advanced machine learning models to predict poultry health and performance outcomes. By leveraging both 16S rRNA amplicon and shotgun metagenomic datasets, the approach aims to uncover microbial biomarkers and compositional patterns linked to productive traits, laying the groundwork for precision microbiome engineering in poultry farming (Gilbert et al. 2016).

## Team 4: RARExDrug: AI-Driven Prediction of Drug-Protein Interactions for Rare Diseases

RARExDrug aims to bridge the huge disparity between millions of existing drug-like molecules and the lack of treatment in nine-tenth of rare diseases. By leveraging existing drug-protein interaction databases and rare disease-protein databases, we predicted novel drug-protein binding interactions. Furthermore, we employed ProteinBERT, a state-of-the-art transformer-based protein language model pretrained on ~106 million sequences from UniRef90 using a masked language modeling (MLM) technique. Remarkably, this model uses a dual-scale embedding architecture—integrating residue-level embeddings and sequence-level embeddings—with global-attention layers of linear complexity to appropriately capture both local and global contextual information across entire protein sequences, enabling efficient and scalable modeling of protein function and interactions.. This enabled our prototype machine learning model to process extremely long protein sequences—which are often infeasible for standard models—and extract biologically meaningful residue-level representations. We applied this framework to large-scale datasets using the rare disease cystic fibrosis as a test case to explore functional protein-ligand interactions. Additionally, we externally validated the obtained potential drug candidate results by comparing the structure of identified ligands with existing experimentally validated therapeutic alternatives. The abundance of well-curated ClinVar data on pathogenic variants of Cystic Fibrosis and its clear genotype-phenotype correlation makes it advantageous for training this model. Ultimately, RARExDrug promises to accelerate drug discovery for rare diseases, reducing both timeline and cost.

## Team 5: Phasing structural variants using phased aligned data

Understanding genetic variation is fundamental to deciphering genome function and disease. Haplotypes, sets of co-inherited DNA variations, are crucial for elucidating gene function, disease susceptibility, and population genetics. Concurrently, Structural Variants (SVs)—large-scale genomic alterations—significantly contribute to genetic diversity and are implicated in numerous human diseases. However, determining the haplotype phase of SVs, assigning each to its parental chromosome, is substantially more challenging than for smaller variants like SNPs, largely due to SV size and complexity. While SNP phasing methods are mature and modern sequencing can provide phased alignments, a critical gap exists in accurately transferring this phase information to co-located SVs. Phased SVs are vital for identifying compound heterozygosity and understanding allele-specific effects, thereby improving genomic studies. This project aims to bridge this gap by developing a novel method that integrates information from pre-phased SNPs and phased read alignments to accurately estimate SV haplotypes, offering a valuable contribution to the genomics toolkit.

## Team 6: Leveraging LLMs for alternative splicing studies

Alternative splicing (AS) is a vital post-transcriptional mechanism in eukaryotic gene regulation that enables a single gene to produce multiple mRNA transcripts and protein isoforms. This biological process expands the functional capacity of the genome, playing a critical role in tissue-specific gene expression, cellular identity, and developmental processes. However, dysregulation of AS has been strongly linked to cancer progression, contributing to key hallmarks such as uncontrolled proliferation, resistance to apoptosis, angiogenesis, and metastasis. Given its complexity and relevance, accurate detection and prediction of splicing events—especially tumor-specific ones—are crucial for understanding disease mechanisms and identifying potential biomarkers or therapeutic targets. This project aims to leverage LLMs in the process of splicing, thereby increasing the efficiency and accuracy (as seen in Fig. Team 6-1).

## Team 7: Harmonization and imputation of epigenomics data – exposome

The exposome, a term coined to describe the totality of environmental exposures from conception onwards, is increasingly recognized for its role in shaping health outcomes, including the development of chronic diseases and cancers (Vineis and Barouki 2022). Among the various factors that contribute to the exposome, epigenetic modifications such as DNA methylation and microRNA (miRNA) expression have been shown to be particularly influential in regulating gene expression without altering the DNA sequence itself (Danieli et al. 2024). The interaction between the exposome and these epigenetic markers is a burgeoning area of research, with previous studies suggesting that environmental factors can induce epigenetic changes that may lead to disease susceptibility (Ogunjobi et al. 2024). In the face of growing evidence linking environmental exposures to chronic diseases and cancers, our project aims to leverage advanced machine learning techniques, specifically bidirectional recurrent neural networks (BiRNNs), to explore the intricate relationship between the exposome and epigenomics. By integrating diverse datasets from different, we seek to uncover how environmental variables influence epigenetic markers, potentially offering novel insights into disease development and progression.

## Team 8: Discovering cell cycle phase-specific chromatin conformation changes based on single cell Hi-C and multi-omics data

Chromatin undergoes dynamic structural reorganisation which may drive chromatin organization throughout the cell cycle. Our project aims to comprehensively integrate multi-omics datasets—including gene expression, chromatin accessibility, and contact maps—to advance the understanding of cell cycle phase-specific chromatin dynamics. Coupled with 3D genome modeling, our approach seeks to uncover novel and distinct chromatin conformational changes along the trajectory of cell cycle progression and other genomic processes such as cellular maturation. We employ state-of-the-art 3D modeling techniques that incorporate temporal information from the cell cycle, alongside cutting-edge methods for multi-omics integration, clustering, and pattern recognition. This combined strategy is designed to reveal common principles and patterns underlying chromatin structural organization within the cell nucleus.

## Team 9: Advanced Modeling of Toxicological Profiles

Estrogen related receptors (ERRs) are one of the first orphan nuclear receptors identified (Aubert et al. 2013). ERRs are required for high-energy production in response to the environmental and physiological challenges. They play an important role in the control of cellular energy, including mitochondrial biogenesis, gluconeogenesis, and oxidative phosphorylation (Aubert et al. 2013; Audet-Walsh and Giguére 2015), with signaling implicated in metabolic disorders like type 2 diabetes (Audet-Walsh and Giguére 2015), with EER-alpha (subfamily of EERs) identified as an adverse marker for breast cancer progression (Huang 2016).
Screening and identifying environmental compounds that perturb the EER signaling pathways could provide information for potential preventive measures in treating the mentioned metabolic diseases (Aubert et al. 2013). Predicting their activity continuously allows for a quantitative assessment of receptor activation or inhibition, reflecting real biological responses more accurately than binary (toxic/nontoxic) labels, additionally allowing for information on dose-response that is not present in binary toxicity prediction.

## Team 10: Developing graph neural networks for gene regulation discovery

The Gene regulatory networks (GRNs) play a pivotal role in revealing the extended regulatory relationship between genes and transcription factors, which forms the basis of describing complex biological processes and modes of gene regulation for the therapy of human diseases (Pratapa et al. 2020). With revolutions in the single-cell RNA sequencing (scRNA-Seq) and chromosome conformation capture technologies, we can perform the simultaneous analysis of gene expression and 3D chromatin (Cremer and Cremer 2019; Rao et al. 2014; Zheng et al. 2019). Graph neural networks (GNNs) provided natural architecture for modeling network-like data with the ability to integrate various additional features and choose between a range of architecture variants (Zhou et al. 2020), most notably, the Graph Attention Networks (GATs), (Veličković et al. 2017). multilayered genomic data types from cutting-edge omics technologies . The aim of this project is to provide an extensible framework for training GNN models on custom datasets, adding the ability to adjust and provide custom features by the user without the need to rewrite training code. We build on previous approaches (Paul et al. 2024) in particular by incorporating chromosome conformation capture data (Hi-C), to improve the GRN predictions from scRNA-Seq to bridge graph-based machine learning and 3D Genomics.

# Methods







# Discussion and/or Conclusion

## Virus Susceptibility

Building and querying the vector database that was previously created using the embeddings from the CORD-19 dataset didn't show the expected result (articles related to the topic of the query). This highlights a possibility for improvement in data and code reproducibility. Building our own custom vector database from the CORD-19 articles and querying it yields articles relevant to the query. Example results for a query “hypertension” show provided search results that included an article related to cardiovascular diseases. This result can be found on the GitHub page. Querying the vector database with the embedded query takes only ~190 ms.

## Graph Based Tuning

The results show that neither ChatGPT nor the original Llama model 2 were able to relate specific drug (ID: D0Y6UB) to the target protein (see **Figures 6 and 7**), whereas our LLAMA2Glendalorian model suggested a putative target protein (POL_HV1B1) for the drug with the corresponding binding relationship (see **Figure 8**). In most of our experiments, the improvement from the 13B models over the 7B models indicates that use of larger models – or leveraging smaller models – is warranted for questions in the biomedical domain that were appropriate for deep learning models, such as those involving many-to-many comparisons and finding contextualised etiologies.  

![Figure 6. Response from ChatGPT to the benchmark prompt.](./figures/chat_gpt_response.png)\
**Figure 6.** Response from ChatGPT to the benchmark prompt.

![Figure 7. Response from the Llama 2 model to the benchmark prompt.](./figures/llama2_response.png)\
 **Figure 7.** Response from the Llama 2 model to the benchmark prompt.


![Figure 8. Response from the LLAMA2Glendalorian model to the benchmark prompt.](./figures/llama2glendalorian_response.png)\
**Figure 8.** Response from the LLAMA2Glendalorian model to the benchmark prompt.


## VCFs to Knowledge Graphs

The underlying relationships within the graph were constructed based on cohort-specific relationships (for example, whether patients have colon adenocarcinoma or not) as well as information acquired from existing clinical knowledge bases. A schema of the ideal graph construction has been provided (see **Figure 9**), with dashed edges representing planned but not implemented (due to time constraints) relationships. Concepts contained within the graph constructed using this framework from the CPTAC dataset are shown below (see **Table 1**) and embedded within **Figure 9**.

**Table 1.** Concepts for the graph construction.

|   Concept   |   Name                                          |   Number |
|:-----------:|:-----------------------------------------------:|:--------:|
|   Node Type |   Sample                                        |   93     |
|   Node Type |   Gene                                          |   3302   |
|   Node Type |   Cancer Type                                   |   1      |
|  Edge Type  | isCancerTypeOf (connects Sample -> Cancer Type) |  93      |
|  Edge Type  | hasHugoSymbol (connects Sample -> Gene)         |  15285   |

![Figure 9. A schema of an ideal graph construction.](./figures/ideal_graph_construction.png)\
**Figure 9.** A schema of an ideal graph construction.


## Knowledge Graph Based Validation

The single nucleotide polymorphisms/variants that we evaluated are shown below (see **Table 2**). These pairs were collected using the DisGeNET database, as described above. Some examples of the responses from the models tested are provided below in **Figure 10**. Notably, many of the prompts including the abstracts exceeded the recommended context window for some of these models, and we note that prompts approaching the context window recommendation or exceeding it tended to lead to substantially worse performance. 
 
**Table 2.** Evaluated SNPs.

| SNP             |                   Diseases                   |
|:---------------:|:--------------------------------------------:|
| rs113993960     | BRONCHIECTASIS                               |
|                 | Stenosis of duodenum                         |
|                 | Congenital bilateral aplasia of vas deferens |
|                 | Hereditary pancreatitis                      |
|                 | Recurrent pancreatitis                       |
|                 | Cystic Fibrosis                              |
| rs199473282     | LONG QT SYNDROME 3                           |
|                 | Brugada Syndrome (disorder)                  |
|                 | Brugada Syndrome 1                           |
|                 | Long QT Syndrome                             |
|                 | Hereditary bundle branch system defect       |
| rs121909211     | Plaque, Amyloid                              |
|                 | Familial Amyloid Polyneuropathy, Type V      |
|                 | Corneal dystrophy                            |
|                 | Corneal deposit                              |
|                 | Corneal Dystrophy, Lattice Type IIIA         |
|                 | Dystrophy, granular                          |
|                 | Reis-Bucklers' corneal dystrophy             |
|                 | Corneal guttata                              |
|                 | Lattice corneal dystrophy Type I             |
|                 | Amyloidosis                                  |
|                 | Neoplasms                                    |
|                 | Granular Dystrophy, Corneal                  |
|                 | Thiel-Behnke corneal dystrophy               |
|                 | Stromal Dystrophies, Corneal                 |
|                 | Avellino corneal dystrophy                   |

![Figure 10. Outputs from the tested LLMs.](./figures/outputs_from_tested_llms.png)\
**Figure 10.** Outputs from the tested LLMs.


# Conclusion and Future Directions

The advent of large language models (LLMs) has provided a unique opportunity in the biomedical domain. LLMs have shown the capability in outputting code or file formats given natural language prompts, synthesising data, and extracting relevant information from corpus. Below we provide future Directions for the Teams Involved in this Hackathon.

## Virus Susceptibility

-	Create a vector database of 1M CORD-19 articles
-	Develop a more efficient method to generate queries for the vector database
-	Use the vector database to ask complex scientific questions:
-	"What combinations of features predispose cohorts to viral infections?"
-	"Which combinations differentially predispose individuals to chronic disease post infection?”

## Graph Based Tuning

-	Fine-tune LLMs onto additional biomedical KGs:
-	DrugBank/ROBOKOP 
-	Protein-protein interactions
-	Drug-drug interactions

## VCFs to Knowledge Graphs

-	Construct sample-sample edges from a genetic relatedness matrix, automatically identifying duplicates and related individuals across cohorts
-	Create disease-disease edges based on co-occurrence and different levels of granularity
-	Include gene-disease edges from DisGeNet
-	Include additional node attributes, e.g.: original cohort, sex, age on the sample level; or gene type (protein-coding, noncoding, pseudogene) on the gene level

## Knowledge Graph Based Validation

-	Compress prompts by summarizing abstracts further to reach context windows
-	Create an end-to-end pipeline using DisGeNET
-	Implement dynamic parameter tuning and queryable database formatting
-	Implement data structures for comparing SPO objects: 
-	Q/A implement comparison of data structures 
-	Implement key word predicates to limit the scope of keywords

If you or your colleagues are interested in collaborating on these or similar projects in a hackathon or professional setting, please contact ben.busby@gmail.com. If you have technical questions or issues, please put an issue into one of the github repositories listed below.  

# Data and software availability

All code is provided in the following GitHub repositories, which may include additional links to data repositories and Jupyter Notebooks.

-	https://github.com/collaborativebioinformatics/virustrajectory
-	https://github.com/collaborativebioinformatics/graphbasedtuning
-	https://github.com/collaborativebioinformatics/vcfs2kgs
-	https://github.com/collaborativebioinformatics/kgbasedvalidation

# Acknowledgements

## Carnegie Mellon Libraries

For providing space – in both Pittsburgh, PA and Palo Alto, CA – as well as refreshments and other logistical support. The authors would especially like to thank Tom Hughes, Melanie Gainey, and Leigh Mason.

## DNAnexus

Thanks to DNAnexus for providing computing resources for the Hackathon, as well as the time of BB and CL.  

## Grant funding

Van Q. Truong is supported by the Microsoft Research PhD Fellowship and ACM SIGHPC Computational and Data Science Fellowship. Rachit Kumar is supported by the Training Program in Computational Genomics grant from the National Human Genome Research Institute to the University of Pennsylvania under award number T32HG000046.

# References


