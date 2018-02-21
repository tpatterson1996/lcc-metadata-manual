## Adding PROJECTS: Quick Reference

---

This page will provide a brief overview of required fields for a metadata Project record, for more in-depth information, rationale and instructions, please see the relevant section in [Records](/records.md).

---

### Overview of Required/Recommended Fields for Projects:

To_ see the fields described in this Quick Reference, select the green edit button next to an existing record in the left vertical menu, or _[_create a new record_](/record-new.md)_._

### **Main Tab**

##### **In Main/Basic Information, Resource Type, Point of Contacts**

See [Record Main](/record/main.md) for more information

| **Field** | **Instructions/Notes on Entering** |
| :--- | :--- |
| Record ID \(Required\) | The Record ID will be generated automatically. |
| Title \(Required\) | Enter a title. **Best Management Practice \(BMP\): **Since products and projects are independent records, we recommend having as informative a title as possible. Good titles, when they appear in a search, will be understood and/or traceable. |
| Status \(Required\) | Choose status ONLY from the four following options: Completed, On Going, Proposed, or Accepted. |
| Default Locale \(Required\) | Language should be set to _**English**,_ Character set to_ **UTF-**_**8,** Country set to_ **USA. **_ |
| Resource Type \(Required\) | Select "Project" from the picklist. |
| Point of Contact \(Required\) | From the Role drop-down menu, select **pointOfContact**. From the Contacts drop-down menu, select a **contact** from the list of contacts. |
|  | **Best Management Practice: **Enter \(1\) your** LCC **and \(2\) **the LCC Network Data Steward** as "pointOfContacts." This way there is a point of contact that users can reach even if there is a positional change in an organization |
|  | **Best Management Practice:** Enter the Project PI as a "principalInvestigator" |

**In Main/Citation**

See [Main Citation ](/record/main/citation.md)for more information

| Field | Instructions/Notes On Entering |
| :--- | :--- |
| Title \(Auto-Generated\) | Added automatically, based on the title of your record. |
| Alternate Title \(Optional\) | Enter a shorter title |
| Dates \(Optional\) | Enter _acquisition, creation, revision,_ or another date reference from the pick-list and then enter the date |
| Responsible Parties \(Required\) | This must include a point of contact, but may also include other responsible parties such as a project lead. |
|  | Enter the Network Data Steward as "pointOfContact" \(See [Contacts\)](/contacts.md) |
|  | **Best Management Practice:** Add your LCC, and the project PI. Enter your LCC as "administrator" and the Project PI as "principalInvestigator." |
|  | You can also add funders \(including your LCC, Partners, Collaborators, and/or Contributors\) |
| Online Resources** **\(Required, If Available\) | Enter the URL for the project homepage on your LCC website |
| Identifier \(Required\) | **Best Management Practice:** Enter ScienceBase ID \(SBID\), if known. mdEditor can use the SBID to locate and publish the metadata to the correct item in ScienceBase. |
|  | \(Recommended, if available\) Enter Digital Object Identifier, if available |
|  | \(Recommended, if available\) Enter any internal project ID, up to 32 characters |
|  | \(Optional\) Enter funding identifier, if desired |

**In Main/Description**

See [Record Main ](/record/main.md)for more information

| Field | Instructions/Notes On Entering |
| :--- | :--- |
| Abstract \(Required\) | **Best Management Practice**: Write your abstracts for projects in the present tense if the project is underway, and past tense if it has been completed. |
| Short Abstract \(Optional\) | Enter a short description of the project, if desired |
| Supplemental Information \(Optional\) | Enter comments, if desired |

**In Main/Time Period**

See [Record Main ](/record/main.md)for more information

| Field | Instructions/Notes On Entering |
| :--- | :--- |
| Date \(Required\) | Time Period refers to project start and end date, or the date that the project was applicable \(time that the project was funded to date of completion\). |
|  | For each project, add a start, end date, and fiscal year. |

---

### Metadata TAB

**In Metadata/Basic Information**

See [Record Metadata ](/record/metatdata.md)for more information

| Field | Instructions/Notes on Entering |
| :--- | :--- |
| Metadata Status \(Required\) | Choose Status from Metadata Pick-list |
| Date \(Required\) | Enter a date for "creation" or "last updated" |

**In Metadata/Contacts**

See [Record Metadata ](/record/metatdata.md)for more information

| Field | Instructions/Notes on Entering |
| :--- | :--- |
| Point Of Contact \(Required\) | Enter the LCC Network Data Steward as a “pointOfContact” \(see [Contacts\) ](/contacts.md)for contact information. |
| Author \(Optional\) | Enter your LCC data manager as the “author.” You do not need to use individual names and can create a generic data manager for your LCC, but this is up to the individual LCC. |
| Publisher \(Recommended\) | **Best Management Practice**: Enter your LCC as the "publisher" |

**In Metadata/Identifier & Parent Metadata**

See [Record Metadata ](/record/metatdata.md)for more information

