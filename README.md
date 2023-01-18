# About

This repository contains the code for

- data preparation
- natural language processing
- evaluation

of the project "IN8 Anwendung von NLP auf die nicht-finanzielle Berichterstattung von Schweizer Unternehmen", financed by Digitale Verwaltung Schweiz (DVS) and conducted by a partnership between NADEL, businessresponsibility.ch and planet10.

# Structure

This project contains four relevant directories/notebooks:

> - 01_pdf_parsing.ipynb: A Jupyter Notebook with the code to parse sustainability reports in pdf format into computer readable format.
>   -- Currently data is parsed using pdfminer and easyocr
> - 02_encode.ipynb: A Jupyter Notebook with the code to encode the parsed text.
>   -- Currently SBERT is used for encoding
> - 03_sentence_similarity_analysis.ipynb: A Jupyter Notebook with the code to generate similarity results of paragraphs
> - 04_evaluation.ipynb: A Jupyter Notebook assessing the quality of the analysis
> - 00_data: Contains all intermediate and final results of the notebooks.

# Getting Started

1.  Install packages:

        $ pipenv install

2.  Run Jupyter Notebooks:

    Option 1: Run Notebook in [VS Code](https://code.visualstudio.com/docs/datascience/jupyter-notebooks)
