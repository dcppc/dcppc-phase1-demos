# Helium Demo 12: Research brings their own data, combines it with other data, and runs a workflow.

Researcher brings their own data to helium platform; combines it with GTEx or MOD data; runs a CWL workflow on the data; saves and analyzes the output data; captures the data and workflow as a reproducible workspace shared with colleagues with GUIDS minted pointing to BDBags for all data and workflows.

•         Researcher logs into CommonsShare and creates a Reference Resource pointing to their own data. As with all CommonsShare resources, a GUID and metadata are assigned to the Resource and stored in BDBag format.
•         Researcher creates Workspace Resource in CommonsShare, and adds the Reference Resource from the prior step to it.  As with all CommonsShare resources, a GUID and metadata are assigned to the Resource and stored in BDBag format.
•         Researcher adds additional data from their desktop computer and GTEx or MOD data to the CommonsShare Workspace Resource.  
•         Researcher adds a CWL workflow as an additional Resource to the CommonsShare Workspace Resource that will use a combination of the existing data entered above as input.
•         Research will select an “Open With” on the Resource landing page to run the workflow in the Helium PIVOT cloud-agnostic architecture.
•         Results will be placed via REST API into the Workspace Resource as a new Reference Resource with its own GUID and Metadata.
•         Researcher will navigate to the Results Reference Resource within the Workspace Resource and open an App from the Helium App Store to analyze the results.
•         Researcher will share the CommonsShare Workspace created with a colleague, and the colleague will be able to reproduce the results.
•         This Helium demo will be presented live and captured on video and will be made available as a public resource in CommonsShare generally available for download and viewing.

