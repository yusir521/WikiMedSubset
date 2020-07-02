# WikiMedSubset

As part of an effort to build a medical knowledge graph by machine learning, we developed a automatic mechanism to identify medical articles in Wikipedia and classified them into 7 semantic groups: Anatomy (ANAT), Chemicals & Drugs (CHEM), Devices (DEVI), Disorders (DISO), Living Beings (LIVB), Physiology (PHYS), and Procedures (PROC). Since the prevalence of medical articles in Wikipedia is estimated to be 1.5%, using conventional classification methods would result in a large number of false discoveries, making the results unusable. To address this difficulty, we developed a crawling classification strategy to raise the positive rate. A deep learning model is then used to further classify the identified articles by semantic groups.

From the 2020-05-01 dump of Wikipedia, we identified 93,420 medical articles. Structure information from the Infoboxes and Wikidata items associated with articles were also extracted. We share these results with the medical informatics community. We plan to update the results on a yearly basis.

- Article names and classification: https://cloud.tsinghua.edu.cn/f/c026918469ac40d9af41/?dl=1
- Associated Infobox data: https://cloud.tsinghua.edu.cn/f/893b7fde65bc4a55b2a4/?dl=1
- Associated Wikidata Items: https://cloud.tsinghua.edu.cn/f/e892125c83374d7588bf/?dl=1
