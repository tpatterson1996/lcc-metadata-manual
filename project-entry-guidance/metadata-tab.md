# Metadata Tab: Project

The Metadata tab describes your project's metadata, including a description that outlines the process of metadata creation, contributors to the creation of the metadata, and metadata repositories.

| Quick Reference: Project Metadata Tab | Required? |
| :--- | :--- |
| Basic Information: Metadata Status, Dates | Best Practice |
| Metadata Contacts | Required |
| Metadata Identifier | Required |
| Parent Metadata | Required |
| Metadata Repositories | Required |

## Basic Information

### Metadata Status \(Best Practice\)

Select the appropriate status of the creation of your metadata from the drop down menu. _For example, if you have added all of your metadata, select "completed." If you still have metadata to add, select "onGoing."_

### Dates \(Best Practice\)

Add at least one date. Recommended are "creation" \(when you first created your metadata\) and "lastUpdate" \(when you updated metadata after initial publication\).

## Metadata Contacts

**Metadata Contacts** are required. Adding a metadata contact will give users a contact point should they have any questions about the metadata. __

| Role | Contact | Required? |
| :--- | :--- | :--- |
| author | See notes below | At least one is required |
| publisher | In most cases, this will be the LCC | Best Practice |
| pointOfContact | LCC Network Data Steward | Required |

**Regarding Role of "author"**

* The author does not necessarily have to be the LCC \(e.g., imported FGDC metadata can list the original author\).
* "Author" can be an individual or an organization.
* You can enter your LCC data manager as the “author”. If you prefer, you can use a generic data manager contact rather than an individual name.

## Metadata Identifier

The **Metadata Identifier** is automatically populated by mdEditor. The metadata identifier gives each of your projects and products a unique ID and differentiates them from other similar projects and products.

* If the record was imported from ScienceBase, the Metadata Identifier will be auto-populated with the ScienceBase ID \(SBID\).
* If the record was created in mdEditor, it will generate a universally unique identifier \(UUID\).

{% hint style="danger" %}
Once a Metadata Identifier is created in the metadata, do not change it. mdEditor uses the Metadata Identifier to connect records and changing the Metadata Identifier can break those connections. If there are additional identifiers you want to include in your metadata record, include them in [Main/Citation/Identifier](record-main-copy.md#identifier).
{% endhint %}

## Parent Metadata

**Parent Metadata** defines the ScienceBase folder in which the project will be published. The parent metadata tells mdEditor where the project metadata should go when it is published to ScienceBase.

If you imported the project metadata from ScienceBase originally, this section will be populated already.

If you created the project metadata from scratch in mdEditor, this will be blank. If you provide a default parent ID in [Settings](../settings.md#publishing-settings) \(Publishing Settings for ScienceBase\), this will be generated for you when when you publish. This is most likely your LCC's project folder. You can enter the parent item SBID directly in your individual metadata record if you wish.

### Parent Metadata Required Fields:

#### Title \(Required\)

If this is not already populated, you can enter something like "Parent folder."

#### Identifier \(Required\)

Defines the location of the parent folder in ScienceBase.

| Identifier | Namespace |
| :--- | :--- |
| ScienceBase identifier for the parent item | scienceBase |

{% hint style="info" %}
The ScienceBase identifier is the alphanumeric string in the item's URL immediately following "**item/".** For example, **59b97600e4b091459a54d9f3c** is the SBID for the item at the URL: [https://www.sciencebase.gov/catalog/item/59b97600e4b091459a54d9f3c](https://www.sciencebase.gov/catalog/item/59b97600e4b091459a54d9f3c)
{% endhint %}

## Metadata Repositories

**Metadata Repositories** indicate where the metadata will be sent upon publishing.

### LCC Science Catalog

For projects that should be listed in the LCC Science Catalog: Select _“LCCScienceCatalog”_ from the repository list. _“LCC Network Science Catalog”_ should automatically show up as the collection title. If the collection title does not appear, stop and enter the correct information in [Settings](../settings.md). Then select the repository for your project. Projects without the correct tag and collection title will not show up in the Science Catalog.

{% hint style="danger" %}
The Metadata Repository and Collection Title must be exactly the same for each of your LCC's records with no variations in spelling, spaces, capitalization, etc. Specifying this information in Settings is the best way to ensure the repository information will be consistent across all of your records. It strongly recommended that you do not type these in by hand on individual metadata records.
{% endhint %}

{% hint style="info" %}
You should only use the data.gov repository for products \(projects are not sent to data.gov\).
{% endhint %}

![](../.gitbook/assets/project_metadata.png)

