# Calcium Demo 3 - Workflows

A given researcher pulls a workflow from Dockstore, runs on samples
through FireCloud (or other workspace), generates output that can be
shared in FireCloud (or other workspace) with other TOPMed
researchers.

How this relates to other full stacks:
*	Register CWL and WDL versions of TOPMed workflow in Dockstore
	* Team Argon, Team Calcium, and potentially other teams will collaborate on creating a CWL/WDL workflow for TopMed data analysis, publish the workflow in DockStore.  
*	Each team will execute the workflow on test data and produce a comparable result.
    *	The execution takes place via WES gateway for Team Calcium (Firecloud, Toil, and Framework services) and Team Xenon (can be a lambda proxy to SBG)
	* Team Argon will use the same workflow on datasets from Demo 1 to generate results that can be further analyzed using other team’s capabilities (effectively some form of Demo 3 below)
*	Also show UI-based workflow “Launch With” function in Xenon and Calcium platforms
How this will be demonstrated:
*	We will show the workflow in Dockstore
*	Each Team will live demo the launch of this workflow and switch to a precomputed result on the same sample, indicating concordant results across stacks
*	For those Teams supporting a GUI launch approach, live demo that UI

