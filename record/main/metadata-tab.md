# Project Entry Guidance: Metadata Tab

---

Record Metadata allows you to describe your record's metadata, including a description that outlines the process of metadata creation, contributors to the creation of the metadata, and metadata repositories.

| **Quick Reference: Required Metadata Sections** |
| :--- |
| Basic Information \(Required\) |
| Metadata Contacts \(Required\) |
| Metadata Identifier \(Required\) |
| Parent Metadata \(Required\) |
| Identifier \(Required\) |

---

#### **BASIC INFORMATION**

**Metadata Status: **Select the appropriate status of the creation of your metadata from the drop down menu._ For example, If you have added all of your metadata, select "**completed,**" if you still have metadata to add, select "**onGoing**."_

---

#### **METADATA CONTACTS**

**Metadata Contacts **are required and selected from your list of contacts. Adding a metadata contact will give users a contact point should they have any questions about the metadata._ _

* **REQUIRED:** At least one contact with the role of “author” is required. Does not necessarily have to be the LCC \(e.g., imported FGDC metadata can list the original author\)

  * "Author" can be an individual or an organization.

  * You can enter your LCC data manager as the “author”. You do not need to use individual names. You can create a generic data manager for your LCC, but this is up to each LCC.

* **REQUIRED: **Enter the LCC Network Data Steward as a “pointOfContact.”

* **BEST MANAGEMENT PRACTICE:** Enter a “publisher.” In most cases it will be the LCC**.**

---

#### METADATA IDENTIFIER

The **Metadata** **Identifier **is automatically populated by mdEditor. The metadata identifier gives each of your projects and products a unique ID and differentiates them from other similar projects and products.

* If the record was imported from ScienceBase, the Metadata Identifier will be auto-populated with the ScienceBase ID \(SBID\)
* If the record was made in mdEditor, the will generate a universally unique identifier \(UUID\).

---

#### **PARENT METADATA **

The **Parent Metadata **is used to define the folder on ScienceBase where the project or product will be published to. Adding parent metadata lets mdEditor know where the data should go when it is published to ScienceBase. It also lets LCC staff search for other items that may be in the same location in ScienceBase.

> **NOTE:** The Parent Metadata Identifier** **can be added in **mdEditor** **Settings**, or in the **Parent** **Metadata **section of the **Metadata **tab, or both. Adding the identifier to Settings ensures that every item in mdEditor is published to ScienceBase, and it helps to maintain a precise identifier. However, if the identifier is only added in settings, the Parent Metadata Identifier is not written into the mdEditor records. If the records are then shared from ScienceBase, they will not include the ScienceBase Parent Folder Identifier. If the Parent Metadata Identifier is added in the Parent Metadata section of the Metadata tab, the Identifier will be added to the record, insuring that shared records will note where the ScienceBase parent folder resides.

_The following fields are required for Parent Metadata creation:_

* **Title \(**Required\)

* **Identifier Section **\(Required\) Lets you define the location of the parent folder \(the folder where the item will be uploaded to\) in the database repository.

  * **Identifier** \(Required\) is typically a string of numbers in a parent items URL.  A ScienceBase identifier is the section of the URL immediately following "**item/"  **

    > For Example **59b97600e4b091459a54d9f3c ** is the SBID for a parent item at the URL: _"_[https://www.sciencebase.gov/catalog/item/59b97600e4b091459a54d9f3c](https://www.sciencebase.gov/catalog/item/59b97600e4b091459a54d9f3c)_"_

  * **Namespace: **\(Required\) The Namespace field** **allows for the selection of the database that you are adding to. Select **scienceBase **from the Namespace.

---

#### **METADATA REPOSITORIES**

**Metadata Repositories **indicate where the metadata should be sent. Select the "LCCScienceCatalog" as your repository. Selecting LCCScienceCatalog insures that your item will appear in the National LCC Science Catalog.

* For **Projects **that should be listed in the LCC Science Catalog: Select_ “LCCScienceCatalog” from the picklist as repository and “LCC Network Science Catalog_” as the collection title \(these should be entered in your [settings](/settings.md) as default repositories. 

> **BEST MANAGEMENT PRACTICE:** In[ settings](/settings.md), create default repositories to help maintain precise titles

---

![](/assets/metadata_window.png)

> For more information, consult the [**Record Metadata**](https://adiwg.gitbooks.io/mdeditor/content/record/edit/main.html) section of the mdEditor manual.



