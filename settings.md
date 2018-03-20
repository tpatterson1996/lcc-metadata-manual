# Settings \(![](/assets/symbol_cog_16.png)\)

---

The settings menu allows for the configuring of user-specific options. Settings must be configured before you create LCC metadata. 

---

### LCC Specific Settings

_These must be implemented before you begin creating metadata records. Adding these in settings insures that your items are added to the correct repository and published correctly._

* **Metadata Repositories**: In the Default Selection of the Settings, click "Add Metadata Repository." Select **LCCScienceCatalog **from the Repository drop-down menu. If you wish to also add your items to data.gov, once again click "Add Metadata Repository" and select **data.gov **from the repository drop-down menu.
* **Parent Identifier: **In the publishing settings, enter your LCC's ScienceBase project folder's identifier in the "Default Parent Identifier" field.

---

### General Settings

* **mdEditor Version:** The mdEditor version notes the current version of mdEditor. Use this when reporting errors. Errors can be reported at [https://github.com/adiwg/mdEditor/issues](https://github.com/adiwg/mdEditor/issues). You must have a github account in order to post.
* **Auto-Save**: The Auto-Save option will write all changes to local storage when you exit a data entry field. Changes must be manually saved if the Auto-Save feature is turned off. 
  > **NOTE:** Auto-Save allows the user to save less frequently, but it makes it harder to undo changes that you make to your records. If you stay on the same record, you can cancel changes. But once you leave the record, the record is saved and you can’t cancel the change except by manually reediting the record.

* **Clear All Records: **All records can be cleared by clicking the "Clear Storage Cache."

> ![](/assets/caution.png)** **_**CAUTION! Clearing all records will delete your current set of records.**_** If you wish to retain your records for future use, be sure and make a backup with the **[**export**](/export.md)** function before clearing the cache.  **



---

### Defaults

**Defaults **include settings for **Language**, **Character Set**, **Country**, and the **Import URL \(**used for defining the default URL for importing\). To Set the default import URL for importing items from ScienceBase, enter [https://api.sciencebase.gov/sbmd-service/mdjson/](https://api.sciencebase.gov/sbmd-service/mdjson/).

![](/assets/settings_defaults.png)

The following defaults will be pre-loaded:

* default language: English
* default character set: UTF-8
* default location: USA

Also included in **Defaults** are the **Metadata Repositories **\(a server where the metadata is published to\)**. **Once entered in **Settings **these can then be selected for projects and products so that they are flagged to a metadata repository of your choice. In the Default Selection of the Settings, click "Add Metadata Repository." For LCC metadata records, select **LCCScienceCatalog **from the Repository drop-down menu. If you wish to also add your items to data.gov, once again click "Add Metadata Repository" and select **data.gov **from the repository drop-down menu.

---

### Publishing Settings

Items can be published to an online repository such as ScienceBase.

In the **Default Parent Identifier**, enter the repository's parent ID. You may also enter the **Default Community **and **Default Organization**. 

For LCC Metadata enter your LCC's ScienceBase project folder's identifier in the "Default Parent Identifier" field.

 



![](/assets/publishing_settings.png)

