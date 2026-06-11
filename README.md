<img width="2650" height="1447" alt="Image" src="https://github.com/user-attachments/assets/b4c5cb43-536b-46e5-819f-6edf1d533c3f" />

# Metadatabase: Dataset-Catalog (GEOS-EUDR Project)
A curated table of metadata for published and public forest, commodities-related and other spatial datasets at global, regional scales and national-level (few countries).

## Overview

This repository contains the dataset catalog developed within the **GEOS-EUDR project**, which supports spatially explicit analyses under the **European Regulation on Deforestation-free Products** (https://environment.ec.europa.eu/topics/forests/deforestation/regulation-deforestation-free-products_en). 

Within this context, the catalog compiles and organizes relevant geospatial datasets that contribute to the understanding and monitoring of deforestation-free supply chains and land-use dynamics across multiple spatial scales. 

To facilitate usability, the dataset collection is structured to support transparent data discovery and reuse across both research and policy applications related to forest monitoring.

---

## Thematic Scope of the Dataset Catalog

The datasets included in this repository are organized into the following thematic domains:

- **Forest / Tree Cover Information**  
  Datasets describing forest/tree area extent, canopy cover, and tree cover dynamics over time
  Geographical Scale: Global.

- **Forest Management Information (Degradation and Plantation)**  *(to be released)*   
  Data related to forest degradation processes, managed forests, and plantation systems
  Geographical Scale: Mostly Global.

- **Deforestation / Tree Loss Information** *(to be released)*  
  Datasets describing areas of detected tree loss and deforestation over time
  Geographical Scale: Mostly Global.

- **Regional Scale Data**  *(to be released)* 
  Spatial datasets covering sub-national and regional administrative or ecological units
  Geographical Scale: Regional/Continental.

- **Commodity and Crop-Related Data**  *(to be released)*    
  Information on selected EUDR-relevant commodities (cattle, wood, cocoa, soy, palm oil, coffee, and rubber) as well as areas associated with general cropping systems
  Geographical Scale: Mostly Global coverage, but not fully globally representative.

- **National Level Data**  *(to be released)*)    
  Country-scale datasets supporting broader comparative or aggregated analyses. Only available for few countries.
  

> ⚠️ **Disclaimer:** Each thematic domain may include multiple versions of a dataset, reflecting updates over time, as the production of remotely sensed derived products is continuously evolving and frequently revised.

---

## Repository Structure

The repository is organized into three main folders:

### 1. `data/`
This folder contains the full dataset catalogs in multiple formats:
- `.csv`
- `.tsv`
- `.xlsx`
  
The datasets are further organized according to the thematic groups listed above. These files represent the complete versions of each thematic catalog.
Within the tables, entries may sometimes appear as “NR” or “NA”, where:
- **NR** indicates “not explicitly reported/not explicated”
- **NA** indicates “not applicable”.
  
#### 1.1 Data naming convention

All dataset files follow the standardized naming structure:

E.g. **`[Theme]__[Project]__[Source]_[Version].xlsx`**

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


### 2. `catalog-files/`

These files are simplified summaries of each dataset catalog, designed to facilitate quick exploration through links and provide a concise overview of the available datasets.

Example: `ForestCover_TreeExtent_Global_Thuenen_v1.0_SummaryTable`

---

### 3. `docs/`
This folder provides detailed documentation supporting the dataset catalog. It includes:

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

This project is associated with several publications, dataset descriptions, and policy briefs.  
For detailed information, please see the dedicated [Publications](publications.md) page.

---

## Suggested Citation
Freitas Beyer, J., Köthke, M., & Lippe, M. (2026). Title (Acronym). Zenodo. https://doi.org/...

---

## Contact
If you have questions or suggestions, feel free to open an issue or reach out to: **geos-eudr@thuenen.de**.

