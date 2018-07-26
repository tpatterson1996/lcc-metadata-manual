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

## **Basic Information**

**Metadata Status: **Select the appropriate status of the creation of your metadata from the drop down menu._ For example, If you have added all of your metadata, select "completed," if you still have metadata to add, select "onGoing."_

**Dates**: Add at least one date. Recommended are "creation" \(when you first create your metadata\) and "lastUpdate" \(when you update metadata after initial publication\).

---

## **Metadata Contacts**

**Metadata Contacts **are required. Adding a metadata contact will give users a contact point should they have any questions about the metadata._ _

* **REQUIRED:** At least one contact with the role of “author” is required. This does not necessarily have to be the LCC \(e.g., imported FGDC metadata can list the original author\).

  * "Author" can be an individual or an organization.

  * You can enter your LCC data manager as the “author”. If you prefer, you can use a generic data manager contact rather than an individual name. 

* **REQUIRED: **Enter the LCC Network Data Steward as a “pointOfContact.”

* **BEST MANAGEMENT PRACTICE:** Enter a “publisher.” In most cases it will be the LCC**.**

---

## Metadata Identifier

The **Metadata** **Identifier **is automatically populated by mdEditor. The metadata identifier gives each of your projects and products a unique ID and differentiates them from other similar projects and products.

* If the record was imported from ScienceBase, the Metadata Identifier will be auto-populated with the ScienceBase ID \(SBID\).
* If the record was created in mdEditor, it will generate a universally unique identifier \(UUID\).

---

## **Parent Metadata **

The **Parent Metadata **is used to define the folder on ScienceBase where the project or product will be published to. Adding parent metadata lets mdEditor know where the metadata should go when it is published to ScienceBase. 

> **NOTE:** The Parent Metadata Identifier** **can be added in **mdEditor** **Settings**, or in the **Parent** **Metadata **section of the **Metadata **tab, or both. Adding the identifier to Settings ensures that every item in mdEditor is published to ScienceBase, and it helps to maintain a precise identifier. However, if the identifier is only added in settings, the Parent Metadata Identifier is not written into the mdEditor records. If the records are then shared from ScienceBase, they will not include the ScienceBase Parent Folder Identifier. If the Parent Metadata Identifier is added in the Parent Metadata section of the Metadata tab, the Identifier will be added to the record, ensuring that shared records will note where the ScienceBase parent folder resides.

_The following fields are required for Parent Metadata creation:_

* **Title \(**Required\)

* **Identifier Section **\(Required\) Lets you define the location of the parent folder \(the folder where the item will be uploaded to\) in the database repository.

  * **Identifier** \(Required\) is typically a string of numbers in a parent items URL.  A ScienceBase identifier is the section of the URL immediately following "**item/"  **

    > For Example **59b97600e4b091459a54d9f3c ** is the SBID for a parent item at the URL: _"_[https://www.sciencebase.gov/catalog/item/59b97600e4b091459a54d9f3c](https://www.sciencebase.gov/catalog/item/59b97600e4b091459a54d9f3c)_"_

  * **Namespace: **\(Required\) The Namespace specifies your selected database. Select **scienceBase **from the Namespace.

---

## **Metadata Repositories**

**Metadata Repositories **indicate where the metadata should be sent.

* For **Projects **that should be listed in the LCC Science Catalog: Select _“LCCScienceCatalog”_ from the repository list. _“LCC Network Science Catalog”_ should automatically show up as the collection title if you have entered the default metadata repository information in [settings](/settings.md). Items without this tag and collection title will not be displayed in the Science Catalog.

> **BEST MANAGEMENT PRACTICE:** In[ settings](/settings.md), create default repositories to maintain exact titles.
>
> Note: The Metadata Repository and Collection Title must be exactly the same for each record with no variations in spelling, spaces, capitalization, etc. Specifying the information in Settings is the best way to ensure the repository information will be consistent across records. It highly recommended that you do not type these in by hand on individual metadata records.

---

![](/assets/metadata_window.png)

> For more information, consult the [**Record Metadata**](https://adiwg.gitbooks.io/mdeditor/content/record/edit/main.html) section of the mdEditor manual.



