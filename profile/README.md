![TAGC logo](https://tagc.univ-amu.fr/sites/default/files/styles/actu_300x200/public/2024-11/logo_tagc_sans_fond_0.png)

# TAGC | Theories and Approaches of Genomic Complexity

**Research software, analysis workflows and reproducible genomics.**

TAGC is an Inserm and Aix-Marseille Université research laboratory (UMR 1090) in Marseille, France. We investigate genome regulation, biological networks, evolution and the genetic basis of complex traits.

This page brings together code developed by TAGC researchers and collaborators, hosted across laboratory, team and individual GitHub accounts. Archived code and supporting datasets are available through Zenodo and Recherche Data Gouv.

[Website](https://tagc.univ-amu.fr/) · [Zenodo community](https://zenodo.org/communities/tagc) · [Contact](https://tagc.univ-amu.fr/en/contact)

[Tools and databases](#tools-and-databases) · [Code accompanying studies](#code-accompanying-studies) · [Teaching](#teaching) · [Using and citing our work](#using-and-citing-our-work)

## Tools and databases

### Genome regulation and transcriptomics

| Resource | Purpose | Code and resources |
| --- | --- | --- |
| MUFFIN | Analysis of functional sequencing data. | [GitHub](https://github.com/pdelangen/Muffin) · [Archived code](https://zenodo.org/records/11066512) |
| ReMap | Processing workflows for integrated transcriptional regulator binding maps. | [Pipeline](https://github.com/remap-cisreg/remap-pipeline) · [ReMap 2022 data](https://zenodo.org/records/10527088) · [mESC ChIP-seq bigWig tracks, mm10 (Recherche Data Gouv)](https://doi.org/10.57745/GEIHVN) |
| pygtftk | Toolkit for working with GTF genome annotations. | [GitHub](https://github.com/dputhier/pygtftk) |
| libgtftk | Library supporting GTF annotation processing. | [GitHub](https://github.com/dputhier/libgtftk) |
| SciGeneX | Co-expression gene module detection in single-cell and spatial transcriptomics. | [GitHub](https://github.com/dputhier/scigenex) · [Reproduction environment](https://zenodo.org/records/12801381) |
| LedPred | Supervised prediction of regulatory sequences from sequence features and genomic annotations. | [GitHub](https://github.com/aitgon/LedPred) · [Study data](https://github.com/aitgon/LedPreddat) |
| TAGOOS | Scoring intronic and intergenic variants using regulatory annotations and machine learning. | [GitHub](https://github.com/aitgon/tagoos) |

### Networks, interactions and complex traits

| Resource | Purpose | Code and resources |
| --- | --- | --- |
| Clust&See 3 | Cytoscape app for network clustering, module exploration and annotation enrichment. | [GitHub](https://github.com/fafa13/ClustnSee-3) · [Paper](https://doi.org/10.12688/f1000research.152711.2) · [Archived code](https://zenodo.org/records/13220735) |
| mimicINT | Inference of microbe-host protein interactions. | [Workflow](https://github.com/TAGC-NetworkBiology/mimicINT) · [Web application code](https://github.com/TAGC-NetworkBiology/mimicINTweb) · [Paper](https://doi.org/10.12688/f1000research.160063.1) |
| BactMentha | Processing of host-bacterium protein interaction data and associated database code. | [Workflow](https://github.com/TAGC-NetworkBiology/BactMentha) · [Database](https://github.com/TAGC-NetworkBiology/BactMentha-DB) |
| epiMEIF | Detection of high-order epistatic interactions using mixed-effect conditional inference forests. | [GitHub](https://github.com/TAGC-NetworkBiology/epiMEIF) |
| ChagasDB | Chagas disease database project. | [GitHub](https://github.com/TAGC-ComplexDisease/ChagasDB) |

### Open reading frames and gene evolution

| Resource | Purpose | Code and resources |
| --- | --- | --- |
| DESwoMAN | Detection and comparative analysis of newly expressed non-canonical ORFs. | [GitHub](https://github.com/AnnaGrBio/DESWOMAN) · [Paper, 2026](https://doi.org/10.1093/nargab/lqag114) · [Archived code](https://zenodo.org/records/22146842) |
| MetamORF | Database construction workflows for human and mouse open reading frames. | [GitHub](https://github.com/TAGC-NetworkBiology/MetamORF) |

### Sequencing and workflow infrastructure

| Resource | Purpose | Code |
| --- | --- | --- |
| VTAM | Validation and taxonomic assignment of metabarcoding data. | [GitHub](https://github.com/aitgon/vtam) |
| WopMars | Workflow management. | [GitHub](https://github.com/aitgon/wopmars) |
| MetaWorkflow TGML | Sequencing analysis workflows from the TGML platform. | [GitHub](https://github.com/TGMLplatform/mw-tgml) |

## Code accompanying studies

Analysis repositories and archives supporting individual papers and manuscripts. Publication status and citations are documented in the linked resources.

| Study or project | Analysis focus | Code and supporting resources |
| --- | --- | --- |
| ExonEnhancer | Identification and characterisation of exonic enhancers across species. | [GitHub](https://github.com/benoitballester/ExonEnhancer) · [Code v3, 2026](https://zenodo.org/records/18255062) · [Data](https://zenodo.org/records/17208730) |
| InteractORF | Analysis scripts for *A functional landscape of human microproteins*, including interaction networks and functional inference. | [GitHub](https://github.com/TAGC-NetworkBiology/InteractORF) |
| RNA Pol II Atlas | Intergenic transcription at RNA polymerase II binding sites in normal and cancer tissues. | [GitHub](https://github.com/benoitballester/Pol2Atlas) · [Input data](https://zenodo.org/records/7785393) · [Output data (Zenodo)](https://zenodo.org/records/8091826) · [Output data (Recherche Data Gouv)](https://doi.org/10.57745/ONGXGD) |
| Epromoter-regulated gene clusters | Identification of Epromoter-like clusters using RNA-seq and ChIP-seq data. | [GitHub](https://github.com/Spicuglia-Lab/Epromoter-like-cluster-pipeline) · [Study data](https://zenodo.org/records/14211588) |
| ArchiHeart | Genetic architecture of natural variation in cardiac performance in flies. | [GitHub](https://github.com/TAGC-NetworkBiology/ArchiHeart) · [Data and containers](https://zenodo.org/records/5582846) |
| RAINET-RNA | RAINET-RNA study resources. | [GitHub](https://github.com/TAGC-Brun/RAINET-RNA) |
| biomarkersChagas | Chagas disease biomarker study. | [GitHub](https://github.com/TAGC-ComplexDisease/biomarkersChagas) |
| epiChagas | Chagas disease epistasis study. | [GitHub](https://github.com/TAGC-ComplexDisease/epiChagas) |

### Additional analysis code on Zenodo

These archives provide study-specific scripts or computational environments alongside data.

| Study | Available code | Archive |
| --- | --- | --- |
| Cardiac aging and Pdp1/dHLF in Drosophila | Variant annotation, analysis and figure scripts; code archive v2 released September 2026. | [Analysis code](https://zenodo.org/records/22747522) · [Companion GWAS resources](https://zenodo.org/records/18911553) |
| Structural comparison of type III effectors | Scripts and data for comparing known and candidate effectors with FoldSeek. | [Code and data](https://zenodo.org/records/11951539) |
| HuRI network neighbourhood analysis | Containerised code and random networks for random-walk-with-restart analysis of host proteins targeted by microbial effectors. | [Code and data](https://zenodo.org/records/12743976) |
| Cardiac responses to high-fat and high-sugar diets in flies | Figure data, including an R script for the transcriptomic heatmaps in Figure 2. | [Data and heatmap script](https://zenodo.org/records/19725994) |

## Teaching

- [CENTURI Summer School 2021](https://github.com/benoitballester/centuri-summer-school-2021)
- [Inserm workshop: Machine Learning in Biology](https://github.com/benoitballester/inserm-ML-workshop-266)

## Using and citing our work

Please follow each repository's installation instructions and licence. For reproducible analyses, use the release or archived version associated with the study, and cite the corresponding publication and software or dataset DOI where available.

For software questions and bug reports, use the relevant repository's issue tracker. To suggest a resource for this directory, [open an issue](https://github.com/TAGC-Inserm/.github/issues).

## Contact

[TAGC website](https://tagc.univ-amu.fr/) · [Contact page](https://tagc.univ-amu.fr/en/contact) · [TAGC on X](https://twitter.com/TAGC_U1090) · [Zenodo](https://zenodo.org/communities/tagc)

Laboratoire TAGC, Inserm U1090, Aix-Marseille Université  
Parc Scientifique de Luminy, Case 928  
163 Avenue de Luminy, 13288 Marseille Cedex 09, France  
[Find us on Google Maps](https://maps.app.goo.gl/s9dgTpa97emEcZGa7)

<!-- Maintainers: keep entries concise; distinguish code archives from datasets; link paper-specific versions when available. Last content review: 2026-10-28. -->
