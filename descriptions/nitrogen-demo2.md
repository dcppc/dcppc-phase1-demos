# Nitrogen Demo 2: Automatically Generated Jupyter Notebook Reports for RNA-seq Data Analysis
The BioJupies web server will allow users to automatically generate Jupyter Notebooks containing tailored analyses of RNA-seq datasets through an intuitive user interface.

The web server will provide access to the following features:

## RNA-seq Data Upload 
The BioJupies web server will allow users to upload their own RNA-seq data for generation of tailored Jupyter Notebooks. Initially, this feature will be restricted to gene expression matrices containing gene-level counts. This will require users to perform read alignment prior to analysis. In the future, we will implement a pipeline to allow direct upload and processing of raw FASTQ read files using a Cloud-based infrastructure.

## Streamlined Analysis of Public RNA-seq Data
In addition to uploading their own data, users will be able to analyze publicly available RNA-seq datasets published in major biomedical data repositories such as the Gene Expression Omnibus. By leveraging the data processed by ARCHS4 (http://archs4.cloud), users will have access to over 200,000 pre-processed, ready-to-analyze RNA-seq samples from published human and mouse studies.

## Generation of Notebooks through a Chrome Extension
Generation of Jupyter Notebooks will additionally be made possible from the websites of data repositories through a free Chrome browser extension. The Chrome extension will embed buttons in the landing pages of processed datasets. Here, users will be able to select the tools they wish to analyze the data with, modify optional parameters, and rapidly access the results of the analyses.

## Access to Pre-Configured Analysis Tools
BioJupies will provide access to multiple data analysis and visualization tools to interactively explore and analyze RNA-seq data. These will include principal component analysis (PCA), interactive clustered heatmaps, tools for differential expression and enrichment analyses, and queries of signatures against the LINCS L1000 dataset for small molecule that can mimic or reverse signatures.

## Contribution of Computational Analysis Plugins
Users who wish to contribute their own code to BioJupies will be able to do so through a submission form. Submissions will be performed by sharing a link to a GitHub repository containing the source code of the user’s tool. An example repository will be provided to use as a template for tool submission. Once incorporated in BioJupies, other users will be able to use these plugins for data analysis and notebook generation.

## Permanent Cloud Storage of Analysis Results
Jupyter Notebooks generated using BioJupies will be automatically uploaded to a Google Cloud storage and made available to the public through a permanent URL. The accessibility of these digital objects will be therefore guaranteed.

## Reusability of Jupyter Notebooks through Docker Containers
In addition to accessing the results through a permanent URL, users will be able to download and re-run the analyses on their computers through a pre-configured Docker container. This will guarantee the reusability of such digital objects and give users additional options to customize their analyses.
