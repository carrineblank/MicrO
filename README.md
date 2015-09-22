# MicrO
A Microbial Ontology of Phenotypic Characters Found in Prokaryotic Taxonomic Descriptions

Alpha Version

Created by Carrine E. Blank, University of Montana, fall 2013 through summer 2015.

This alpha version of the ontology includes terms and term synonyms found in over 1200 prokaryotic taxonomic descriptions, collected from a diverse set of taxonomic descriptions from Archaea, Cyanobacteria, Bacteroidetes, and Mollicutes.

Contains ~ 1,550 terms and term definitions, along with thousands of term synonyms.  Constructed in OWL Protégé; following OBO Foundry principles.  Imports ~10,240 terms from 15 other ontologies, including Phenotype Quality (PATO), the Gene Ontology (GO), and Chemical Entities of Biological Interest (ChEBI).  Contains >20,500 logical axioms connecting entities and processes across multiple ontologies to facilitate inference of higher-order phenotypic traits.

Many thanks to Hong Cui (University of Arizona), Ramona Walls (New York Botanical Garden), Lisa Moore (University of Southern Maine), Gail Gasparich (Towson University), and Gordon Burleigh (University of Florida) for assistance with ontology construction and compilation of taxonomic descriptions.

Thanks to Oliver He (University of Michigan) for technical assistance with OntoBee and OntoFox, and Gareth Owen (ChEBI project leader, head curator) for assistance in the incorporation of microbial-specific chemical terms and synonyms into ChEBI.

Thanks also to the instructors (Melissa Haendel, Matt Yoder, Jim Baihoff) and students of the 2013 NESCent Ontologies for Evolutionary Biology workshop, and to Karen Cranston (NESCent director) and the support staff at NESCent.

This work was supported by a grant from the National Science Foundation Assembling the Tree of Life Program (DBI-1208534), and by a travel grant to attend the 2013 NESCent Ontologies for Evolutionary Biology workshop.

***TO DOWLOAD***

1.  Download the folder "MicrO and Import Modules"

2.  Execute using Protege v. 4.3 or Protege v. 5.0.0 (runs in beta 17).

3.  Once executed you can then run the reasoner.

***KNOWN ISSUES***

1.  Logical axioms for three classes of microbiological culture media are not functioning.

2.  There are a number of new terms that are being requested for entry into ChEBI.  Temporary terms are located under the class "ChEBI terms to be added and processed"

3.  External ontologies are currently being imported using temporary owl files (created by OntoFox) in the "MicrO and Import Modules" folder.  Once the domain name request has been approved and purl addresses assigned, these will be replaced.