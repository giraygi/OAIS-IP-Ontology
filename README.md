# OAIS IP Ontology Project

This project contains:

- The oais-ip-tbox.owl file that is OAIS IP ontology shcema located in tbox folder of this project.
- Two sets of individual assertions stored in OWL files located in abox folder.  
  - The blue-statistics.owl ontology file contains individual assertions representing actual objects in TIB Terminology Service Statistics domain. 
  - The blue-library.owl file contains individual assertions representing actual objects in TIB Terminology Service Library domain. 
  - The green.owl file that contains individual assertions representing actual objects in CoyPu collection domain. It states that CoyPu collection is composed on CoyPu collection content information. 
- Folder images contains the following files: 
  - The oais-ip-tib-terminology-service-statistics.png that depicts class hiearchy from OAIS IP ontology and related individual assertions for TIB Terminology
    Service Statistics.
  - The importing-mechanism-oais-ip-collection-project.png that depicts how importing mechanism works in OAIS IP ontology project.
  
##Importing mechanism

The green.owl imports

- blue-statistics.owl that imports oais-ip-tbox.owl
- blue-library.owl that imports oais-ip-tbox.owl
- oais-ip-tbox.owl

In blue.owl ontology file Object Property composedOf creates a link between CoyPu collection content information and TIB Terminology Srvice Statistics (AIP1).