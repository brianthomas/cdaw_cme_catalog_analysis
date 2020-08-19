# LASCO CME Catalog Analysis

## About
Repository for code analyzing SOHO LASCO CME catalog found at this location:

https://cdaw.gsfc.nasa.gov/CME_list/UNIVERSAL/text_ver/univ_all.txt

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
> jupyter notebook notebooks/Lasco_catalog.ipynb
```
