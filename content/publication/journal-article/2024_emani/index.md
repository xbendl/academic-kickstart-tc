---
title: "Single-cell genomics and regulatory networks for 388 human brains"

authors:
- Prashant S Emani, 
- Jason J Liu
- Declan Clarke
- Matthew Jensen
- Jonathan Warrell
- Chirag Gupta
- Ran Meng
- Che Yu Lee
- Siwei Xu
- Cagatay Dursun
- Shaoke Lou
- Yuhang Chen
- Zhiyuan Chu
- Timur Galeev
- Ahyeon Hwang
- Yunyang Li
- Pengyu Ni
- Xiao Zhou
- PsychENCODE Consortium‡
- Trygve E Bakken
- Jaroslav Bendl
- Lucy Bicks
- Tanima Chatterjee
- Lijun Cheng
- Yuyan Cheng
- Yi Dai
- Ziheng Duan
- Mary Flaherty
- John F Fullard
- Michael Gancz
- Diego Garrido-Martín
- Sophia Gaynor-Gillett
- Jennifer Grundman
- Natalie Hawken
- Ella Henry
- Gabriel E Hoffman
- Ao Huang
- Yunzhe Jiang
- Ting Jin
- Nikolas L Jorstad
- Riki Kawaguchi
- Saniya Khullar
- Jianyin Liu
- Junhao Liu
- Shuang Liu
- Shaojie Ma
- Michael Margolis
- Samantha Mazariegos
- Jill Moore
- Jennifer R Moran
- Eric Nguyen
- Nishigandha Phalke
- Milos Pjanic
- Henry Pratt
- Diana Quintero
- Ananya S Rajagopalan
- Tiernon R Riesenmy
- Nicole Shedd
- Manman Shi
- Megan Spector
- Rosemarie Terwilliger
- Kyle J Travaglini
- Brie Wamsley
- Gaoyuan Wang
- Yan Xia
- Shaohua Xiao
- Andrew C Yang
- Suchen Zheng
- Michael J Gandal
- Donghoon Lee
- Ed S Lein
- Panos Roussos
- Nenad Sestan
- Zhiping Weng
- Kevin P White
- Hyejung Won
- Matthew J Girgenti
- Jing Zhang
- Daifeng Wang
- Daniel Geschwind
- Mark Gerstein

date: "2024/5/24"
doi: "10.1126/science.adi5199"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Science"
publication_short: ""

abstract: INTRODUCTION. Single-cell genomics offers a powerful method to understand how variants influence gene expression, especially across the numerous cell types in the human brain. Moreover, it can potentially refine our understanding of the regulatory mechanisms underlying brain-related traits. However, population-scale cohorts with a wide range of brain phenotypes are needed to infer key associations among variants and to develop models of regulation at the single-cell scale -- RATIONALE. To address this, the PsychENCODE Consortium performed many single-cell experiments [single-nucleus RNA sequencing (snRNA-seq), snATAC-seq (ATAC, assay for transposase-accessible chromatin), and snMultiome plus genotyping] and computational analyses on prefrontal-cortex samples of adults with a range of brain-related disorders such as schizophrenia, autism spectrum disorder, bipolar disorder, and Alzheimer’s disease, as well as controls -- RESULTS. We developed a uniformly processed resource comprising >2.8 million nuclei from 388 individuals (brainscope.psychencode.org). The resource is based on harmonized cell typing, with 28 neuronal and non-neuronal cell types (registered against BICCN). Partitioning the expression variation within these types revealed higher cell-type variability than interindividual variability; this pattern was amplified in neurotransmitter and neurorelated drug-target genes such as CNR1.
Integration of expression and genotype data revealed >1.4 million single-cell expression quantitative trait loci (eQTLs), many of which were not seen in bulk gene-expression datasets and a subset of which involved variants related to brain disorders. Moreover, we found that expression patterns across cell types recapitulated the spatial relationships of excitatory neurons across cortical layers and enabled the identification of “dynamic eQTLs,” with smooth changes in regulatory effect across cortical layers. The chromatin datasets in the resource allowed for identification of >550,000 single-cell cis-regulatory elements, which were enriched at loci linked to brain-related traits. Combining expression, chromatin, and eQTL datasets, we built cell type–specific gene regulatory networks. In these, information-flow bottleneck genes tended to be specific to particular cell types, in contrast to hubs. We also developed cell-to-cell communication networks, which highlighted differences in signaling pathways in disorders, including altered Wnt signaling in schizophrenia and bipolar disorder. We developed an integrative deep-learning model with embedded layers for genotypes, eQTLs, and regulatory and cell-to-cell communications networks. The model allowed for accurate imputation of cell type–specific expression and phenotype from genotype. It prioritized >250 risk genes and drug targets for brain-related disorders along with associated cell types. Simulated perturbation of individual genes led to predicted expression changes mirroring those for disease cases, suggesting drug targets. Lastly, we constructed predictive models for aging and Alzheimer’s disease, showing, for instance, that expression and chromatin in specific neurons were highly predictive of an individual’s age


# Summary. An optional shortened abstract.
summary: Our population-scale single-cell resource for the human brain can help facilitate precision-medicine approaches for neuropsychiatric disorders, especially by prioritizing follow-up genes and drug targets linked to cell types.

tags:
- Source Themes
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: ''
url_code: ''
url_dataset: 'http://brainscope.psychencode.org/'
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

---
