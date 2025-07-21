# Armenian Stylometry Dataset

This repository contains the dataset used in the stylometric study, presentend à Digital Humanities 2025 Conference (Lisbon).

> **Whose Pen Wrote the Map? Battling Over the Armenian Medieval Text *Ashkharhatsuyts* with Stylometry**  
> Jean-Baptiste Camps & Chahan Vidal-Gorène  
> [HAL ID: hal-05062055v1](https://enc.hal.science/hal-05062055) — *DH 2025*, Lisbon


## Repository Contents

- `data/` — Normalized Classical Armenian texts grouped by author:
  - **Anania Shirakatsi**
  - **Movses Khorenatsi**
  - **Eghishe**
  - **Ghazar Parpetsi**
- `archive_data-digilib/` — Source texts, from Digilib or OCR (Calfa)
- `armenian-words_feats.json` — Extracted feature list (e.g., function words)
- `list_words/` — Stopword and function word lists for stylometric analysis

## Purpose

This dataset supports authorship attribution analysis of the *Ashkharhatsuyts*, a medieval Armenian geographic treatise traditionally attributed either to **Movses Khorenatsi** or **Anania Shirakatsi**.
The corpus was normalized, cleaned, and sampled to allow machine learning models (e.g. SVM) to distinguish authorship through function word usage and stylometric markers (see paper)

## Citation

If you use this dataset or the study, please cite the following publication:

```bibtex
@inproceedings{camps:hal-05062055,
  TITLE = {{Whose Pen Wrote the Map? Battling Over the Armenian Medieval Text Ashkharhatsuyts with Stylometry}},
  AUTHOR = {Camps, Jean-Baptiste and Vidal-Gor{\`e}ne, Chahan},
  URL = {https://enc.hal.science/hal-05062055},
  BOOKTITLE = {{DH 2025 Book of Abstracts}},
  ADDRESS = {Lisbon, Portugal},
  ORGANIZATION = {{ADHO}},
  YEAR = {2025},
  MONTH = Jul,
  KEYWORDS = {Computational human sciences ; Stylometry ; Classical Armenian ; Authorship Attribution},
  PDF = {https://enc.hal.science/hal-05062055v1/file/DH_2025_Moses-11.pdf},
  HAL_ID = {hal-05062055},
  HAL_VERSION = {v1},
}
