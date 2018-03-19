# User Manual: mdEditor for LCCs

---

## **Overview**

**Making information discoverable, accessible, and usable**  
This manual describes how staff from the Landscape Conservation Cooperatives \(LCCs\) can create high-quality, consistent metadata to support the LCC Science Catalog, which will make LCC projects and products discoverable, accessible, and usable.

A unified LCC Science Catalog requires a standardized metadata format across the LCCs. With this ultimate goal in mind, this manual describes the requirements, recommendations, and best practices for the creation of LCC metadata records \(Contacts, Projects, and Products\). This guidance was developed by the LCC Data Management Working Group with the leadership of the Architecture Subgroup.

_This manual refers to the creation of LCC metadata specifically_. If you want information on the creation of other metadata records using MDEditor, or more information in general, please refer to the [MDEditor User Manual](https://adiwg.gitbooks.io/mdeditor/content/).

**LCC Science Catalog**

The Landscape Conservation Cooperative Science Catalog collates the metadata from all 22 LCCs and Headquarters. It allows for user-defined searching and filtering of projects and products as well as access to products for download. Users can see what has been funded, which can help prevent duplication of work. The LCC Science Catalog will also enable reporting, such as funding summaries or project examples based on particular geographies, species, organization, year, or other categories of interest.

**LCC Science Catalog Architecture**  
LCCs edit metadata in mdEditor and then publish the metadata to ScienceBase, where it can be channeled to the LCC Science Catalog and data.gov. The mdTranslator tool is integrated with mdEditor so you can create metadata once, and then convert and publish the metadata in your desired format, such as mdJSON for the LCC Science Catalog, sbJSON for ScienceBase, XML for data.gov, and FGDC for geospatial data.


---


## Overall Science Catalog System Architecture

_The following diagram details the science catalog system architecture._


![](/assets/science_catalog_system_architecture.png)
1. Items are imported from a database \(like ScienceBase\), or created directly in mdEditor.
2. mdJSON files can also be stored in a local repository and then transmitted via a web service to ScienceBase. Alternately, the  local files can be exported to a web accessible folder and then harvested by ScienceBase.
3. The mdTranslator converts the mdJSON files into sbJSON \(the ScienceBase JSON format\), and XML.
4. Items are exported from ScienceBase to: Data.gov as XML; the LCC Science Catalog website as Projects and Products; or into mdEditor as mdJSON.





{% include "git+https://github.com/adiwg/mdEditor-doc.git/README.md" %}

---
 ![]**Note: **This manual has been revised for LCC use. You may access the full mdEditor manual [**here**](https://adiwg.gitbooks.io/mdeditor/content/).
