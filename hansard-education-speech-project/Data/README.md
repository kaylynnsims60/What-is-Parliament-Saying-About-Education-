# Raw Data

This folder is intended to store the raw Hansard source data used in the Hansard Education Speech Project.

## Data Description

The project uses publicly available Canadian House of Commons Hansard data covering the period 1901–2019.

These raw files are not stored directly in this GitHub repository because the full corpus exceeds practical GitHub file-size limits. Instead, this folder documents the source of the data and where the files should be placed locally in order to reproduce the project workflow.

## Source

Raw Hansard data were obtained from a public source.

Source name: Lipad, Canada Hansard Dataset  
Source link: (https://www.lipad.ca/data/)  
Date accessed/downloaded: April 2026  

## How to Use This Folder

To reproduce the project:

1. Download the raw Hansard data from the source listed above.
2. Place the raw files in this folder: `Data/raw/`
3. Run the data preparation scripts in the `Code/` folder in the order described in the main repository `README.md`.  


## Notes

Because the raw data are large, they were not uploaded directly to GitHub. The repository instead provides the full transformation pipeline used to generate the processed and derived datasets locally.



# Processed Data

This folder is intended to store cleaned, filtered, merged, or otherwise processed datasets created from the raw Hansard source data.

## Data Description

The files in this folder are generated through the project workflow and are used for downstream analysis. These include cleaned master datasets, filtered education-related corpora, validation datasets, and other working files.

Some processed files used in the project were too large to store directly in this GitHub repository. They can be regenerated locally by running the scripts in `Code/` after obtaining the raw data.

## How to Reproduce Processed Files

1. Obtain the raw Hansard data and place those files in `Data/raw/`
2. Run the data preparation and filtering scripts in `Code/`
3. The resulting processed datasets will be written to this folder


## Notes

Files in this folder are derived from the raw Hansard corpus and should be treated as generated data rather than original source data.
