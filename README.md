# India Industrial Survey Analysis

## Overview

This repository contains cleaned and harmonized datasets created from the Annual Survey of Industries (ASI) and Annual Survey of Unincorporated Sector Enterprises (ASUSE) datasets for economic analysis and research.

## Files

### master_github_paths_fixed.ipynb

* Contains cleaned ASI data from 2011–2024.
* Raw ASI datasets were processed and converted into a harmonized wide-format panel dataset.
* Includes data cleaning, variable standardization, and merging across years.

### master_product_github_ready.ipynb

* Focuses on ASI Block J (Products and By-products).
* Uses ASICC product codes to identify products manufactured by industries.
* Data is maintained in long format, where each row represents a product observation.
* Includes information on product revenue, taxes, and other product-level variables.

### asuse_2_github_ready.ipynb

* Contains ASUSE datasets from different NSS survey rounds (2011 and 2016 onwards).
* Datasets were harmonized to ensure consistent variable definitions across years.
* Appended into a unified dataset for longitudinal analysis of the unincorporated sector.

## Data Sources

* Annual Survey of Industries (ASI)
* Annual Survey of Unincorporated Sector Enterprises (ASUSE)
* National Sample Survey (NSS)

## Tools Used

* Python
* Pandas
* NumPy
* Jupyter Notebook

## Author

Samnan
