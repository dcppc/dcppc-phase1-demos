# Full Stack DEMO2: FAIR Data Ingestion and Access 
Demonstrate the ability of a researcher to find TOPMed/GTEx/MOD data across multiple Full Stacks using common GUIDs. 

Example:
* TOPMed/GTEx/MOD data are present on AWS and Google buckets now, Azure TBD. All Full Stacks will utilize the same files on each cloud infrastructure
* A minimal GUID scheme (informed/replaced by services developed by KC2) is used to identify these files and link them to metadata (on donors, samples, aliquots, etc.) based on metadata selected/organized by KC7
* Data access permissions are determined based on a user’s current data approvals (informed by KC6)
* Minimally, the data is accessible to an approved user via these GUIDs in the Full Stack’s workflow engine
* Ideally, we identify a common data object service API (such as DOS from GA4GH or S3 via Globus, see KC3) that the data onboarded can be accessed consistently across Full Stacks
