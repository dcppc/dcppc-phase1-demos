Demo 3: Secure interoperation with other (including new) Commons services
Our other demonstrations have already demonstrated secure interoperation among Team Argon services: e.g., Globus Transfer, Minids, Search, DERIVA. Here we will demonstrate secure service-to-service interoperation with another service, ideally one associated with another full stack team. If none such are available, we will develop a simple service for illustrative purposes (e.g., one that creates tissue expression heat maps).
●	Register this service as an OAuth2 server. 
●	Select permitted identity providers that can authenticate to the service (e.g., UChicago and NIH) and indicate that access to the GTEx dataset is needed to use the service.
●	Log in with permitted identity.  
●	Indicate approval for the service to access GTEx data
●	Make approved (and secure) HTTPS calls to access the data and execute the service, e.g. compute derived results

Relationship to other full stacks:
●	We will work with Team Calcium to demonstrate interoperability with a service that they provide.
●	We would also like to demonstrate having a Team Calcium stack user (or the user of another full stack) authenticate to Team Argon services.
●	It will be easy to incorporate other full stack services into the demonstration.

