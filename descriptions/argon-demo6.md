Demo 6: Cloud-hosted Jupyter Notebooks demonstrating interservice interoperability
This demo will demonstrate the use of Jupyter as a user interface to Data Commons capabilities, and the use of various REST APIs using a common authentication and authorization layer. We assume that the Jupyter environment is hosted on Google Compute Engine using Kubernetes.
●	Using Globus Auth, login to a JupyterHub instance using an institutional identity. 
●	Select a Notebook Server from a catalog of containers. (We expect this will be a Python notebook, but it could also be R, for example.)
●	Launch the Notebook Server within the JupyterHub environment
●	Pass auth tokens into the notebook environment for use by Python libraries calling external APIs
●	Within a notebook, execute the following demos from above:
○	Demo 3: Service-service interoperation
○	Demo 4: Workflows on Galaxy/Globus Genomics
○	Demo 5: Virtual Cohorts
●	Capture the notebook and its output to record the analysis process.
●	Show how notebooks can be reused for training and outreach
Relationship to other full stacks
●	The list of demos can be extended to encompass other services secured using Globus Auth, as implemented by other full stack teams

