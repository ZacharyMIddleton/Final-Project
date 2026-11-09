# Final Project

## Overview
This repository analyzes municipal 311 service requests, city playground availability, and police arrest records across Pittsburgh to determine the overall best neighborhood to live in.

---

## Team Name & Members

**Team Name:** Final Project Group 12

* **Travis Castle** - `tec122@pitt.edu` *(311 Service Requests)*
* **Zachary Middleton** - `zam165@pitt.edu` *(Playgrounds)*
* **Ryan Walter** - `rkw22@pitt.edu` *(Arrests)*

---

## Datasets 

1. **311 Service Requests**
   * **Description:** Contains all non-emergency municipal service requests reported by residents across Pittsburgh neighborhoods (e.g., pothole repairs, trash removal, building violations). Used to measure civic maintenance demand and neighborhood activity.
   * **Link:** [WPRDC 311 Data](https://data.wprdc.org/dataset/311-data)

2. **City Playgrounds**
   * **Description:** Catalog of official City of Pittsburgh playgrounds organized by neighborhood. Used to measure outdoor access and recreational quality.
   * **Link:** [WPRDC Playgrounds Data](https://data.wprdc.org/dataset/playgrounds)

3. **Police Arrests**
   * **Description:** Record of police arrests compiled by the Pittsburgh Bureau of Police, categorized by neighborhood. Used as an indicator for neighborhood safety.
   * **Link:** [WPRDC Police Arrests Data](https://data.wprdc.org/dataset/pbp_arrest_data_2024_2025)

---

## Structure
* `311.ipynb` – Submetric notebook analyzing 311 service request counts and metric normalization.
* `playgrounds.ipynb` – Submetric notebook analyzing city park distribution.
* `arrests.ipynb` – Submetric notebook analyzing police arrest frequencies.
* `final.ipynb` – Final notebook with all three metrics into an overall neighborhood ranking.
