# The DemKG framework
DemKG is a framework that allows you to build a Knowledge Graph and integrate your experimental research data. DemKG has a special focus on the Dementia research space, implementing specific terminological extensions and design patterns. 

The framework builds upon community efforts: 
* [OBO ontologies](http://obofoundry.org/), some previously transformed from [KG-OBO](https://github.com/Knowledge-Graph-Hub/kg-obo)
* The [Monarch KG](https://monarchinitiative.org/) and annotations.
* [Reactome](https://reactome.org/)
* [String](https://www.string-db.org/) PPI database. 

DemKG is comprised of three main modules:
* The [extensions ontology](https://github.com/demkg-framework/extensions-ontology). An OWL ontology that models classes and relationships to provide relevant terms needed for Dementia research data.
* The [transformation module](https://github.com/demkg-framework/kg-transform). A Python package that allows you to easily transform your tabular source data into a sub-graph following robust semantic design patterns.
* The [KG-Builder](https://github.com/demkg-framework/kg-builder). A module built with Python and ODK that gathers the Knowledge Sources along with your transformed data and constructs the final KG.

