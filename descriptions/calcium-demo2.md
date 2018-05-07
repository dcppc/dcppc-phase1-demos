# Calcium Demo 2 - Data Availability

Onboard TOPMed CRAMs in Google/AWS clouds, agree on GUIDs used, setup accounts for researchers from TOPMed in the FireCloud and other environments.

How this relates to other full stacks:
*	We  onboard TOPMed/GTEx data in our respective systems using a common set of GUIDs (aliases)
	* We will collaborate with Team Argon and KC2 to come up with minids for TopMed datasets encapsulated as BDBags (and share these with the other full stacks so we can have agreed upon GUIDs for TOPMed/GTEx data)
*	Team Xenon, Team Calcium, and potentially other full stacks are implementing a DOS layer on top of our storage systems so data can be accessed in the same way, using the same IDs (or aliases). Can be a lambda proxy.
	* Both team Calcium and team Argon will use the same minids and BDBags for analysis on their respective platforms to generate results
*	Each system has a workspace or data browser so people can find the data in the respective systems. Importantly, all systems will point to the same data on cloud infrastructures (ie, data won’t be replicated for each stack). 
    *	Calcium will use Boardwalk for this 
    *	Xenon will use their own GUI web app
    *	Argon will use Globus
    *	Helium will use CommonsShare 
    
How this will be demonstrated:

*	Each Team will live demo the data onboarded in their respective workspace/data browser UI
