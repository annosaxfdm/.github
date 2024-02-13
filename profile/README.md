# The ANthropological Notation Ontology (ANNO): A core ontology for annotating human bones and deriving phenotypes

The Anthropological Notation Ontology (ANNO) allows the systematic and standardized classification of recovered bone finds into the skeletal system, the description of the skeletal pieces, and the definition of functions for the derivation of different phenotypes of humans in forensic and historical anthropology.
ANNO consists of two components:
ANNOdc, a domain-core ontology providing core entities such as basic anatomical categories, and ANNOds, a domain-specific ontology used for annotating structures of the human skeleton.
ANNO is integrated into AnthroWorks3D, a photogrammetry pipeline and application for the creation and analysis of 3D-models of human skeletal remains.
The integration is based on the three-ontology method with the General Formal Ontology as the top-level ontology, ANNOdc as the task ontology and ANNOds as the domain ontology.
Thus, AnthroWorks3D only needs to implement access to the entities (classes and properties) of the task ontology, whereas the entities of the corresponding domain ontology are imported dynamically.
ANNO supports the analysis of skeletal and bone finds in forensic and historical anthropology, facilitating the standardization of data annotation and ensuring accurate preservation of information for posterity. 

## Links

* [Project website](https://annosaxfdm.de)
* [RDF browser](https://annosaxfdm.de/ontology/)
* [OLS terminology server](https://ols.imise.uni-leipzig.de/ontologies/anno)
* [Journal paper (under review)](https://github.com/annosaxfdm/anno-paper-swj)
