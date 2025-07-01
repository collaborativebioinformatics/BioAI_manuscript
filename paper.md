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
    orchid: 0009-0007-7752-6990
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
    orcid:
    affiliation: 37
  - name: Paulina Kaczyńska
    orcid: 0000-0002-8690-8436
    affiliation: 16
  - name: Pu Kao
    orchid:
    affiliation: 36
  - name: Fahad Ali Khan
    orcid: 
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
    orcid:
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
    orcid: -
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
    index:29
  - name: Institute of Zoology and Biomedical Research, Faculty of Biology, Jagiellonian University, Kraków, Poland
    index: 30
  - name: Institute of Zoology and Biomedical Research, Faculty of Biology, Jagiellonian University, Kraków, Poland
    index: 31
  - name: Bioinformatics Laboratory, Research and Development cell & Parul Institute of Applied Sciences 
Parul University.India
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


   
date: 
bibliography: paper.bib
authors_short:  \emph{et al.}
group: 
event: 
git_url: 
---

#### \* These authors contributed equally

# Introduction


## Code Availability

Team name: link


## Virus Susceptibility


## Graph-Based Tuning


# Flow diagrams

## Virus Susceptibility

![Figure 1. Virus Susceptibility workflow.](./figures/virus_susceptibility_workflow.png)\
**Figure 1.** Virus Susceptibility workflow.

## Graph Based Tuning

![Figure 2.Graph Based Tuning workflow.](./figures/graph_based_tuning_workflow.png)\
**Figure 2.** Graph Based Tuning workflow.

## VCFs to Knowledge Graphs

![Figure 3. VCFs to Knowledge Graphs workflow.](./figures/vcfs_to_knowledge_graphs_workflow.png)\
**Figure 3.** VCFs to Knowledge Graphs workflow.

## Knowledge Graph Based Validation

![Figure 4. Knowledge Graph Based Validation workflow.](./figures/knowledge_graphs_based_validation_workflow.png)\
**Figure 4.** Knowledge Graph Based Validation workflow.

# Methods

## Virus Susceptibility

