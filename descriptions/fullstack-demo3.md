# Full Stack DEMO3: FAIR Workflow Execution 
Demonstrate that a portable workflow can be scheduled by a researcher on two or more Full Stacks using the same API. (This really brings together DEMO1 and DEMO2.)

Example:
* Use a TOPMed workflow, the same from the above
* Two or more Full Stacks implement a common API (such as WES by GA4GH) to send workflows to stacks for remote execution 
(see KC3)
* Full Stacks issue tokens (or similar) based on researcher identity and authorization to run workflows in that environment 
(informed by KC6)
* Full Stacks have onboarded TOPMed/GTEx/MOD data into their stacks and use a common set of GUIDs to identify them (KC2)
* Researcher executes the same workflow on two or more Full Stacks, processing the same data in each environment. 
Importantly, they use the same workflow and are able to execute it using the same API interface on different Full Stacks 
referencing the distinct data with the same GUID scheme
* For the purposes of the demo the user triggering workflows can be a mock user but over time it is expected to be a 
real researcher from TOPMed/GTEx/MODs
