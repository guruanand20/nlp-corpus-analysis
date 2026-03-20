# \# NLP Corpus Analysis

# \## Text Analytics Coursework — Comparative Corpus Analysis

# 

# \### Overview

# This project analyses how the focus, framing and communication of NLP 

# research has changed over time using scientific abstracts from the 

# arXiv dataset (cs.CL category, 1990–2021).

# 

# \### Team

# 

# | Rui Liu         | TF-IDF Representation | 01\_representation.ipynb |

# | Dekai Fan       | SBERT \& LDA Representation | 01\_representation.ipynb |

# | Karen Coutinho  | Top-N Keyword Shifts | 02\_comparison.ipynb |

# | Guruanand Reddy | Cosine Distance | 02\_comparison.ipynb |

# | Chang Gao       | PCA Trajectory Visualisation | 03\_pca\_trajectory.ipynb |

# 

# \### Dataset

# \- Source: gfissore/arxiv-abstracts-2021 (HuggingFace)

# \- Filter: cs.CL category (NLP papers only)

# \- Approx. 50,000–80,000 abstracts after filtering

# 

# \### Design Axes

# \- Axis 1 — Text Representation: TF-IDF Unigrams vs Bigrams vs SBERT vs LDA

# \- Axis 2 — Comparison Method: Top-N Keyword Shifts vs Cosine Distance

# 

# \### Notebook Structure

# | Notebook | Purpose |

# |---|---|

# | 00\_preprocessing.ipynb | Load, filter and clean the dataset |

# | 01\_representation.ipynb | Build TF-IDF, SBERT and LDA representations |

# | 02\_comparison.ipynb | Keyword shift and cosine distance analysis |

# | 03\_pca\_trajectory.ipynb | PCA and UMAP trajectory visualisation |

# | 04\_report.ipynb | Final comparison, evaluation and findings |

# 

# \### How to Run

# 1\. Install dependencies: `pip install -r requirements.txt`

# 2\. Download the shared data folder and place files in `/data` and `/outputs`

# 3\. Run notebooks in order: 00 → 01 → 02/03 → 04

