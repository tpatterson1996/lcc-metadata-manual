## Adding PRODUCTS: Quick Reference

---

This page will provide a brief overview of required fields for a metadata Product record, for more in-depth information, rationale and instructions, please see the relevant section page.

---

### Required/Recommended Fields for Products:

_To see the fields described in this Quick Reference, select the green edit button next to an existing record in the left vertical menu, or _[_create a new record_](/record-new.md)_._

#### **Main Tab**

##### **In Main/Basic Information, Resource Type, Point of Contacts**

See [Record Main](/record/main.md) for more information

| **Field** | **Instructions/Notes on Entering** |
| :--- | :--- |
| Record ID \(Required\) | The Record ID will be generated automatically. |
| Title \(Required\) | Enter a title. **Best Management Practice \(BMP\): **Since products and projects are independent records, we recommend having as informative a title as possible. Good titles, when they appear in a search, will be understood and/or traceable. |
| Status \(Required\) | Choose status ONLY from the four following options: Completed, On Going, Proposed, or Accepted. |
| Default Locale \(Required\) | Language should be set to _**English**,_ Character set to_ **UTF-**_**8,** Country set to_ **USA. **_ |
| Resource Type \(Required\) | Enter appropriate item from picklist. It is important to properly identify the resource type for improved discoverability. The most commonly used product resource types are: _report, document, publication, presentation, factsheet, user guide, dataset \(geographic\), tile \(geographic raster\), non-geographic dataset, tabular dataset map, model, photographic image, application \(online\), software, and website._ |
| Point of Contact \(Required\) | Enter the LCC Network Data Steward as a “pointOfContact.” This is important so that there is a point of contact that users can reach even if there is a positional change in an organization \(see [Contacts ](/contacts.md)for more information\). |
|  | **Best Management Practice**:  Enter your LCC as "administrator" and the Project PI as "principalInvestigator." |

**In Main/Citation**

See [Main Citation ](/record/main/citation.md)for more information

| Field | Instructions/Notes On Entering |
| :--- | :--- |
| Title \(Auto-Generated\) | Added automatically based on the title of your record. |
| Alternate Title \(Optional\) | Enter a shorter title. |
| Dates \(Optional\) | Enter _acquisition, creation, revision,_ or another date reference from the picklist and then enter the date. |
| Responsible Parties \(Required\) | Enter your LCC as "administrator." |
|  | Enter the Network Data Steward as "pointOfContact." This is important so that there is a point of contact that users can reach even if there is a positional change in an organization \(see [Contacts ](/contacts.md)for more information\). |
|  | **Best Management Practice:** Add your LCC, and the project PI. Enter your LCC as "administrator" and the Project PI as "principalInvestigator." |
|  | You can also add funders \(including your LCC, Partners, Collaborators, and/or Contributors\) |
| Online Resources** **\(Required, If Available\) | Enter the URL for any project related website \(ie. PI has website information\) |
| Identifier \(Required\) | Enter ScienceBase ID \[gid-optional\], if available.** This is recommended if the metadata was developed in mdEditor and there is a corresponding ScienceBase item. **mdEditor can use the SBID to locate and publish the metadata to the correct item in ScienceBase. |
|  | \(Recommended, if available\) Enter Digital Object Identifier, if available |
|  | \(Recommended, if available\) Enter any internal project ID, up to 32 characters |
|  | \(Optional\) Enter funding identifier, if desired |
|  | \(Optional\) Enter archive folder name, if desired |
|  | **Note:** If the product metadata was created from copying another metadata record, this identifier needed to be edited/changed since it will reflect the copied record identifier. Only the mdEditor UUID changes to represent a new record when an item is copied. |

**In Main/Description**

See [Record Main](/record/main.md) for more information

| Field | Instructions/Notes On Entering |
| :--- | :--- |
| Abstract \(Required\) | **Best Management Practice**: Write your abstracts for projects in the present tense if the project is underway and past tense if it has been completed. |
| Short Abstract \(Optional\) | Enter a short description of the project, if desired |
| Supplemental Information \(Optional\) | Enter comments, if desired |

**In Main/Time Period**

See [Record Main](/record/main.md) for more information

| Field | Instructions/Notes On Entering |
| :--- | :--- |
| Date \(Required\) | Enter Start Date and End Date |

---

### Metadata TAB

**In Metadata/Basic Information**

See [Record Metadata ](/record/metatdata.md)for more information

| Field | Instructions/Notes on Entering |
| :--- | :--- |
| Metadata Status \(Required\) | Choose Status from Metadata Picklist |
| Date \(Required\) | Enter a date for "creation," "last updated," or "finalized." |

**In Metadata/Contacts**

See [Record Metadata ](/record/metatdata.md)for more information

