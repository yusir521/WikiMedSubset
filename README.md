# WikiMedSubset

As part of an effort to build a medical knowledge graph by machine learning, we tried to identify Wikipedia articles on medicine and classify them into 7 classes by semantic type: Anatomy (ANAT), Chemicals & Drugs (CHEM), Devices (DEVI), Disorders (DISO), Living Beings (LIVB), Physiology (PHYS), and Procedures (PROC). Since the proportion of Wikipedia articles about medicine is estimated to be 0.2-0.3%, it is infeasible to use conventional classification models and is hard to prepare training data. To address this difficulty, we developed a crawling classification strategy to raise the positive rate. A deep learning model is then used to further classify the identified articles by semantic type.

As a result, we identified 38,803 articles on medicine from the entire Wikipedia. Validating using article names identifiable in the UMLS, the precision of semantic type classification was 97.5%.  Searching notable concept codes (ICD, UMLS, etc.) in the associated Wikidata items showed that most of the articles could not be identified by simple queries. We aggregated 306,190 facts from Wikidata and 176,835 lines of properties from the Infobox associated with the identified medical articles.

Here we share the results with the medical informatics community.

- Article names and classification: https://cloud.tsinghua.edu.cn/f/11a02d7c7e0c4037b1b0/?dl=1
- Associated Infobox data: https://cloud.tsinghua.edu.cn/f/a82e6ba54ca742e6a83b/?dl=1
