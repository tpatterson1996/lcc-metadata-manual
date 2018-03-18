# Publish

---

Users can publish records to an online platform. The current option is ScienceBase, a collaborative data cataloging and data management platform developed by the United States Geological Survey. It provides a centralized, searchable, and publicly-available repository for data. You must have a ScienceBase user account with publishing rights in order to publish to ScienceBase. Publishing adds your items to ScienceBase database as well as the National Science Catalogue.

### ![](/assets/publish_screenshot_overview.png)

### Before You Begin

Please read through ALL instructions before you begin the publishing process. After you understand how the publishing function works, please read the[** testing instructions**](/publish/instructions-for-testing-publishing.md) and proceed with testing a record before you try to publish any of your real records.

---

## Overall Science Catalog System Architecture

Currently the mdEditor is used primarily with ScienceBase, a collaborative scientific data and information management platform developed and run by the USGS and used directly by science teams. The mdEditor can work with other databases, but in this manual, ScienceBase will be used as the primary example of a database. For more information, see ScienceBase in the glossary of terms.

The following describes the process of publishing from mdEditor

1. mdEditor outputs an mdJSON file.
2. The mdJSON file is transmitted via a webservice to mdTranslator.
3. mdTranslator translates the mdJSON file into sbJSON and XML.
4. ScienceBase imports the sbJSON and XML.
5. Depending on the default repository that you defined in settings, the records are outout from ScienceBase to DATA.GOV, the LCC Science Catalog Website, or both.

_The following diagram describes the overall science catalog system architecture._

![](/assets/science_catalog_system_architecture.png)

