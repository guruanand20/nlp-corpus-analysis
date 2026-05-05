# NLP Corpus Analysis
## Overview
This project analyses how the focus, framing and vocabulary of NLP research has changed over time, using scientific abstracts from the arXiv dataset (cs.CL and cmp-lg categories, 1994–2021)

The analysis is structured around two axes:
- Axis 1 Text Representation: compares four methods (TF-IDF Unigrams, TF-IDF Bigrams, SBERT, LDA) to examine how representational choices shape what patterns become visible

- Axis 2 Comparison Method: contrasts Top-N Keyword Shift analysis with Cosine Distance to determine what kind of change each method can detect and explain


### Team & Contributions

Contributions of this project are students at University of Bristol.

| Member   | Name            | Notebook Role                                                | Report Sections                                              |
| -------- | --------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| Member 1 | Rui Liu         | EDA, Preprocessing, TF-IDF Representation (`EDA + Add year.ipynb.ipynb`,`EDA + select NLP + year segments .ipynb`,`NB01.ipynb`,`NB01_all data.ipynb`) | Intro §1 (task & motivation), Methods §2.1 (preprocessing & TF-IDF baseline), Eval §3.1 (TF-IDF results), Conclusions §4 (TF-IDF finding) |
| Member 2 | Dekai Fan       | SBERT & LDA Representation (`NB01.ipynb`, `NB01_all data.ipynb`) | Intro §1 (available data), Methods §2.3 (SBERT & LDA), Eval §3.2 (SBERT & LDA results), Conclusions §4 (SBERT/LDA finding) |
| Member 3 | Karen Coutinho  | Top-N Keyword Shift Analysis (`02_comparison.ipynb`,`NB02.ipynb`) | Intro §1 (requirements for a good solution), Methods §2.4 (keyword shift), Eval §3.4 (keyword shift results), Conclusions §4 (keyword shift finding) |
| Member 4 | Guruanand Reddy | Cosine Distance Analysis (`NB02.ipynb.ipynb`)                | Intro §1 (dataset examples), Methods §2.5 (cosine distance), Eval §3.5 (cosine distance results), Conclusions §4 (cosine distance finding) |
| Member 5 | Chang Gao       | PCA & UMAP Trajectory Visualisation (`03_pca_trajectory.ipynb`) | Abstract, Methods §2.6 (dimensionality reduction), Eval §3.6 (evaluation & discussion), Conclusions §4 (opening & closing paragraphs) |



### Data and Cloud files
OneDrive main directory (University of Bristol institutional account access only): https://uob-my.sharepoint.com/:f:/g/personal/fx25224_bristol_ac_uk/IgAdwqaWLo6xS7KCRQTknVLPAaq16MTS3VqWvsqZVZdfQVM?e=p5WeAL

The entire data with time label: https://uob-my.sharepoint.com/:x:/g/personal/fx25224_bristol_ac_uk/IQDzMRQhPytASaF8S3e0vVnrAXcoae0Da-vz8gItPO36B9I?e=cJaeVh 

The NLP data with time and technique label：https://uob-my.sharepoint.com/:x:/g/personal/fx25224_bristol_ac_uk/IQDakmgwzEzLT7eYQWwrlqfgARaJ7qcYnxv3-tBJCDbiGKk?e=RJxSNY

The Overleaf report zip file: https://uob-my.sharepoint.com/:u:/r/personal/fx25224_bristol_ac_uk/Documents/tb2/AI%26text/CWdata/report_resource.zip?csf=1&web=1&e=Idp8ox



