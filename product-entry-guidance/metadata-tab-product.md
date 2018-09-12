# Product Entry Guidance: Metadata Tab

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

**Metadata Status: **Select the appropriate status of the creation of your metadata from the drop-down menu._ For example, if you have added all of your metadata, select "**completed**." If you still have metadata to add, select "**onGoing**."_

---

## **Metadata Contacts**

**Metadata Contacts **are required and selected from your list of contacts. Adding a metadata contact will give LCC staff a contact point should they have any questions about the metadata._ _

* **Required:** At least one contact with the role of “author” is required. Does not necessarily have to be the LCC \(e.g., imported FGDC metadata can list the original author\)

  * "Author" can be an individual or an organization.

  * You can enter your LCC data manager as the “author”. You do not need to use individual names, if you want, you can create a generic data manager for your LCC, but this is up to each individual LCC.

* **Required: **Enter the LCC Network Data Steward as a “pointOfContact.”

* **Best Practice:** Enter a “publisher.” In most cases, it will be the LCC.

---

## Metadata Identifier

The **Metadata** **Identifier **is automatically populated by mdEditor. The metadata identifier gives each of your projects and products a unique ID and differentiates them from other similar projects and products.

* If the record was imported from Science Base, the Metadata Identifier will be auto-populated with the ScienceBase ID (SBID)
* If the record was made in mdEditor, the will generate a universally unique identifier (UUID).

---

## **Parent Metadata **

The **Parent Metadata **is used to define the folder on ScienceBase where the project or product will be published to. Adding parent metadata lets mdEditor know where the data should go when it is published to ScienceBase. 

_The following fields are required for Parent Metadata creation:_

* **Title \(**Required\)

* **Identifier Section **\(Required\) Lets you define the location of the parent folder \(the folder where the item will be uploaded to\) in the database repository.

  * **Identifier** \(Required\) is typically a string of numbers in a parent items URL.  
   {% hint style='info' %}A ScienceBase identifier is the section of the URL immediately following "**item/"**. For example, **59b97600e4b091459a54d9f3c** is the SBID for a parent item at the URL: [https://www.sciencebase.gov/catalog/item/59b97600e4b091459a54d9f3c](https://www.sciencebase.gov/catalog/item/59b97600e4b091459a54d9f3c){% endhint %}

  * **Namespace: **\(Required\) The Namespace field** **allows for the selection of the database that you are adding to. Select **scienceBase **from the Namespace.

---

## **Metadata Repositories**

**Metadata Repositories **indicate where the metadata should be sent. Select the "LCCScienceCatalog" as your repository. Selecting LCCScienceCatalog insures that your item will appear in the National LCC Science Catalog.

* For **Products **that should be listed in the LCC Science Catalog: Select_ “LCCScienceCatalog” from the picklist as repository and “LCC Network Science Catalog_” as collection title \(these should be entered in your [settings](/settings.md) as default repositories. Additionally, adding the record in the Metadata Repositories section of the Metadata tab insures that the repository is written to your record.

{% hint style='danger' %} The Metadata Repository and Collection Title must be exactly the same for each of your LCC's records with no variations in spelling, spaces, capitalization, etc. Specifying this information in Settings is the best way to ensure the repository information will be consistent across all of your records. It strongly recommended that you do not type these in by hand on individual metadata records.{% endhint %}

---

![](/assets/metadata_window.png)

> For more information, consult the [**Record Metadata**](https://adiwg.gitbooks.io/mdeditor/content/record/edit/metadata.html) section of the mdEditor manual.



