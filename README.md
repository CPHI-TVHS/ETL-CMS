# ETL-CMS
Workproducts to ETL CMS datasets into OMOP Common Data Model

## What's in Here?


### scripts
The scripts folder holds handy scripts for munging some of the raw data used in the ETLs we're developing.

Known scripts:

- get_synpuf_files.py
    - A python3 script that will download sets 4 and 15 from the CMS website and unzip them into a folder of your choosing.


## python_etl
A Python-based ETL of SynPUF into CDMv5-compatible CSV files.  **This implementation is under active development and is intended to be used by people aiming to contribute to its implementation.  It is not ready for general use**


### Additional Resources
- [Partial ETL of SEER Medicare to OMOP CDMv4](https://github.com/outcomesinsights/seer_to_omop_cdmv4) - [Outcomes Insights](http://outins.com) has released their partial implementation of a SEER Medicare ETL, along with their specification document to serve as a reference for the ETLs created by this workgroup
