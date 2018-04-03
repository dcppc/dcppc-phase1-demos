Demo 2:  Use of identifiers to identify and access intermediate data
Here we show how persistent identifiers (Minids) associated with data described in Demo 1 can be used to access individual files, and how these identifiers can be associated with new data, such as data produced by data analyses, and then used to access those data.
●	Resolve an identifier provided for a specific file to access a landing page that provides minimal metadata, including checksum, which we use to validate the integrity of the data
●	Request and monitor transfer of data given only their identifier, with validation of data integrity using the checksum
●	Given a set of VCF files created as a result of an analysis on cloud compute, define a collection (represented as a BDBag) and create an identifier for that collection
●	Transfer the collection from cloud compute to cloud object storage
●	Share the new identifier with a collaborator and demonstrate download of the data using the identifier, plus and validation of the downloaded files
●	Search the collaboration’s catalog using the identifier to see if any linkage with source data exists. If not, put the intermediate data into the catalog so it can be associated with source data.

Relationship to other full stacks:
●	We will work with Teams Calcium, Xenon, and Helium to demonstrate interoperability using identifiers and BDBags.

