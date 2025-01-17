# QA/QC Fixes

## Must Do QA/QC Fixes

### Main

\(1\) Products need to have a specific resource type selected \(not “product”\) AND they need to be valid resource types. See [QA/QC list from DJ Case](https://lccnetwork.org/science-catalog/api/item/qaqcIssues).

### Main/Citation

\(2\) Responsible Parties need to have a valid role selected. See [QA/QC list from DJ Case](https://lccnetwork.org/science-catalog/api/item/qaqcIssues).

### Metadata Repositories

\(3a\) Ensure you have a single version of your data.gov tag and it is consistent across all of your items. See [ScienceBase scanner](http://calcommons.info/sb2/scansb.php).

\(3b\) If you update your Metadata Repositories in mdJSON and publish to ScienceBase, you will also need to delete the erroneous version from ScienceBase \(called Harvest Sets in SB\). The issue is that SB doesn’t remove tags when an item is republished, it just adds to tags. This issue applies to all keywords, but it is most important to fix for Harvest Sets. This scenario can happen with both erroneous data.gov tags or misspelled Harvest Set tagging.

You may want to consider using the injector script to delete or replace erroneous versions from mdJSON. You would still be required required to manually remove the erroneous versions from SB items.

### Funding

\(4\) LCC allocations need to list the funding agency as the source \(e.g., U.S. Fish and Wildlife Service\), not the LCC. See [QA/QC list from DJ Case](https://lccnetwork.org/science-catalog/api/item/qaqcIssues).

* Additionally, all funding from other FWS programs need to list FWS as the source \(and not list the source as Fisheries, specific Refuges, ES, etc.\). Clarifications on the exact program or refuge where the funding came from can be done through the Funding/Other Contacts field \(and choose the role of "administrator"\).

\(5\) All allocations should list the fiscal year when the funds were allocated \(this is different than a project's overall start and end dates - those are entered in Main/Time Period\). There should be only a single fiscal year identified per allocation. Use the “Pick a Fiscal Year” dropdown to autofill the date fields.

![](https://lh4.googleusercontent.com/HhhIrQf8mZVYMVYCcBX2KtZcRZCDYN20n2gPTDvnm_NBEkeHUc2J9VLiXuIObjSAuXkPbB3Vx-b9CJsKyvxKhZtFJqBQzMLY1GsVAJSSMhhBwMOmDP1zZZxqe2F-caBONgQJEm-o)

\(6\) All allocation recipients should be an Organization, not an Individual contact. Clarifications, although not required, can be done through the Funding/Other Contacts field \(e.g., list a "principalInvestigator"\).

### Contacts

\(7\) All contacts need the appropriate contactType identified—this is particularly important for funding summaries. See [QA/QC list from DJ Case](https://lccnetwork.org/science-catalog/api/item/qaqcIssues).

\(8\) Address the [Contact QA/QC list from DJ Case](https://drive.google.com/open?id=1eUeDjCFpLIiVksmkmzL7-BoBr8ai8rl09FBDIh7Xe3w).

* Note: this is a static list that was generated during the initial creation of the Science Catalog. The spreadsheet will not update when you fix an issue listed. Please update the "Fixed" column to "yes" when you have addressed a particular item.

### Keywords

\(9\) Fix “consevation design” Typo. Select correct option in mdEditor and re-publish. Affected records can be viewed [here](https://lccnetwork.org/catalog#/eJxlT7GOwjAM/ZXIqlSQEOLWbohbEAMDI2LwJaayzjglCQWu6r9fgjpwus3vPfs9vwFaUgoo0AzwTc+7Dy6WWXzLFmXfZTH5AA2gOliADZwoMEJzHKBHuVGWNl4j9ZjYq3EUuVUYT+O4gMp6TcG/3Kue6Z6XE34JZaeqw5YO/JMNPlarCW/V0QOaAqMP6ZMD2WJb8qOFiV5nri/BkS+d8JnJLcVaKIlnlvzgH80oGb2JmFzBzN5uUGQ3dTZ0NfX/HvUcxl+N0GTK) \(this is a link to a saved Science Catalog search for the erroneous keyword\).

### Distribution

\(10\) Distribution links need to be included for products. This was already required for all products and this is particularly critical for items sent to data.gov. This is the only online resource data.gov reads so without a URL here, there is no way for a user to access the actual product. The recommended role is "distributor" \(see the [Product Distribution](../../product-entry-guidance/distribution.md) section for more info\).

Note: Matt Heller is looking into a solution \(mid-November\) using the injector script so data managers could run this automated process themselves to meet minimum requirements.

### Fixing Errors

\(11\) Republish any records that don’t have mdJSON attached \(without mdJSON, the item will not show up in the Science Catalog\). See [ScienceBase scanner](http://calcommons.info/sb2/scansb.php).

\(12\) Go through errors/warnings in the [ScienceBase scanner](http://calcommons.info/sb2/scansb.php) \(e.g., no ISO Keyword, bad repo tag, etc.\) .

\(13\) Address remaining [QA/QC issues from DJ Case](https://lccnetwork.org/science-catalog/api/item/qaqcIssues).

\(14\) Fix the errors identified by the ASG in manual QA/QC checks of the Science Catalog. [See list](https://docs.google.com/spreadsheets/d/1eUeDjCFpLIiVksmkmzL7-BoBr8ai8rl09FBDIh7Xe3w/edit#gid=117396702).

\(15\) Template scripting introduced some errors for some LCCs. Fixing these may be most effective with the injector script. Specific details related to these issues will be discussed with those who used the template scripting.

