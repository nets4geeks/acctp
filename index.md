## Overview 

The Academic Cloud Computing Threat Patterns (ACCTP) catalog depicts common threats to cloud computer systems.
It is based on the data of the common security knowledge sources, as well as the academic community findings.
It “mines” the knowledge of the risk-oriented cloud security models and maps the risk-based terminology (risks, assets) 
to the design terminology (components, flows, threats).

The [ACCTP catalog](catalog.md) contains a set of profiles (architecture, compliance, privacy, IaaS, PaaS, SaaS, cloud storage); 
the entities are mapped to the STRIDE model.

The ACCTP catalog is well-formed with the [ontological SP schema](https://github.com/nets4geeks/SPCatalogMaker).
Entities are saved as JSON files. There is an OWL ontology and RDF dataset of the catalog data 
(see the [sources folder](https://github.com/nets4geeks/SPCatalogMaker/tree/master/catalogs/acctp/catalog)).
You can use the OWL ontology to make DL queries, for example, with the Protege editor,
and the RDF dataset to make the SPARQL requests with the Apache Jena toolset.
Also, the ACCTP catalog can be used as a source of domain specific threat model for 
the [ontology-driven threat modeling](https://github.com/nets4geeks/OdTM) of cloud systems with 
the DFD (Data Flow Diagram) approach.

## Resources

* The [ACCTP catalog](catalog.md)
* The [sources folder](https://github.com/nets4geeks/SPCatalogMaker/tree/master/catalogs/acctp/catalog)
* [References](references.md)

