# CDAW CME Catalog Analysis

## About
Repository for code analyzing CDAW CME catalog found at this location:

https://cdaw.gsfc.nasa.gov/CME_list/UNIVERSAL/text_ver/univ_all.txt

catalog description here:

https://cdaw.gsfc.nasa.gov/CME_list/catalog_description.htm

The analysis will attempt to estimate various parameters about CME and use for classification into types.

## Installation
```bash
> python3 -m venv ./venv
> source venv/bin/activate
> pip install -r requirements.txt
```

## Usage
All of the analysis is in a notebook. Fire it up as:
```bash
> jupyter notebook notebooks/cdaw_cme_catalog_analysis.ipynb
```
