# LCC Science Catalog System Architecture

---

A more detailed look at the parts and pieces behind the LCC Science Catalog.

---

_The following diagram details the LCC Science Catalog system architecture._

![](/assets/science_catalog_system_architecture.png)  
1. Items are imported from a database \(like ScienceBase\), or created directly in mdEditor.  
2. mdJSON files can also be stored in a local repository and then transmitted via a web service to ScienceBase. Alternately, the local files can be exported to a web accessible folder and then harvested by ScienceBase.  
3. The mdTranslator converts the mdJSON files into sbJSON \(the ScienceBase JSON format\), and XML.  
4. Items are exported from ScienceBase to: Data.gov as XML; the LCC Science Catalog website as Projects and Products; or into mdEditor as mdJSON.



