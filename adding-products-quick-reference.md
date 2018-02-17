## Adding PRODUCTS: Quick Reference

---

This page will provide a brief overview of required fields for a metadata Product record, for more in-depth information, rationale and instructions, please see the relevant section page.

---

### Overview of Required/Recommended Fields for Products:

To see the fields described in this Quick Reference, select the green edit button next to an existing record in the left vertical menu, or [create a new record](/record-new.md).

### **Main Tab**

##### **In Main/Basic Information, Resource Type, Point of Contacts**

| **Field** | **Instructions/Notes on Entering** |
| :--- | :--- |
| Record ID \(Required\) | The Record ID will be generated automatically. |
| Title \(Required\) | Enter a title. **Best Management Practice \(BMP\): **Since products and projects are independent records, we recommend having as informative a title as possible. Good titles, when they appear in a search, will be understood and/or traceable. |
| Status \(Required\) | Choose status ONLY from the four following options: Completed, On Going, Proposed, or Accepted. |
| Default Locale \(Required\) | Language should be set to _**English**,_ Character set to_ **UTF-**_**8,** Country set to_ **USA. **_ |
| Resource Type \(Required\) | Enter appropriate item from pick-list. It is important to properly identify the resource type for improved discoverability. The most commonly used product resource types are: _report, document, publication, presentation, factsheet, user guide, dataset \(geographic\), tile \(geographic raster\), non-geographic dataset, tabular dataset map, model, photographic image, application \(online\), software, and website._ |
| Point of Contact \(Required\)  | Enter the LCC Network Data Steward as a “pointOfContact.” This is important so that there is a point of contact that users can reach even if there is a positional change in an organization |
|  | **Best Management Practice**:  Enter your **LCC** as "administrator" and the Project PI as "principalInvestigator." |

**In Main/Citation**

| Field | Instructions/Notes On Entering |
| :--- | :--- |
| Title \(Auto-Generated\) | Added automatically based on the title of your record. |
| Alternate Title \(Optional\) | Enter a shorter title. |
| Dates \(Optional\) | Enter _acquisition, creation, revision,_ or another date reference from the pick-list and then enter the date. |
| Responsible Parties \(Required\) | Enter your LCC as "administrator."  |
|  | Enter the Network Data Steward as "pointOfContact." This is important so that there is a point of contact that users can reach even if there is a positional change in an organization |
|  | **Best Management Practice:** Add your LCC, and the project PI. Enter your LCC as "administrator" and the Project PI as "principalInvestigator." |
|  | You can also add funders \(including your LCC, Partners, Collaborators, and/or Contributors\) |
| Online Resources** **\(Required, If Available\) | Enter the URL for the project homepage on your LCC website |
| Identifier \(Required\) | **Best Management Practice:** Enter ScienceBase ID \(SBID\), if known. mdEditor can use the SBID to locate and publish the metadata to the correct item in ScienceBase. |
|  | \(Recommended, if available\) Enter Digital Object Identifier, if available |
|  | \(Recommended, if available\) Enter any internal project ID, up to 32 characters |
|  | \(Optional\) Enter funding identifier, if desired |

**In Main/Description**

| Field | Instructions/Notes On Entering |
| :--- | :--- |
| Abstract \(Required\) | **Best Management Practice**: Write your abstracts for projects in the present tense if the project is underway and past tense if it has been completed. |
| Short Abstract \(Optional\) | Enter a short description of the project, if desired |
| Supplemental Information \(Optional\) | Enter comments, if desired |

**In Main/Time Period**

| Field | Instructions/Notes On Entering |
| :--- | :--- |
| Date \(Required\) | Time Period refers to project start and end date, or the date that the project was applicable \(time that the project was funded to date of completion\). |
|  | For each project, add a start, end date, and fiscal year. |

---

### Metadata TAB

**In Metadata/Basic Information**

| Field | Instructions/Notes on Entering |
| :--- | :--- |
| Metadata Status \(Required\) | Choose Status from Metadata Pick-list |
| Date \(Required\) | Enter a date for "creation" or "last updated" |

**In Metadata/Contacts**

