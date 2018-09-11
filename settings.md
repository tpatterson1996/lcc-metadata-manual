# Settings \(![](/assets/symbol_cog_16.png)\)

---

The settings menu allows for the configuring of user-specific options. Settings must be configured before you create LCC metadata.

---

## General Settings

**mdEditor Version**: The mdEditor version notes the current version of mdEditor. Use this when reporting errors. Errors can be reported at [https://github.com/adiwg/mdEditor/issues](https://github.com/adiwg/mdEditor/issues). You must have a github account in order to post.

**Auto-Save**: The Auto-Save option will write all changes to local storage when you exit a data entry field. Changes must be manually saved if the Auto-Save feature is turned off.

{% hint style='info' %}
Auto-Save allows you to save less frequently, but it makes it harder to undo changes that you make to your records. If you stay on the same record, you can cancel changes. But once you leave the record, the record is saved and you can’t cancel the change except by manually re-editing the record.
{% endhint %}

**Clear All Records: **All records can be cleared by clicking the "Clear Storage Cache."

{% hint style='danger' %}
**Warning**: Clearing all records will delete all of the records currently loaded in mdEditor. Before doing so, use the Export function to make a backup of your records. Otherwise, the records will be permanently lost (unless you previously made a backup copy).
{% endhint %}

---

## LCC Specific Settings

_These must be implemented before you begin creating metadata records._

**Metadata Repositories**: In the Default Section, add two metadata repositories.

1. Select **LCCScienceCatalog** from the Repository drop-down menu. Enter “LCC Network Science Catalog” as the collection title.
2. Select **data.gov** from the Repository drop-down menu. For the collection title, enter "data.gov" followed by the LCC name without acronyms. For example "data.gov Great Northern Landscape Conservation Cooperative".

{% hint style='info' %}
The metadata repository information must be exactly the same for each record with no variations in spelling, spaces, capitalization, etc. Specifying this information in Settings is the best way to ensure the repository information will be consistent across records. It is strongly recommended that you do not type these in by hand on individual metadata records.
{% endhint %}

**Parent Identifier**: Under publishing, enter the ScienceBase identifier for your LCC's ScienceBase project folder in the "Default Parent Identifier" field.



---

## Defaults

**Defaults **include settings for **Language**, **Character Set**, **Country**, and the **Import URL **\(used for defining the default URL for importing\). To set the default import URL for importing items from ScienceBase, enter [https://api.sciencebase.gov/sbmd-service/mdjson/](https://api.sciencebase.gov/sbmd-service/mdjson/).

![](/assets/settings_defaults.png)

The following defaults will be pre-loaded:

* default language: English
* default character set: UTF-8
* default location: USA

Also included in **Defaults** are the **Metadata Repositories** (an online database for storing metadata\). Once entered in **Settings** these can then be selected for projects and products so that they are flagged to a metadata repository of your choice. In the Default Selection of the Settings, click "Add Metadata Repository." For LCC metadata records, select **LCCScienceCatalog **from the Repository drop-down menu. If you wish to also add your items to data.gov, once again click "Add Metadata Repository" and select **data.gov** from the repository drop-down menu.

---

## Publishing Settings

Items can be published to an online repository such as ScienceBase.

In the **Default Parent Identifier**, enter the repository's parent ID. You may also enter the **Default Community** and **Default Organization**.

For LCC Metadata enter your LCC's ScienceBase project folder's identifier in the "Default Parent Identifier" field.

![](/assets/publishing_settings.png)

