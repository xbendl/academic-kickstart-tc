---
title: "DeepGAMI: deep biologically guided auxiliary learning for multimodal integration and imputation to improve genotype–phenotype prediction"

authors:
- Pramod Bharadwaj Chandrashekar
- Sayali Alatkar
- Jiebiao Wang
- Gabriel E Hoffman
- Chenfeng He
- Ting Jin
- Saniya Khullar
- Jaroslav Bendl
- John F Fullard
- Panos Roussos
- Daifeng Wang

date: "2023-10-31"
doi: "10.1186/s13073-023-01248-6"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Genome Medicine"
publication_short: ""

abstract: Background - Genotypes are strongly associated with disease phenotypes, particularly in brain disorders. However, the molecular and cellular mechanisms behind this association remain elusive. With emerging multimodal data for these mechanisms, machine learning methods can be applied for phenotype prediction at different scales, but due to the black-box nature of machine learning, integrating these modalities and interpreting biological mechanisms can be challenging. Additionally, the partial availability of these multimodal data presents a challenge in developing these predictive models. Method - To address these challenges, we developed DeepGAMI, an interpretable neural network model to improve genotype-phenotype prediction from multimodal data. DeepGAMI leverages functional genomic information, such as eQTLs and gene regulation, to guide neural network connections. Additionally, it includes an auxiliary learning layer for cross-modal imputation allowing the imputation of latent features of missing modalities and thus predicting phenotypes from a single modality. Finally, DeepGAMI uses integrated gradient to prioritize multimodal features for various phenotypes. Results - We applied DeepGAMI to several multimodal datasets including genotype and bulk and cell-type gene expression data in brain diseases, and gene expression and electrophysiology data of mouse neuronal cells. Using cross-validation and independent validation, DeepGAMI outperformed existing methods for classifying disease types, and cellular and clinical phenotypes, even using single modalities (e.g., AUC score of 0.79 for Schizophrenia and 0.73 for cognitive impairment in Alzheimer's disease). Conclusion - We demonstrated that DeepGAMI improves phenotype prediction and prioritizes phenotypic features and networks in multiple multimodal datasets in complex brains and brain diseases. Also, it prioritized disease-associated variants, genes, and regulatory networks linked to different phenotypes, providing novel insights into the interpretation of gene regulatory mechanisms. DeepGAMI is open-source and available for general use.

# Summary. An optional shortened abstract.
summary: We demonstrated that DeepGAMI improves phenotype prediction and prioritizes phenotypic features and networks in multiple multimodal datasets in complex brains and brain diseases.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 'https://genomemedicine.biomedcentral.com/counter/pdf/10.1186/s13073-023-01248-6.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

---
