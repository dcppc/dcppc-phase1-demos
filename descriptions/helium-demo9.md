# Helium Demo 9: Search over public knowledge resources for omics data for tissue of interest

* The user is a bioinformatician looking to search public knowledge resources such as public data from data stewards for data about gene expression in a particular tissue, perhaps to explore differences in gene regulation across some parameter e.g. sex.
* The user environment is a Jupyter notebook.
* The user invokes the CommonShare search API via a lightweight python client (transparently and reproducibly downloaded in advance from pypi as specified in the notebook’s requirements.txt file).
* The user experiments with different search parameters, e.g. ‘kidney’.
* The API invocation triggers a search over standard semantic search APIs including the Monarch search API, which returns a payload indicating data types available for tissue of interest, including MOD data, GO data and GTEx, rendered in the notebook as a standard python dataframe.
* The payload also indicates data available for finer-grained or coarser-grained queries (based on the hierarchy of the standard multi-species Uberon tissue anatomy), and based on this the user decides to generalize the search to ‘genitourinary system’.
* This search profile includes gene interaction data from GTEx broken down by tissues in this system, pathway and function data for genes involved in embryonic development of this system in GO, and model organism gene expression data aggregated via Bgee, relevant phenotypes of interest [these could later be linked to dbgap variables and used for interrogating TopMed data but this is out of scope for 180 days]. From here the user can import the relevant data into the notebook environment.
