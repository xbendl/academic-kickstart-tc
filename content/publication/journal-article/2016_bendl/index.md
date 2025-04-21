---
title: "PredictSNP2: A Unified Platform for Accurately Evaluating SNP Effects by Exploiting the Different Characteristics of Variants in Distinct Genomic Regions"
authors:
- admin
- Milos Musil
- Jan Stourac
- Jaroslav Zendulka
- Jiri Damborsky 
- Jan Brezovsky
date: "2016-05-12"
doi: "10.1371/journal.pcbi.1004962"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "PLoS computational biology"
publication_short: ""

abstract: An important message taken from human genome sequencing projects is that the human population exhibits approximately 99.9% genetic similarity. Variations in the remaining parts of the genome determine our identity, trace our history and reveal our heritage. The precise delineation of phenotypically causal variants plays a key role in providing accurate personalized diagnosis, prognosis, and treatment of inherited diseases. Several computational methods for achieving such delineation have been reported recently. However, their ability to pinpoint potentially deleterious variants is limited by the fact that their mechanisms of prediction do not account for the existence of different categories of variants. Consequently, their output is biased towards the variant categories that are most strongly represented in the variant databases. Moreover, most such methods provide numeric scores but not binary predictions of the deleteriousness of variants or confidence scores that would be more easily understood by users. We have constructed three datasets covering different types of disease-related variants, which were divided across five categories, i.e., (i) regulatory, (ii) splicing, (iii) missense, (iv) synonymous, and (v) nonsense variants. These datasets were used to develop category-optimal decision thresholds and to evaluate six tools for variant prioritization, i.e.,  CADD, DANN, FATHMM, FitCons, FunSeq2 and GWAVA. This evaluation revealed some important advantages of the category-based approach. The results obtained with the five best-performing tools were then combined into a consensus score. Additional comparative analyses showed that in the case of missense variations, protein-based predictors perform better than DNA sequence-based predictors. A user-friendly web interface was developed that provides easy access to the five tools’ predictions, and their consensus scores, in a user-understandable format tailored to the specific features of different categories of variations. To enable comprehensive evaluation of variants, the predictions are complemented with annotations from eight databases. The web server is freely available to the community at [http://loschmidt.chemi.muni.cz/predictsnp2](http://loschmidt.chemi.muni.cz/predictsnp2).


# Summary. An optional shortened abstract.
summary: Meta-predictor of the effect of nucleic acid substitution on human health (rare diseases).

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://journals.plos.org/ploscompbiol/article/file?id=10.1371/journal.pcbi.1004962&type=printable
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  focal_point: ""
  preview_only: false
  
---
