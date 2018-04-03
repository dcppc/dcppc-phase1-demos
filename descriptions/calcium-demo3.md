DEMO 2 - Workflows
A given researcher pulls a workflow from Dockstore, runs on samples through FireCloud (or other workspace), generates output that can be shared in FireCloud (or other workspace) with other TOPMed researchers.

How this relates to other full stacks:
●	Register CWL and WDL versions of TOPMed workflow in Dockstore
○	Team Argon, Team Calcium, and potentially other teams will collaborate on creating a CWL/WDL workflow for TopMed data analysis, publish the workflow in DockStore.  
●	Each team will execute the workflow on test data and produce a comparable result.
○	The execution takes place via WES gateway for Team Calcium (Firecloud, Toil, and Framework services) and Team Xenon (can be a lambda proxy to SBG)
○	Team Argon will use the same workflow on datasets from Demo 1 to generate results that can be further analyzed using other team’s capabilities (effectively some form of Demo 3 below)
●	Also show UI-based workflow “Launch With” function in Xenon and Calcium platforms
How this will be demonstrated:
●	We will show the workflow in Dockstore
●	Each Team will live demo the launch of this workflow and switch to a precomputed result on the same sample, indicating concordant results across stacks
●	For those Teams supporting a GUI launch approach, live demo that UI
DEMO 3 - Distributed, Cross-Stack Compute
This demo would be a stretch goal in the sense that to fully demonstrate this we need buy-in from multiple full stacks.  The idea is to run all appropriate TOPMed pipelines on ~1000 WGS GTEx samples (or, alternatively, TOPMed data).  This computation would be spread across Toil (Azure), Firecloud (Google), SBG (AWS), and potentially other full stacks.  We would interoperate using the DOS and WES GA4GH APIs.  Workflows would be pulled from the Dockstore using the TRS GA4GH API.  The resulting data would be accessible via portals in our respective platforms and available for downstream analysis in respective full stack workspaces.

How this relates to other full stacks:
●	Stacks that want to participate need to agree on 1) supporting GA4GH APIs and 2) how to split the samples to process.  They need to 3) have the data staged in their system and 4) support for the TOPMed workflow created in Demo 2.
●	Stacks onboard all or a portion of GTEx data, expose the catalog of data via DOS, use agreed upon GUIDs (e.g. minids) and description manifest format (e.g. BDBags)
●	Stacks expose a WES endpoint for their workflow execution system
●	Stacks need to support CWL or WDL workflows from TRS
●	A tester chosen by the stacks (a mock researcher) triggers the running of the appropriate workflows across the stacks using the WES API and appropriate workflow version (CWL or WDL) on the subset of data available/assigned to that stack

How this will be demonstrated:
●	Each Team will live demo the results of the compute onboarded in their respective workspace/data browser UI
●	Each Team will show documentation for doing a similar compute for researchers using their respective stacks in the Commons