| Field | Instructions/Notes on Entering |
| :--- | :--- |
| Point Of Contact \(Required\) | Enter the LCC Network Data Steward as a “pointOfContact” |
| Author \(Optional\) | Enter your LCC data manager as the “author.” You do not need to use individual names and can create a generic data manager for your LCC, but this is up to the individual LCC. |
| Publisher \(Recommended\) | **Best Management Practice**: Enter your LCC as the "publisher" |

**In Metadata/Identifier & Parent Metadata**

See [Parent Metadata](/record/metatdata/parent-metadata.md) for more information

| Field | Instructions/Notes on Entering |
| :--- | :--- |
| Identifier \(Required\) | If record was imported from ScienceBase, this field is auto-populated with the ScienceBase identifier; |
|  | If record is created new in mdEditor, mdEditor references the mdEditor identifier, UUID. If there is not currently a ScienceBase Identifier, leave the mdEditor UUID; |
|  | If there is a ScienceBase Identifier, you may enter it here, but if there are associated items, changing this identifier may void those connections. It is recommended to enter the ScienceBase identifier in Main/Citation/Identifier. |
|  | **Best Management Practice**: If you know the ScienceBase identifier \(SBID\), add it in the metadata identifier _when you create the record_. When you start to associate the item, changing the metadata identifier can break the links. |
| Parent Metadata \(Required\) | Parent Metadata** **is used to define the folder on ScienceBase where the project or product will be published to. Items added to the parent folder are considered children \(or child items\) of that folder. |
|  | Enter the ScienceBase ID of the parent item--if record was imported from ScienceBase, this field is auto populated; if record is created new in mdEditor and has a corresponding parent item in ScienceBase, the identification information should be populated here. Double-check that these values are correct; If this record is created new in mdEditor and does not exist in ScienceBase, populate the parent metadata with the parent ScienceBase identifier, if present in ScienceBase. Recommended workflow is 1\) complete project metadata, 2\) complete child product metadata and associate the items. In this way, parent-child relationships can be defined. |
|  | **Note:** If items are moved in ScienceBase, and the parent metadata is not changed in mdEditor, when mdEditor publishes to ScienceBase, the parent-child relationships in ScienceBase will be overwritten. |

**In Metadata/Repositories**

See [Record Metadata ](/record/metatdata.md)for more information

| Field | Instructions/Notes on Entering |
| :--- | :--- |
| Repository | For **Projects **that should be listed in the LCC Science Catalog, Enter “LCCScienceCatalog” from the pick-list as repository and “LCC Network Science Catalog” as collection title \(these should be entered in your Settings as default repositories.** Note**: this is  a free-text field so the title must be exactly the same in order to insure that the metadata is harvested for the LCC Science Catalog.\) |
|  | For **Data Products **that should be shared with Data.gov, Enter “data.gov” and “data.gov” from the pick-list as repository and enter “data.gov” followed by your LCC name as the collection title. **Note:** this is a free-text field so the title must be exactly the same in order to insure that the metadata is harvested for the LCC Science Catalog.\) |
|  | **Best Management Practice**: In Settings, create default repositories to help maintain precise titles |

**In Metadata/Online Resources**

See [Record Metadata ](/record/metatdata.md)for more information

| Field | Instructions/Notes on Entering |
| :--- | :--- |
| Online Resource \(Optional, Required if available in Main/Citation/Online Resources \) | Enter a URL for any other project related website-optional \(ie. PI has website information or data hosting site\) |

---

### Keywords Tab

See [Record Keywords ](/record/keywords.md)for more information about editing and adding thesauruses.

| Thesaurus | Instructions | Notes |
| :--- | :--- | :--- |
| LCC Category Thesaurus | Choose from picklist \(Category\) |  |
| LCC Delivery Type Thesaurus | Choose from picklist \(Deliver\) |  |
| LCC End User Type Thesaurus | Choose from picklist \(Usertype-optional\) |  |
| Custom Thesaurus | Title thesaurus as EndUsers \(endusers-optional\) | Enter enduser keywords that do not appear in the usertype keywords |
| ISO Topic Category Thesaurus | Choose from picklist \(topicCategory\) |  |
| Custom Thesaurus | Title thesaurus as subject \(subject-optional\) | Enter Subject Keywords |
| Custom Thesaurus | Title thesaurus as geographic \(geog-optional\) | Enter geographic keywords |
| Custom Thesaurus | Title thesaurus as Conservation Target \(ConservationTarget-optional\) | Enter conservation target keywords |
| Custom Thesaurus | Title thesaurus as State/Province \(state/province-optional\) | Enter state/Province keywords\* |
| Congressional Districts | \[congdist\] | Recommend to include geographic extent to mdEditor \(see Extent TAB, below\). Congressional districts can be derived later. \(BMP\) |
| GCMD Science Thesaurus | Choose from picklist and include full path \(recommended\) |  |

