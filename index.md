## Overview

The [Academic Cloud Computing Threat Patterns (ACCTP) catalog](catalog/) depicts common threats to cloud-based computer systems.
It “mines” knowledge of risk-oriented cloud security models and maps the risk-based terminology (risks, assets) 
to the design terminology (components, flows, threats).
It is based on the data of common security knowledge sources, as well as academic community findings
(see [references](references.md)).

The ACCTP catalog contains a set of profiles (architecture, compliance, privacy, IaaS, PaaS, SaaS, cloud storage); 
the entities are mapped to the STRIDE model.

The ACCTP catalog is well-formed with the [SPCatalogMaker](https://github.com/nets4geeks/SPCatalogMaker) toolset.
Entities are saved as JSON files. There is an OWL ontology and RDF dataset of the catalog data 
(see [sources folder](https://github.com/nets4geeks/SPCatalogMaker/tree/master/catalogs/acctp/catalog)).

The ACCTP catalog is used as a source of domain specific threat model for the 
[ontology-driven threat modeling](https://owasp.org/www-project-ontology-driven-threat-modeling-framework/) 
of cloud systems with Data flow diagrams (DFDs). Also, You can use the OWL ontology to make DL queries, 
for example, with the Protege editor, and the RDF dataset to create the SPARQL requests with the Apache Jena tool.

## Content

* [ACCTP catalog](catalog/)
* [Sources folder](https://github.com/nets4geeks/SPCatalogMaker/tree/master/catalogs/acctp/catalog)
* [SPCatalogMaker](https://github.com/nets4geeks/SPCatalogMaker)
* [References](references.md)

## Feedback

This is an open project and everyone is welcome to participate with contributions.
Please [send issues](https://github.com/nets4geeks/SPCatalogMaker/issues) 
and [get into the discussion](https://github.com/nets4geeks/SPCatalogMaker/discussions/1)
on GitHub.


license: [CC BY 4.0](http://creativecommons.org/licenses/by/4.0/)
