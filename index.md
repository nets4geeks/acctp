## Overview 

The [Academic Cloud Computing Threat Patterns (ACCTP) catalog](catalog.md) depicts common threats to cloud-based computer systems.
It “mines” knowledge of risk-oriented cloud security models and maps the risk-based terminology (risks, assets) 
to the design terminology (components, flows, threats).
It is based on the data of common security knowledge sources, as well as academic community findings
(see [references](references.md)).

The ACCTP catalog contains a set of profiles (architecture, compliance, privacy, IaaS, PaaS, SaaS, cloud storage); 
the entities are mapped to the STRIDE model.

The ACCTP catalog is well-formed with the [SPCatalogMaker toolset](https://github.com/nets4geeks/SPCatalogMaker).
Entities are saved as JSON files. There is an OWL ontology and RDF dataset of the catalog data 
(see [sources folder](https://github.com/nets4geeks/SPCatalogMaker/tree/master/catalogs/acctp/catalog)).
You can use the ontology to make DL queries, for example, with the Protege editor,
and the dataset to make the SPARQL requests with the Apache Jena tool.
Also, the ACCTP catalog can be used as a source of domain specific threat model for 
the [ontology-driven threat modeling](https://owasp.org/www-project-ontology-driven-threat-modeling-framework/) 
of cloud systems with Data flow diagrams (DFDs).

## Content

* [ACCTP catalog](catalog.md)
* [Sources folder](https://github.com/nets4geeks/SPCatalogMaker/tree/master/catalogs/acctp/catalog)
* [References](references.md)

