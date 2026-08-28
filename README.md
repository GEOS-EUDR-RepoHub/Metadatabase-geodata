<img width="2649" height="1448" alt="dataset_theme_distribution_nature_style" src="https://github.com/user-attachments/assets/4bd76488-f2f0-44f9-ba42-4ebc67ff9495" />

# Metadatabase: a structured metadata repository from [(GEOS-EUDR Project)](https://www.thuenen.de/en/cross-institutional-projects/geos-eudr)
A curated catalog of metadata for published, and publicly available (open access) forest and commodities-related spatial datasets at global, regional, and national scales with particular relevance to the EU regulation of deforestation-free products (EUDR).

## Overview

This repository contains the metadatabase developed within the [GEOS-EUDR](https://www.thuenen.de/en/cross-institutional-projects/geos-eudr) project at the [Thünen-Institute of Forestry](https://www.thuenen.de/en/institutes/forestry). GEOS-EUDR accompanies the implementation of the [European Regulation on Deforestation-free Products (EUDR)](https://environment.ec.europa.eu/topics/forests/deforestation/regulation-deforestation-free-products_en) from a scientific perspective. It aims to contribute to the operational feasibility of the regulation with a focus on geolocation and the detection of deforestation and forest degradation using available earth observation (EO)-based products and geocomputation.

Within this context, the metadatabase compiles and organizes relevant geospatial datasets that contribute to the understanding and monitoring of deforestation-free supply chains and land-use dynamics across multiple geographical and spatial scales. 

To facilitate usability, the metadatabase collection is structured to support transparent data discovery and reuse across both research and policy applications related to forest monitoring.

---

## Thematic Scope of the Dataset Catalog

The datasets included in this repository are organized into the following thematic domains:

- **Forest / Tree Cover Information**  
  Datasets describing forest/tree area extent, canopy cover, and tree cover dynamics over time.
  
    Geographical Scale: Global

- **Forest Management Information (Degradation and Plantation)**  *(to be released)*   
  Data related to forest degradation processes, managed forests, and plantation systems.
  
    Geographical Scale: Mostly Global

- **Deforestation / Tree Loss Information** *(to be released)*  
  Datasets describing areas of detected tree loss and deforestation over time.
  
    Geographical Scale: Mostly Global

- **Regional Scale Data**  *(to be released)* 
  Spatial datasets covering sub-national and regional administrative or ecological units.
  
    Geographical Scale: Regional/Continental

- **Commodity and Crop-Related Data**  *(to be released)*    
  Information on selected EUDR-relevant commodities (cattle, wood, cocoa, soy, palm oil, coffee, and rubber) as well as areas associated with general cropping systems.
  
    Geographical Scale: Mostly Global coverage, but not fully globally representative.

- **National Level Data**  *(to be released)*    
  Country-scale datasets supporting broader comparative or aggregated analyses. Only available for few countries.
  

> ⚠️ **Disclaimer:** Each thematic domain may include multiple versions of a dataset, reflecting updates over time, as the production of remotely sensed derived products is continuously evolving and frequently revised. The catalog is updated every 3 months on average.

---

## Repository Structure

The repository is organized into three main folders:

### 1. `data/`
This folder contains the full dataset catalogs in multiple formats:
- `.csv`
- `.tsv`
- `.xlsx`
- `.zip` (containing all three formats above)
  
The datasets are further named according to the thematic groups listed priorly. These files represent the complete versions of each thematic catalog.
Within the tables, entries may sometimes appear as “NR” or “NA”, where:
- **NR** indicates “not explicitly reported/not explicated”
- **NA** indicates “not applicable”.
  
#### 1.1 Data naming convention

All dataset files follow the standardized naming structure:

E.g. **`[Theme]_[Project]_[Source]_[Version].xlsx`**

Where:
- **Theme**: Broad thematic domain (e.g., ForestCover, Deforestation, CommodityData)
- **Project**: Project reference = GEOS-EUDR
- **Source**: Institution of data provider = Thünen
- **Version**: Dataset iteration identifier (see versioning rules below)

#### 1.2 Data versioning convention

Versioning reflects changes in dataset content, particularly updates such as:
- addition of new dataset entries (new lines in the catalog table)
- revisions or corrections of existing entries
- structural changes to the dataset
  
The adopted version format is:

**vX.Y**

Where:
- **X (major version)**: Changes that modify structure or significantly alter the dataset (e.g., new variables, schema changes)
- **Y (minor version)**: Updates that add or modify dataset entries without changing structure

Example:
- `v1.0` → initial release
- `v1.1` → new datasets added to the catalog
- `v2.0` → structural change or major redesign


### 2. `Metadatabase-files/`

These files are simplified summaries of each metadatabase catalog, designed to facilitate quick exploration through links and provide a concise overview of the available datasets.

Example: `SummaryTable_ForestCover_TreeExtent_GeosEUDR_Thuenen_v1.0`

*Note* that the repository links provided refer to the most recent version of the dataset, or to the version corresponding to the year 2020. 
For all available links, refer to full table at [data](data/) page folder.

---

### 3. `docs/`
This folder provides detailed documentation supporting the metadatabase. It includes:

- **Methodological description**  
  Overview of how datasets were identified and collected, including the search period (although this is an ongoing effort), search strategies, and the criteria used for dataset selection and inclusion in the catalog.

- **Column reference guide**  
  Detailed descriptions of each column in the dataset catalog, clarifying meaning and units (where applicable).

This documentation ensures transparency, reproducibility, and consistent interpretation of the dataset structure.

---

## Purpose

This repository is intended to serve as a structured reference library for geospatial datasets relevant to the GEOS-EUDR project. It supports efficient dataset discovery, standardized documentation, and improved accessibility for analysis and reporting workflows.

## License

This project is released under the terms of the **MIT license specified in the `LICENSE` file**.
If you plan to create any material based on the Forest Agreement Layer scripts, please ensure that you cite them appropriately.

**©Copyright 2026, Thünen-Institute, GEOS-EUDR, Juliana Freitas Beyer, Margret Köthke, Melvin Lippe**.

---

## Publications

This project is associated with a publication, and a policy brief.  
For detailed information, please see the dedicated [Publications](publications.md) page.

---

## Suggested Citation
**Forest/Tree cover Dataset**: Freitas Beyer, J., Köthke, M., & Lippe, M. (2026). GEOS-EUDR:  Dataset Catalog - Forest Metadata (Version 1.0). Zenodo. https://10.5281/zenodo.20698510

---

## Contact
If you have questions or suggestions, feel free to open an issue or reach out to: **geos-eudr@thuenen.de**.

