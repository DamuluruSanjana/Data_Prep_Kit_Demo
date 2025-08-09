# Data_Prep_Kit_Demo: Data Preparation Toolkit for PDF to Parquet Conversion 🗂️➡️📊
 AICTE - IBM Internship on AI &amp; Cloud Technologies by Edunet Foundation 


## Definition 📚
Data_Prep_Kit_Demo demonstrates the use of the Data Preparation Toolkit (DPK) to convert PDF files into Apache Parquet format using a simple, reproducible workflow in Jupyter Notebook or Google Colab.

## Project Overview 📝
This notebook provides a step-by-step guide to setting up and running the DPK `pdf2parquet` transform. It covers environment setup, sample data download, PDF-to-Parquet conversion, and verification of results using pandas DataFrames. The project is part of the AICTE - IBM Internship on AI & Cloud Technologies by Edunet Foundation.

## How to Use ⚙️
1. **Run Notebook:** Open the notebook in Colab or locally.
2. **Install Dependencies:** Execute cells to install `data-prep-toolkit-transforms`, `pandas`, and `numpy`.
3. **Download Sample Data:** Automatically downloads PDF and ZIP files to a temporary input folder.
4. **Convert Files:** Use the `Pdf2Parquet` class to transform PDFs/ZIPs to Parquet format.
5. **Verify Output:** Read and display the converted `.parquet` files as pandas DataFrames.

## Features ✨
- Converts PDFs and ZIPs containing PDFs to Parquet format.
- Simple setup for Colab or local Jupyter environment.
- Automated sample data download.
- Output verification with pandas and pyarrow.
- Efficient columnar storage for analytics workflows.

## Example Workflow 🔄
1. Create temporary input/output directories.
2. Download sample PDF and ZIP files.
3. Run `Pdf2Parquet.transform()` to convert files.
4. Locate and read `.parquet` outputs in `tmp/output`.
5. Display data as pandas DataFrame.

## Technologies Used 🛠️
- Data Preparation Toolkit (`data-prep-toolkit-transforms`)
- pandas
- PyArrow
- Jupyter Notebook / Google Colab

## References 🔗
- [Data Preparation Toolkit Documentation](https://github.com/IBM/data-prep-toolkit)
