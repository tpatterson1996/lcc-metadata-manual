# Appendix:

## Overall Science Catalog System Architecture

![](/assets/science_catalog_system_architecture.png)

* Items are imported from a database \(like ScienceBase\), or created directly in mdEditor.
* mdJSON files can also be stored in a local repository and then transmitted via a web service to ScienceBase. Alternately, the  local files can be exported to a web accessible folder and then harvested by ScienceBase.

* The mdTranslator converts the mdJSON files into sbJSON \(the ScienceBase JSON format\), and XML.

* Items are exported from ScienceBase to: Data.gov as XML; the LCC Science Catalog website as Projects and Products; or into mdEditor as mdJSON.

# Fields Required for LCC Projects and Products

Certain fields are required for successful LCC product and project creation. These required fields are listed below.

| PROJECT: Required _**Project**_ Fields | PRODUCT: Required **Product** Fields |
| :--- | :--- |
| [**Main Tab**](/record/main.md) | [**Main Tab**](/record/main.md) |
| Title | Title |
| Status | Status |
| Language | Language |
| Resource Type | Resource Type |
| Point of Contact | Point of Contact |
| [**Main Citation**](/record/main/citation.md) | [**Main Citation**](/record/main/citation.md) |
| Identifier | Identifier |
| Online Resource URI | Online Resource URI |
| **Main Citation Responsible Parties** | **Main Citation Responsible Parties** |
| Point of Contact | Point of Contact |
| **Description** | **Description** |
| Abstract | Abstract |
| **Time Period** | [**Metadata Tab**](/record/metatdata.md) |
| Start | Metadata Contacts |
| End | Metadata Identifier |
| [**Metadata Tab**](/record/metatdata.md) | **Parent Metadata** |
| Metadata Contacts | Title |
| Metadata Identifier | **Identifier** |
| **Parent Metadata** | Identifier |
| Title | Namespace |
| **Identifier** | Metadata Repositories |
| Identifier | [**Keyword Tab**](/record/keywords.md) |
| Namespace | ISO 19115 Topic Category |
| Metadata Repositories | [**Associated Tab**](/record/record-associated.md) |
| [**Keyword Tab**](/record/keywords.md) | Association Type |
| ISO 19115 Topic Category |  |
| LCC Project Category |  |
| Deliverable Types |  |
| [**Extent Tab**](/record/record-extent.md) |  |
| Bounding Box |  |
| [**Funding Tab**](/record/record-funding.md) |  |
| **Allocation** |  |
| Amount |  |
| Currency |  |
| Source |  |
| Recipient |  |
| **Time Period** |  |
| Start Date |  |
| End Date |  |
| Year |  |
| Source |  |
| Amount |  |
| **Matching Funds** |  |
| Year |  |
| Source |  |
| Amount |  |
| Fund Recipient |  |
| Fund Recipient Type |  |
| Fund Recipient Amount |  |
| AwardID |  |