---

### Extent Tab

See [Record Extent ](/record/record-extent.md)for more information about how to add Extents.

| Notes & Best Management Practices |
| :--- |
| Extents are recommended, but not required. It is Recommended that you use an extent since they can be used to populate Congressional districts once that capability is available. |
| **Notes: ** |
| Add a bounding box or simple extent in WGS84 coordinate system. The extent must use geographic coordinates, not projected coordinates. |
| Extents are imported from ScienceBase records, can be drawn in mdEditor, or can be dragged and dropped into mdEditor from multiple file types. |
| The bounding box does not work across datelines. However, you can have more than one extent, so if your area crosses a dateline, split the area and create separate extents. |
| **Best Management Practices: ** |
| Extents should be simple with a modest number of vertices. The extent is for display and discovery only. |
| Shapefiles are limited to 5000 vertices. It is recommend that you create only simple polygons or bounding boxes. If you want greater detail, attach high-definition shapefiles instead of trying to draw them. |

---

### Spatial Tab

| Field | Notes |
| :--- | :--- |
| Spatial \(Required for Datasets Only\) | Enter the type of spatial dataset from the picklist. Common types include: _grid, tin, and vector._ |
| Spatial Resolution \(Recommended\) | Often geospatial metadata accompanying the geodata will include this detailed information. |
|  | You can also import FGDC metadata into mdEditor. |
|  | **Note**: It is undesirable to have multiple metadata files affiliated with a single product. |

---

### Lineage Tab

| Notes |
| :--- |
| Not required for LCC product metadata, but recommended. Lineage tab designed for documenting the creation of spatial data metadata |
| Can document who did the process, including  role and contact. |
| If you have citation for a manual, you can simply create a citation instead of having to enter the information into the metadata |
| Use the Sources field to indicate what you used to create the product and then write a statement \(can do instead of writing all other steps\). |

---

### Distribution Tab

| Field | Notes |
| :--- | :--- |
| Distribution \(Required\) | This documents how people go about obtaining your product \(e.g., your website, download from PI website, from an archive, etc.\). If it’s not online, describe how to obtain it \(e.g., not available to public but contact someone to obtain\). |
|  | **Note: **This section will most likely simply involve adding distributer information and URL for data products that are hosted elsewhere. \(e.g., if The Nature Conservancy is hosting a data source, the distributor is "The Nature Conservancy" and then enter a link to location of distribution\). |
| Distributor Contact \(Required\) | Enter contact from contact list |
| Distributor Role \(Required\) | Input “distributor” |
| Transfer Size \(Recommended\) | Describe size of resource \(in MB\). |
| Distribution Units \(If Applicable\) | Used for items with unique units \(e.g. USGS quads\). If this is not applicable, leave blank. |
| Online Options \(If Applicable\) | Add URL here and type of URL space. If it’s a direct download, select “download.” If it goes to an informational page, select “information.” |
| Offline Options \(If Applicable\) | Add contact information for how to obtain product offline. |

---

### Constraints Tab

| Constraint Type | Definition |
| :--- | :--- |
| Use Limitation | Enter text that describes how people should or should not use the product. Depending on the type you select, it will tell you what you have to enter. If your product is licensed, let people know. Most of what we have is public domain, but not always. |
| Legal | Select the access and property restraints from the controlled value list. _Access constraints_: apply to assure the protection of privacy or or intellectual property, and any special restrictions or limitations on obtaining the resource._ Use constraints_: detail how the product should be used. _Other constraints_: this a good place to put a standard disclaimer. |
| Security Constraints | Describe legal constraints or security pertaining to security of the resource, need to choose classification. _Classification is the Identify class of security \(e.g., top secret, public access\)._ |

---

### **Associated Tab **

| Notes on Associated Records |
| :--- |
| The Associated section is used to connect items with each other. This feature should be used when items are related. I.E. Products are often the result of projects, and projects often have sub projects. All of these can be linked together by means of association. |
| Add or import items that are parent projects of products. |
| If the project record is from ScienceBase and it was linked \(as an Associated Item of type "parentProject"\) to its ScienceBase Product record, then the Associated tab will already be populated correctly as described below, and should be reviewed. |
| If not associated from ScienceBase, you can associate in this section. Make sure that the relevant Project record is loaded into mdEditor. Choose “parentProject” as the Association Type. Click "Select a Record" \(on the right\), find the project record, and select it. This will fill in all the needed fields for the current association |

---

### Funding **Tab \(Not required for Products\) **

| Notes |
| :--- |
| Funding information is not required for products. |

---

### Contacts **Tab**

See [Contact New](/contact.md) for information on entering contacts.

| Notes/Best Management Practices |
| :--- |
|  |

---