The Jupyter notebooks used in this work are located in the scripts/ directory on the project GitHub page (https://github.com/collaborativebioinformatics/virussusceptibility).
The CORD-19 dataset [@wang_cord-19_2020] contains metadata and embeddings that are generated from Covid-19-related articles. We retrieved the embeddings with references to the original articles from the dataset. The embeddings were generated with SPECTER (Scientific Paper Embeddings using Citation-informed TransformERs) [@cohan_specter_2020], which is a pre-trained language model that can be used to generate high-quality article representations. The training of the model and its implementation details can be found in the original article [@cohan_specter_2020]. We created a vector database with 'insert', 'query', and 'retrieve' methods (https://www.linkedin.com/pulse/vector-databases-demystified-part-2-building-your-own-adie-kaye/). Then, we inserted the CORD-19 embedding into the vector database.
We downloaded SPECTER from GitHub (https://github.com/allenai/specter) and used it to create an embedding for an example query (specifically, "What combinations of features predispose cohorts to virus susceptibility?"). Next, we compared the embedding of the example query with all of the embeddings in the dataset and ranked the comparisons according to cosine similarity. Thus, the highest-ranked paper retrieved should be the closest contextual match to the example query (i.e., the highest ranked paper should have the highest measure of cosine similarity).
Remark: Cosine similarity turned out to be unsuitable for high-dimensional vector comparison. For this reason we reduced the dimensionality of vectors with random projection (http://people.ee.duke.edu/{\textasciitilde}lcarin/p93.pdf; https://towardsdatascience.com/random-projection-in-python-705883a19e48); specifically, Gaussian random projection (https://scikit-learn.org/stable/modules/generate/sklearn.random\_projection.{GaussianRandomProjection}.html). Then, we used cosine similarity to search for articles that showed  the highest relevance with respect to the query.
As a proof of principle, we created a dataset of ten articles and embedded the articles SPECTER [@cohan_specter_2020]. The embeddings were subsequently inserted into a vector database. Lastly, we tested the retrieval of the most relevant articles. The corresponding workflow is provided on the project GitHub page (https://github.com/collaborativebioinformatics/virussusceptibility/scripts/query_custom_dataset.ipynb).

## Graph Based Tuning
Firstly, 38,617 drug-relationship-target triples were downloaded from the Therapeutic Target Database [@zhou_ttd_2023]. A knowledge graph was generated from 20 sample triples and is shown in **Figure 5**. Then, we developed an algorithm to preprocess such triplets into a prompt-response format for LLAMA2 (see “inputdata.txt”). For instance, a sample prompt would be “[INST] Tell me more about the drug with ID D07OAC. [/INST]” and its corresponding response would be “Drug D07OAC is an inhibitor to target protein S5A2_HUMAN.”

![Figure 5. Knowledge graph generated from 20 sample triples.](./figures/kg_20_triplets.png)\
**Figure 5.** Knowledge graph generated from 20 sample triples.



Traditional fine-tuning approaches generally require retraining the last layers of the LLM, which is computationally-expensive. To overcome this, we leveraged QLora [@dettmers_qlora_2023], an efficient parameter tuning method that uses Low Rank Adaptation and Double Quantization to reduce training and inference costs. The Llama 2-7b [@touvron_llama_2023] model was fine-tuned on the preprocessed data for three epochs. Training was done on a NVIDIA Tesla A100 and training time was approximately three hours. Our fine-tuned model LLAMA2Glendalorian has been deployed on HuggingFace (https://huggingface.co/tminh/llama-2-7b-glendalorian). Finally, our fine-tuned model was benchmarked against ChatGPT (https://chat.openai.com) and the original Llama 2 model using the prompt “What can the drug with ID D0Y6UB do?”. The results are shown in the results section.

## VCFs to Knowledge Graphs

We first acquired data from the TCGA COAD-CPTAC dataset, mentioned above and previously described in Vasaikar et. al., 2019 [@vasaikar_proteogenomic_2019]. This dataset consists of a MAF file (pre-converted from a VCF file) that provides data about subjects, the genetic variants they carry, and various annotations for those variants including: what genes they mapped to, the functional impact of those variants, and ClinVar annotations for variants that had a known clinical impact. 

To ensure data harmonization, especially when dealing with the potential integration of data across cohorts (although not implemented in this instance, but is feasible within this framework), we obtained MONDO concepts for various diseases from the MONDO database. Similarly,  we acquired HUGO concepts for each gene. This approach enabled us to establish a unified representation for genes and diseases across various cohorts, addressing potential heterogeneity issues that are most likely to emerge across nodes in the graph between cohorts and where harmonization is critical.

To reduce the number of variants included within the dataset as a proof-of-concept, we filtered the genes contained within the graph to only include those with ClinVar-annotated variants across the entire cohort. However, the same framework can be applied without this filtering step to substantially enrich the graph and enable possible link prediction and inference tasks (of which genes may be associated with disease, for example). The code to implement this is included in the repository (https://github.com/collaborativebioinformatics/vcfs2kgs) as a Python notebook `tcga_rdf.ipynb` that can be run directly so long as the data is downloaded and provided, and a BioPortal API key is acquired (which can be done for free).

## Knowledge Graph Based Validation

We accomplished evaluation of the LLMs by constructing an induced subset of an existing knowledge base known as DisGeNet, which is structured in a relational form as a knowledge graph. The induced subset consisted of three single nucleotide polymorphisms (SNP, aka variants) and the diseases associated with those variants, and it comprised the set of SNPs for which we tested this approach.

For each SNP, we acquired a body of literature from PubMed by using the SNP name as a keyword for a PubMed search. The abstracts from the papers obtained were provided for each SNP to the model and the model was prompted to construct subject-predicate-object triplets from these abstracts. We evaluated this approach on multiple open-source or publicly available LLMs, including Vicuna-7b, Vicuna-13b, llama2-7b, codellama2-7b, and GPT-4. We used three overarching prompts for each of these models:

Prompt 1: “User: Create subject predicate subject logic triplets using some motor vehicles and output it as a subject predicate subject logic triplet. An example subject predicate subject triplet could be Biliary Atresia - results in - biliary obstruction. Create 10 of these triplets.”

Prompt 2: “User: Create subject predicate subject logic triplets using some genes and their disease associations and output it as a subject predicate subject logic triplet. An example subject predicate subject triplet could be Biliary Atresia - results in - biliary obstruction. Create 10 of these triplets.”

Prompt 3: “Create subject predicate subject logic triplets using singlue nucleotide polymorphism rs rs113993960 and their disease associations and output it as a subject predicate subject logic triplet. An example subject predicate subject triplet could be Biliary Atresia - results in - biliary obstruction. Create10 of these triplets.”

We then compared the results of these models to the DisGeNet associations. The code for all of these can be found in the repository (https://github.com/collaborativebioinformatics/kgbasedvalidation/) with documentation in the repository describing the required dependencies and installation instructions. 

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


