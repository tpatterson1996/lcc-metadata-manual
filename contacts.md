# Contact Entry Guidance

---

Contacts are individuals or organizations that can be referenced by other contacts, projects, or products. Contacts contain information such as the names of individuals or organization, email address, physical address, website, and phone number so that viewers of metadata can communicate with those affiliated with a metadata record. They also allow LCC staff to know who is responsible for, or participated in: the creation and maintenance of projects and products; funding of projects; and creation and maintenance of metadata.

---

## General Notes on Contacts

In mdEditor, contacts are created separately from individual records and then stored within a library in mdEditor. Once contacts have been entered or imported into mdEditor, they can be used in metadata records. Editing a contact in the mdEditor contact library will update the contact information included in any metadata record that uses that contact. Editing a contact in mdEditor will also update contact information on Science Base once the record is published.

It is recommended that you leave contacts in mdEditor in-between work sessions. This allows you to readily add contacts to projects and products.

It is also recommended that when you export records, you also export your entire contact list. If you do not export your contact list, and you later import a record that contains a contact not in your library, you may receive an error and have to re-enter the contact to that record.

**Once your contacts have been added to mdEditor, there are five places in a metadata record where contacts can/must be added. **

_Please see the corresponding sections for which contacts should be added where. _

1. The "Point of Contact” Section of the [Main Tab](/record/main/record-main-copy.md)
2. The “Responsible Parties” Section in the Citation of the [Main Tab](/record/main/record-main-copy.md)
3. The “Contacts” Section of the [Metadata Tab](/record/main/metadata-tab.md)
4. The “Allocation”  Section of the[ Funding Tab](/record/main/funding-tab.md) for Projects
5. The “Contacts” Section in the [Distribution Tab ](/distribution.md)for Products

---

## Summary of Contact Requirements & Best Practices

### **In Main /Point of Contact**

* Enter your LCC as a “pointOfContact” \(required\).

* Enter the LCC Network Data Steward as a “pointOfContact” \(required\).

* Enter the project PI as “principalInvestigator” \(best practice\).

### **In Main / Citation /Responsible Parties**

* Enter your LCC as “administrator” \(required\).

* Enter the project PI as “principalInvestigator” \(best practice\).

* Can also add funders \(including your LCC\), partners, collaborators, contributors \(best practice\).

### **In Metadata / Contacts**

* At least one contact with the role of “author” is required. Does not necessarily have to be the LCC \(e.g., imported FGDC metadata can list the original author\).

  * Can be an individual or an organization.

  * You can enter your LCC data manager as the “author”. You do not need to use individual names and can create a generic data manager for your LCC, but this is up to the individual LCC.

* Enter the LCC Network Data Steward as a “pointOfContact” \(required\).

* Enter a “publisher.” In most cases, it will be the LCC \(best management practice\).

### **In Funding / Allocation \(for Projects only\)**

* Add the relevant contact for “source” of the project funding \(required\).

  * Should be an organization, not an individual. For LCC projects, the most common sources are U.S. Fish and Wildlife Service, Bureau of Land Management, and Bureau of Reclamation.

* Add the relevant contact for “recipient” of the project funding \(required\).

  * Should be an organization, not an individual.

### **In Distribution \(for Products only\)**

* Add the relevant contact for “distributor” of the product \(if you fill out anything in the Distribution section, a contact for Distributor is required\).

---

## Best Practices for Contacts

* Always spell out acronyms and organization names.
* Copying contacts will change the ID and the name \(the name will be “Copy of ….”\) but all the other information will be the same.
* Make sure your contacts are loaded and accurate in mdEditor before beginning to create your metadata records. 
* Code lists, including the contact type options/dropdown list, are maintained by ADIwg.

---

## Importing Contacts

When you import a ScienceBase record for the first time,  mdTranslator will automatically load all sbJSON contacts into Main/Citation/Responsible Parties. However, this MUST be reviewed to check for errors and inconsistencies introduced during translation. Delete any duplicate or extraneous contacts or errors from this section. Ensure you meet requirements, follow BMPs, and you can include other contacts as desired.

