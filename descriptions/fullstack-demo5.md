# Full Stack DEMO5: Researcher search and find data across the Full Stacks 
Demonstrate that researchers can produce new analysis results (through the demos above) and then share those results across the Full Stacks with other Commons users, perhaps running subsequent analysis.  This implies analysis is done, GUIDs minted, and the results indexed and available across Full Stacks.

* A researcher group working in a Full Stack to take a dataset defined by, perhaps, a BDBagit (see KC7, KC3), a group of researchers defined by a common mechanism (perhaps ORCID, see KC6), and a CWL/WDL workflow using Docker containers (as described in DEMO1-3)
* Execute the workflow on the dataset to produce a derived dataset that is assigned a new GUID (KC2) and is persisted to the cloud via the Full Stack used in this analysis
* The datasets should be accessible from the other Full Stacks (see KC3) and accessible to the same group of researchers regardless of Full Stack
* The same group of researchers then should be able to use a second Full Stack to perform additional analysis using another workflow, generating GUIDs, and being able to share.  Possibly even showing this chain on multiple Full Stacks.
* For the purposes of the demo the user triggering workflows can be a mock user but over time it is expected to be a real researcher from TOPMed/GTEx/MODs
* There is a lot of complexity in this DEMO related to common auth and data access.  I would classify this as a “stretch” goal for the 6 month pilot given the complexity.
