# OAIS IP Ontology Project

This project structure includes:

- Folder **tbox** that contains:
  - The **oais-ip-tbox.owl** file that is OAIS IP ontology schema.
- Folder **abox** that contains three sets of individual assertions stored in the following ontology files:  
    - The **blue-statistics.owl** ontology file that contains individual assertions representing actual objects in *TIB Terminology Service Statistics* domain. 
    - The **blue-library.owl** file that contains individual assertions representing actual objects in *TIB Terminology Service Library* domain. 
    - The **green.owl** file that contains individual assertions representing actual objects in *CoyPu collection* domain. It states that CoyPu collection is composed of CoyPu collection content information. 
- Folder **images** that contains: 
  - The **oais-ip-tib-terminology-service-statistics.png** that depicts class hiearchy from OAIS IP ontology and related individual assertions from TIB Terminology Service Statistics domain. 
  - The **importing-mechanism-oais-ip-collection-project.png** that depicts how importing mechanism works in OAIS IP ontology project.
  
## Importing Mechanism

The **green.owl** ontology file imports the following ontology files:

- **blue-statistics.owl** that imports **oais-ip-tbox.owl**
- **blue-library.owl** that imports **oais-ip-tbox.owl**
- **oais-ip-tbox.owl**

In **blue.owl** ontology file *ObjectProperty* **composedOf** creates a link between CoyPu collection content information and TIB Terminology Srvice Statistics (AIP1).