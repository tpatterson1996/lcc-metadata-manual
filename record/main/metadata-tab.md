# Project Entry Guidance: Record Metadata

---

Record Metadata allows you to describe your record's metadata, including a description that outlines the process of metadata creation, contributors to the creation of the metadata, and metadata repositories.

---

| **Quick Reference: Required Metadata Sections** |
| :--- |
| Basic Information \(Required\) |
| Metadata Contacts \(Required\) |
| Metadata Identifier \(Required\) |
| Parent Metadata \(Required\) |
| Identifier \(Required\) |

#### **BASIC INFORMATION**

* **Metadata Status: **

---

#### **METADATA CONTACTS**

**Metadata Contacts **are required and selected from your list of contacts. Adding a metadata contact will give LCC staff a contact point should they have any questions about the metadata._ _

* **REQUIRED:** At least one contact with the role of “author” is required. Does not necessarily have to be the LCC \(e.g., imported FGDC metadata can list the original author\)

  * "Author" can be an individual or an organization.

  * You can enter your LCC data manager as the “author”. You do not need to use individual names, if you want, you can create a generic data manager for your LCC, but this is up to each individual LCC.

* **REQUIRED: **Enter the LCC Network Data Steward as a “pointOfContact.”

* **BEST MANAGEMENT PRACTICE:** Enter a “publisher.” In most cases it will be the LCC**.**

---

#### METADATA IDENTIFIER

The **Metadata** **Identifier **is automatically populated by mdEditor. The metadata identifier gives each of your projects and products a unique ID and differentiates them from other similar projects and products.

* If the record was imported from Science Base, the Metadata Identifier will be auto-populated with the ScienceBase ID \(SBID\)
* If the record was made in mdEditor, the will generate a universally unique identifier \(UUID\).

---

#### **PARENT METADATA **

The **Parent Metadata **is used to define the folder on ScienceBase where the project or product will be published to. Adding parent metadata lets mdEditor know where the data should go when it is published to ScienceBase. It also lets LCC staff search for other items that may be in the same location in ScienceBase.

_The following fields are required for Parent Metadata creation:_

* **Title \(**Required\)

* **Identifier Section **\(Required\) Lets you define the location of the parent folder \(the folder where the item will be uploaded to\) in the database repository.

  * **Identifier** \(Required\) is typically a string of numbers in a parent items URL.  A ScienceBase identifier is the section of the URL immediately following "**item/"  **

    > For Example **59b97600e4b091459a54d9f3c ** is the SBID for a parent item at the URL: _"_[https://www.sciencebase.gov/catalog/item/59b97600e4b091459a54d9f3c](https://www.sciencebase.gov/catalog/item/59b97600e4b091459a54d9f3c)_"_

  * **Namespace: **\(Required\) The Namespace field** **allows for the selection of the database that you are adding to. Select **ScienceBase **from the Namespace.

---

#### **METADATA REPOSTITORIES**

**Metadata Repositories **indicate where the metadata should be sent. Select the LCCScienceCatalog as your repository. Selecting LCCScienceCatalog insures that your item will appear in the National LCC Science Catalog.

* For **Projects **that should be listed in the LCC Science Catalog: Enter_ “LCCScienceCatalog” from the picklist as repository and “LCC Network Science Catalog_” as collection title \(these should be entered in your Settings as default repositories. **Note:** this is a free-text field, so the title must be exactly the same in order to insure that the metadata is harvested for the LCC Science Catalog.\)

> ![](/assets/best_practice_small.png)In Settings, create default repositories to help maintain precise titles

---

![](/assets/metadata_window.png)

> ![](/assets/see_full_manual_for.png)Consult the [**Record Metadata**](https://adiwg.gitbooks.io/mdeditor/content/record/edit/metadata.html) ** **section of the full mdEditor manual for instructions on adding additional information into the Metadata Tab.



