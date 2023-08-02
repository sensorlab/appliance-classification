# Appliance classification
## General info

This is a repository for a paper about NILM multi-label robustness. It contains a collection of Jupyter Notebook files that provide functions and scripts for processing and manipulating energy consumption datasets. The tools aim to facilitate dataset merging, normalization, parsing, testing, and validation for further analysis and modeling.


## File Descriptions

- `Split_processed_data.ipynb`: This notebook file focuses on splitting the processed energy consumption datasets into train, validation, and test subsets, facilitating model training and evaluation.

- `Daily_normalization_merger.ipynb`: This notebook file includes functions for merging and normalizing datasets to be split into individual days, allowing for more comprehensive and consistent data analysis.

- `Train_Test_Validate.ipynb`: This notebook file includes functions and tools for training DL models using Ecopirnat or VGG models, testing and validating the processed datasets.

### Parsers

- `Parse_NILMTK.ipynb`: This notebook file provides a "universal" parser for datasets in the NILMTK format, allowing for consistent data extraction and manipulation across various NILMTK-compatible datasets.

- `Parse_HES.ipynb`: This notebook file contains a parser specifically designed for the Household Electricity Survey (HES) dataset, enabling data extraction and preparation for downstream tasks.

- `Parse_lerta.ipynb`: This notebook file is responsible for parsing and handling the LERTA dataset, allowing for data extraction and manipulation.

- `Parse_DRED.ipynb`:  This notebook file is responsible for parsing and handling the DRED dataset, allowing for data extraction and manipulation.

  
