# Helium Demo 11: Perform a FAIRness assessment of test data sets via a web interface.

A specific example of how the aforementioned [Fairness Assessment of a test dataset](helium-demo10.html) may be manually assessed and scored via a Data Commons web interface is as follows:

* A user logs into CommonsShare web interface to perform FAIR-TLC actions demonstrating FAIR-TLC (Findable, Accessible, Interoperable, Reusable, Traceable, Licensed, Connected; http://dx.doi.org/10.5281/zenodo.203295). 
* In this demo/assessment, we’ll use the example resource created in the “Upload and annotate novel data to at least one stack via a web interface” demo titled “My Novel CWL Resource” that has has its Sharing status set to “Public” indicating it can be viewed and downloaded by anyone.
* To demonstrate/assess Findable, the user navigates to the “Discover” tab and and enters into the text entry search box any combination and/or subset of the resource’s Title, GUID, and/or Subject Keywords.
* For example, the user types in “novel” and the desired resource is demonstrated/assessed to be Findable with rich metadata clearly associated with the resource. 
* The resource is demonstrated/assessed to be Accessible by being retrievable via a public CommonsShare REST API within a Swagger Framework that allows the resource data, metadata to be accessible with authentication and authorization.  
* The resource is demonstrated/assessed to be Interoperable by storing all resources in BagIt hierarchical file packaging format (https://en.wikipedia.org/wiki/BagIt) downloadable with a resourcemap and resourcemetadata stored in XML, i.e. a broadly applicable language for knowledge representation. 
* The resource is demonstrated/assessed to be Reusable by basing the resourcemap and resourcemetadata on the Open Archives Initiative’s Object Reuse and Exchange (OAI-ORE) standard (https://www.openarchives.org/ore/).  
* The resource is demonstrated/assessed to be Traceable with clearly denoted Attribution and Provenance with derived content credited using its original identifier and linked using a persistent GUID reference clearly visible below the resource title.  
* The resource is demonstrated/assessed to be Licensed with clearly denoted licensure on the resource landing page and clearly selectable choices of standard licenses as well as the ability for the user to enter an “other” license with area to enter a License Statement, URL, and a checkbox to require agreement to rights statement before downloading. 
* The resource is demonstrated/assessed to be Connected to other resources including one or more resources the current resource is derived from and/or is a version of by clearly denoting “Related” resources on the resource landing page; related is the ability to denote the Relationship type from a drop-down menu of choices. 
* As each aspect of this demonstration is performed via the Data Commons web interface, its Fairness is assessed and scored.
