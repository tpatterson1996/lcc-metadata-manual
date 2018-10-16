# QA/QC Resources
---
There are several resources are your disposal for QA/QC of metadata. They are listed below with descriptions of what each tool can do.

Quick Links:

1. ScienceBase Scanner: [tool](http://calcommons.info/sb2/scansb.php), [guidance
](https://cookmt.gitbooks.io/mdeditor-for-lccs/content/metadata-improvements/qaqc-fixes/dj-case-qaqc-list.html#sciencebase-scanner)

2. DJ Case QA/QC List: [tool](https://lccnetwork.org/science-catalog/api/item/qaqcIssues), [guidance](https://cookmt.gitbooks.io/mdeditor-for-lccs/content/metadata-improvements/qaqc-fixes/dj-case-qaqc-list.html#dj-case-qaqc-list)

3. Contacts QA/QC List: [tool](https://drive.google.com/open?id=1eUeDjCFpLIiVksmkmzL7-BoBr8ai8rl09FBDIh7Xe3w), [guidance](https://cookmt.gitbooks.io/mdeditor-for-lccs/content/metadata-improvements/qaqc-fixes/dj-case-qaqc-list.html#contacts-qaqc)

---

## ScienceBase Scanner

Link to ScienceBase Scanner:
http://calcommons.info/sb2/scansb.php

---

## DJ Case QA/QC List


To aid in our metadata improvements, DJ Case created an automated QA/QC system of checks. This is a dynamic list of errors that will update when you fix an error and republish your record. Note that the updates will only when the Science Catalog itself updates, which occurs overnight.

Link to QA/QC List from DJ Case:
https://lccnetwork.org/science-catalog/api/item/qaqcIssues


Below are definitions of each issue being described in the list:

### Allocation with unspecified recipient
One or more allocations in the metadata is missing a recipient. This is required.


### Allocation with unspecified source
One or more allocations in the metadata is missing a source. This is required.


### Allocation with recipient with unspecified contactType
One or more allocations in the metadata have a recipient contact that does not have "Contact Type" identified in the contact record. This is required.


### Allocation with source with unspecified contactType
One or more allocations in the metadata have a source contact that does not have "Contact Type" identified in the contact record. This is required.

### Allocation with no fiscal years identified
One or more allocations in the metadata is missing a fiscal year. This is required.

### Allocation has a timePeriod spanning multiple fiscal years
One or more allocations in the metadata includes multiple fiscal years. There should be only a single fiscal year per allocation.

### A responsible party has an invalid role ([valid roles](https://mdtools.adiwg.org/#codes-page?c=iso_role))
Invalid roles are likely leftover from items originally created on ScienceBase and then imported into mdEditor. You may not be able to see the erroneous roles unless you are in "View" mode for the mdEditor record, rather than in "Edit" mode.

### An invalid resource type has been specified ([valid types](https://mdtools.adiwg.org/#codes-page?c=iso_scope))
Invalid resource types are likely leftover from items originally created on ScienceBase and then imported into mdEditor. You may not be able to see the erroneous resource type unless you are in "View" mode for the mdEditor record, rather than in "Edit" mode.

### Duplicate contact name
There are multiple unique Contact IDs in the mdJSON for the same "Contact Name."

### Funding source should be "U.S. Fish and Wildlife Service"
One or more allocations have identified a funding source that should be U.S. Fish and Wildlife Service. For example, the source may specify "Ecological Services" or the name of an LCC rather than "U.S. Fish and Wildlife Service".

---

## Contacts QA/QC 

DJ Case identified a list of errors in the Contacts during the initial creation of the Science Catalog. This is a static list of errors (i.e., it will not update when you fix an issue listed). Please update the "Fixed" column to "yes" when you have addressed a particular item.

Link to Contacts QA/QC List:
https://drive.google.com/open?id=1eUeDjCFpLIiVksmkmzL7-BoBr8ai8rl09FBDIh7Xe3w 