| Field | Instructions/Notes on Entering |
| :--- | :--- |
| Identifier \(Required\) | If the record was imported from ScienceBase, this field is auto-populated with the Universally Unique Identifier \(UUID\). |
|  | If the record was created new in mdEditor, mdEditor creates the metadata identifier \(UUID\). It is recommended that you do not change this identifier. |
| Parent Metadata \(Required\) | Parent Metadata** **is used to define the folder on ScienceBase where the project or product will be published to. Items added to the parent folder are considered children \(or child items\) of that folder. |
|  | **Enter the ScienceBase ID \(SBID\) of the parent item**--if the record was imported from ScienceBase, this field is auto populated. If the record was created new in mdEditor \(and has a corresponding parent item in ScienceBase\), the identification information should be put here. Double check that these values are correct; If this record is created new in mdEditor and does not exist in ScienceBase, populate the parent metadata with the parent SBID, if present in ScienceBase. Recommended workflow is 1\) complete project metadata, 2\) complete child product metadata and associate the items. In this way, parent-child relationships can be defined. \(See [Parent Metadata ](/record/metatdata/parent-metadata.md)for more information\) |
|  | **Note:** If items are moved in ScienceBase, and the parent metadata is not changed in mdEditor, when mdEditor publishes to ScienceBase, the parent-child relationships in ScienceBase will be overwritten. |

**In Metadata/Repositories**

See [Record Metadata ](/record/metatdata.md)for more information

| Field | Instructions/Notes on Entering |
| :--- | :--- |
| Repository \(Required\) | For Projects that should be listed in the LCC Science Catalog, Enter “LCCScienceCatalog” from the picklist as repository and “LCC Network Science Catalog” as collection title \(these should be entered in your Settings as default repositories.** Note**: this is  a free-text field, so the title must be exactly the same in order to insure that the metadata is harvested for the LCC Science Catalog.\) |
|  | For data Products that should be shared with Data.gov, Enter “data.gov” and “data.gov” from the picklist as repository and enter “data.gov” followed by your LCC name as the collection title. **Note**: this is a free-text field, so the repository title must be exactly the same for every metadata record to insure proper harvesting of metadata |
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
| GCMD Science Keywords | Choose from picklist and include full path. | GCMD \(Global Change Master Directory keywords\) are built and maintained by NASA. GCMD keywords are listed by category. It is recommended that you click Full Path when editing these keywords to maintain their category. |
| ISO Topic Category Thesaurus | Choose from picklist. | \(International Organization for Standardization\) topics were built and maintained by the ISO Technical Committee and are required for the development of ISO metadata. It's recommended that you use at least one of these keywords so metadata remains ISO compliant. |
| LCC Project Category Keywords | Choose from picklist. | LCC \(Landscape Conservation Cooperatives\) Keywords are maintained by the national LCCs and required for any LCC metadata. |
| LCC Deliverable Type Thesaurus | Choose from picklist. |  |
| LCC End User Type Thesaurus | Choose from picklist. |  |
| Custom Thesaurus | Title thesaurus as EndUsers, | Enter end user keywords that do not appear in the usertype keywords |

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

### **Associated Tab **

| Notes on Associated Records |
| :--- |
| The Associated section is used to connect items with each other. This feature should be used when items are related. I.E. Products are often the result of projects, and projects often have sub-projects. All of these can be linked together by means of association. |
| If the product record is from ScienceBase and it was linked \(as an Associated Item of type "product of"\) to its ScienceBase Project record, then the Associated tab will already should be populated correctly, but should be reviewed for accuracy. |
| If not associated from ScienceBase, you can associate in this section. Make sure that the relevant Product record is loaded into mdEditor. Choose “product” as the Association Type. If entering a sub-project of a project, select “subProject”. Click "Select a Record" \(on the right\), find the product record, and select it. This will fill in all the needed fields for the current association |

---

### Funding **Tab**

See [Record Funding](/record/record-funding.md) for information on entering funding

| Notes |
| :--- |
| Funding information is populated from ScienceBase for imported records. |
| **Allocation \(**Required\): Describes how the funds were allocated. Adding allocation allows LCC staff to see where funding came from and how it was distributed. It also lets staff find your items when searching for specific funders. |
| **Time Period \(**Required\): Describes the time period during the allocation of funds. Adding a time period lets LCC staff know when your items were funded, and lets them find your item when searching for items funded in a similar time period. |
| Funding is required for Projects only |

---

### Contacts **Tab**

See [Contact New](/contact.md) for information on entering contacts.

| Individual Contact | Organizational Contact |
| :--- | :--- |
| **Individual Name **\(Required\) | **Organization Name **\(Required\): The organization's full name. |
| **Position Name **\(Required\) | **Email Address **\(Required\): Add an email address of the primary contact in the organization. _Best Practice:_ If you do not have a contact point for the organization, you can use the LCC Data Steward email address: lccdatasteward@fws.gov |
| **Email Address** \(Required\) | **Online Resource** \(Required\): Add a web URL where your organization resides. |

| Adding Contacts: General Notes | Adding Contacts: Best Practice |
| :--- | :--- |
| All LCC records **require at least one contact **to serve as a point of contact for projects and products. | Always spell out acronyms and organization names |
| One contact must be LCC Network Data Steward. The LCC data steward will serve as the long term contact/backup if LCC staff are not available. The LCC Network Data Steward's contact information is as follows:** Individual Name:** L_CC Network Data Steward **Position Name:** LCC Network Data Manager **Contact Type:** lcc **E-mail Addresses**: lccdatasteward@fws.gov_ |  |
| You must create an organization contact for your LCC and any organization that is involved in your project or product \(partner, co-funder, etc.\) if there is not one already. |  |



