# WikiMedSubset

As part of an effort to build a medical knowledge graph by machine learning, we tried to identify Wikipedia articles on medicine and classify them into 7 classes by semantic type: Anatomy (ANAT), Chemicals & Drugs (CHEM), Devices (DEVI), Disorders (DISO), Living Beings (LIVB), Physiology (PHYS), and Procedures (PROC). Since the proportion of Wikipedia articles about medicine is estimated to be 0.4-0.5%, it is infeasible to use conventional classification models and is hard to prepare training data. To address this difficulty, we developed a crawling classification strategy to raise the positive rate. A deep learning model is then used to further classify the identified articles by semantic type.

As a result, we identified 68,786 articles on medicine from the entire Wikipedia. Searching notable concept codes (ICD, UMLS, etc.) in the associated Wikidata items showed that most of the articles could not be identified by simple queries. We aggregated 182 thousand facts from Wikidata and 445 thousand lines of properties from the Infobox associated with the identified medical articles. A comparison shows that the extracted relations substantially supplements the existing relations in the UMLS, especially in clinically important ones, such as symptoms and treatments.

Here we share the results with the medical informatics community.

- Article names and classification: https://cloud.tsinghua.edu.cn/f/b9b4624d74da483c804f/?dl=1
- Associated Infobox data: https://cloud.tsinghua.edu.cn/f/b1603962fc9142559d91/?dl=1
- Associated Wikidata Items: https://cloud.tsinghua.edu.cn/f/e892125c83374d7588bf/?dl=1
