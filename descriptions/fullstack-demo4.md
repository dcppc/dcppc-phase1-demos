# Full Stack DEMO4: Researcher brings their own data and a workflow to the Full Stacks 
Demonstrate that researchers can combine new data with core Data Commons datasets to produce new analysis results (through the demos above).  The goal is to harmonize a researcher’s data with existing TOPMed/GTEx data using the same pipeline within a Full Stack.

* Researcher uploads new data (perhaps defined by BDBagit, see KC7, KC3)
* A group of researchers defined by a common mechanism (perhaps ORCID, see KC6) identifies a CWL/WDL workflow using Docker containers (as described in DEMO1-3)
* The team executes the workflow on the novel dataset to produce a derived dataset that is assigned a new GUID (KC2) and is persisted to the cloud via the Full Stack used in this analysis
* The same group of researchers is then able to reference this result and share with other researchers within the full stack (see DEMO5 for a more ambitious, cross-stack version of this)  
* For the purposes of the demo the user triggering workflows can be a mock user but over time it is expected to be a real researcher from TOPMed/GTEx/MODs
* There is considerable complexity in this DEMO related to common auth and data access.  We classify this as a “stretch” goal for the 6 month pilot given the complexity.
