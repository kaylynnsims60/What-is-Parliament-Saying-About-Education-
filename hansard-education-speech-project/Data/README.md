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

## Expected Contents

This folder should contain the unmodified raw source files used in the project.

Example contents may include:
- raw Hansard CSV files
- raw metadata files
- source documentation files

If reproducing the project locally, do not alter the raw files stored here. All cleaning, filtering, and transformation steps should be carried out through the scripts in `Code/`.

## Notes

Because the raw data are large, they were not uploaded directly to GitHub. The repository instead provides the full transformation pipeline used to generate the processed and derived datasets locally.
