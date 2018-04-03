# Argon Demo 4: Run Galaxy/Globus Genomics workflow, with cost-aware data staging and provisioning 

Here we assume that: a) data (e.g., TOPMed) are stored in object
storage in two different Amazon regions (e.g., R1 & R2); b) an
identifier (Minid) is provided that references a BDBag containing a
subset of those data; and c) Teams Argon and Calcium, and potentially
other teams, have collaborated to create a workflow for TOPMed data
analysis, and have published CWL and WDL versions of that workflow in
DockStore.

*	Retrieve a TOPMed analysis workflow (e.g., variant calling) from Dockstore
*	Estimate the cost of executing the workflow on various AWS instance types in both R1 and R2, based on their current spot prices
*	Select the cheapest region + instance type(s) combination, provision instances for execution, access an identifier to stage a BDBag containing required data to the compute instances, and execute the workflow on those instances 
*	Generate output as a BDBag with an associated identifier, so it can be be accessed by other TOPMed researchers. 

How this relates to other full stacks:
*	Each team participating in this demo will execute the workflow on the same test data and produce a comparable result.
*	The execution takes place via WES gateway for Team Calcium (Firecloud, Toil, and Framework services), on Globus Genomics for Team Argon and Team Xenon (can be a lambda proxy to SBG)
*	Team Argon will use the workflow to generate results that can be further analyzed using other team’s capabilities (effectively some form of Demo 2 below)