| Field | Instructions/Notes on Entering |
| :--- | :--- |
| Point Of Contact \(Required\) | Enter the LCC Network Data Steward as a “pointOfContact” |
| Author \(Optional\) | Enter your LCC data manager as the “author.” You do not need to use individual names and can create a generic data manager for your LCC, but this is up to the individual LCC. |
| Publisher \(Recommended\) | **Best Management Practice**: Enter your LCC as the "publisher" |

**In Metadata/Identifier & Parent Metadata**

| Field | Instructions/Notes on Entering |
| :--- | :--- |
| Identifier \(Required\) | Enter the ScienceBase ID \(SBID\). If the record was imported from ScienceBase, this field will be auto-populated.  If  the record was created new in mdEditor, mdEditor will populate the identifier field with the and has a corresponding item in ScienceBase, the identification information must be entered here.** ** |
|  | **Best Management Practice**: If you know the ScienceBase identifier, add it in the metadata identifier when you create the record. When you start to associate the item, changing the metadata identifier can break the links. |
| Parent Metadata \(Required\) | Parent Metadata** **is used to define the folder on ScienceBase where the project or product will be published to. Items added to the parent folder are considered children \(or child items\) of that folder. |
|  | Enter the ScienceBase ID of the parent item--if record was imported from ScienceBase, this field is auto populated; if record is created new in mdEditor and has a corresponding parent item in ScienceBase, the identification information should be populated here, double check that these values are correct; If this record is created new in mdEditor and does not exist in ScienceBase, populate the parent metadata with the parent sciencebase identifier, if present in Sciencebase. Recommended workflow is 1\) complete project metadata, 2\) complete child product metadata and associate the items. In this way, parent-child relationships can be defined. |
|  | **Note:** If items are moved in ScienceBase, and the parent metadata is not changed in mdEditor, when mdEditor publishes to ScienceBase, the parent-child relationships in ScienceBase will be overwritten. |

**In Metadata/Repositories**

| Field | Instructions/Notes on Entering |
| :--- | :--- |
| Repository | For Projects that should be listed in the LCC Science Catalog, Enter “LCCScienceCatalog” from the picklist as repository and “LCC Network Science Catalog” as collection title \(these should be entered in your Settings as default repositories.** Note**: this is  a free text field so the title must be exactly the same in order to insure that the metadata is harvested for the LCC Science Catalog.\) |
|  | For data Products that should be shared with Data.gov, Enter “data.gov” and “data.gov” from the picklist as repository and enter “data.gov” followed by your LCC name as the collection title. |
|  | **Best Management Practice**: In Settings, create default repositories to help maintain precise titles |

**In Metadata/Online Resources**

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

### **Associated Tab \(Not Required for Projects\) **

| Notes on Associated Records |
| :--- |
| The Associated section is used to connect items with each other. This feature should be used when items are related. I.E. Products are often the result of projects, and projects often have sub projects. All of these can be linked together by means of association. |
| Add items that are products of projects or related product of another product or vise-versa a product to a project or even a subproject of a project. |
| If this product record is from ScienceBase and it was linked \(as an Associated Item of type "product of"\) to its ScienceBase Project record, then the Associated tab will already be populated correctly as described below, and should be reviewed. |
| If not associated from ScienceBase, you can associate in this section. Make sure that the relevant Project record is loaded into mdEditor \(Import it if not, & return here\). Choose "parentProject" as the Association Type when editing the product entry. Choose “product” as the Association Type when editing the project entry. If entering a sub-project of a project, select “subProject” when editing the subproject entry or “project” when editing the project metadata. Click "Select a Record" \(on the right\), find the Project record, and select it. This will fill in all the needed fields for the current association |
| If entering from scratch, be sure to fill in the Association type as above, as well as an Identifier and Namespace which will uniquely match the referenced Parent, as well as copying the Title and Resource type from the Parent here. It's easier & safer to use the previous method \("Select a Record"\). |

---

### Documents **Tab**

| Notes on Documents |
| :--- |
| Add documents and resources that describe or are related to the project, but are not products of, such as video, webinar, book, poster, webpage, news release, etc. |

---

### Funding **Tab**

See [Record Funding](/record/record-funding.md) for information on entering funding

| Notes |
| :--- |
| Funding is required for projects only. Funding information is not required for products. Funding information is populated from ScienceBase for imported records. |

---

### Contacts **Tab**

See [Contact New](/contact.md) for information on entering contacts.

| Notes/Best Management Practices |
| :--- |
|  |

---



