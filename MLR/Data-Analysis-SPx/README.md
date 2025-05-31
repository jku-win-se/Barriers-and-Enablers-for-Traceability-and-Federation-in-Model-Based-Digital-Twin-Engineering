# Data-Analysis — SPx Pipeline (MLR)

This folder contains the **step-by-step analysis pipeline** used to transform raw search hits into the dataset and plots reported in the paper.

## Folder structure

- Data-Analysis-SPx/
	- 00–SLR-After-Query/:          **Raw search results (Scopus, IEEE, ACM, WoS)*
	- 01–SLR-After-IC-EC/:          **After Inclusion/Exclusion criteria*
	- 02–SLR-Snowballing/:          **Back‑ & Forward‑snowballing*
	- 03–SLR-Selected/:             **Final paper set*
	- 04–SLR-Selected-after-DEF/:   **Dataset enriched with coded variables*

| Stage | What happens here |
|-------|-------------------|
| **00 – After Query** | Import CSVs exported from each digital library; deduplicate and harmonise metadata. | 
| **01 – After IC/EC** | Apply Inclusion/Exclusion criteria; compute basic descriptive analysis. |
| **02 – Snowballing** | Perform backward and forward snowballing. |
| **03 – Selected** | Freeze the *final* list of primary studies; export canonical BibTeX. |
| **04 - SLR-Selected after Data Extraction** | Join coded variables & quality scores; generate all stats/plots. |
