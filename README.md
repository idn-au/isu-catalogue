# ISU Catalogue

This is the source data of the [University of Melbourne](https://www.unimelb.edu.au/)'s [Indigenous Studies Unit](https://mspgh.unimelb.edu.au/centres-institutes/onemda/research-group/indigenous-studies-unit)'s [catalogue](https://data.idnau.org/pid/isucat) which has been established as part of 
the [Indigenous Data Network](https://idnau.org/)'s Catalogue Project.

This catalogue is online at:

* **[isu-catalogue](https://data.dev.idnau.org/catalogs/ns3:isu-catalogue)**


## Catalogue Resources

Resource | Role | Description
--- | --- | ---
Catalogue Definition:<br />[`catalogue.ttl`](catalogue.ttl) | [Catalogue Data](https://prez.dev/ManifestResourceRoles/CatalogueData) | The definition of, and medata for, the container which here is a dcat:Catalog object
Resource Data:<br />[`resources/*.ttl`](resources/*.ttl) | [Resource Data](https://prez.dev/ManifestResourceRoles/ResourceData) | sdo:CreativeWork objects in RDF (Turtle) files in the resources/ folder
Profile Definition:<br />[`ogc_records_profile.ttl`](https://github.com/RDFLib/prez/blob/main/prez/reference_data/profiles/ogc_records_profile.ttl) | [Catalogue & Resource Model](https://prez.dev/ManifestResourceRoles/CatalogueAndResourceModel) | The default Prez profile for Records API
Labels:<br />[`_background/labels.ttl`](_background/labels.ttl) | [Incomplete Catalogue and Resource Labels](https://prez.dev/ManifestResourceRoles/IncompleteCatalogueAndResourceLabels) | An RDF file containing labels for catalogue's content, auto-extracted from KurrawongAI's Semantic Background
Manual Labels:<br />[`_background/labels-manual.ttl`](_background/labels-manual.ttl) | [Incomplete Catalogue and Resource Labels](https://prez.dev/ManifestResourceRoles/IncompleteCatalogueAndResourceLabels) | An RDF file containing labels for catalogue's content, manually created
