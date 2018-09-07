# Protocol for Co-funded LCC and CASC Products

---

### **For LCC/CASC Co-funded PRODUCTS:**

**  
**

1. **Create a metadata record for the product and fill out all LCC metadata requirements. Recommended workflow is:**

2. 1. **Import the sbJSON for the CASC product record.**

   2. 1. **Alternatively you can create a record from scratch in mdEditor and just copy the title, abstract, and other pertinent info from the CASC ScienceBase record.**
   3. **Delete the SBIDs specific to the CASC record.**

   4. **Modify the metadata to meet LCC metadata requirements.**

   5. **Complete the additional metadata requirements for a cofunded product below.**

   6. **Associate this LCC product record with the LCC version of the project record you created.**

**  
**

**Note: The LCC copy of the CASC metadata shouldnotinclude the data.gov tag. As a general rule, the entity who owns/hosts the data should be responsible for sending information to data.gov. In this case, the CASC is hosting the product/data on ScienceBase and they will be sending their information to data.gov directly.**

**  
**

**In addition to standard metadata requirements, complete the following for the co-funded product record:**

**  
**

1. **Add the name of all funding LCCs and CASCs as a “collaborator” in the metadata:**

2. 1. **In mdEditor, underMain/Point of Contacts**

   2. **In mdEditor, underMain/Citation/Responsible Parties**

   3. **Note: the lead LCC should be listed as “administrator” and does not need to be added again as a “collaborator.”**
3. **Include the lead LCC as “publisher” inMetadata/Metadata Contacts,according to**[**standard metadata contact requirements**](https://docs.google.com/document/d/1K0YGU4ZjGpbs1IUrkamffds6mdba48f9W2Hzk6H9dhs/edit#bookmark=id.o96zjsnbnz03)**. Collaborating CASCs \(or other LCCs\) do not need to be listed here.**

4. **Add the following textto bothMain/Abstract\(required; add as the last sentence\) and toMain/Supplemental Information\(Best Practice\):**

5. 1. **“This product was co-funded by the \[A, B, C\] Landscape Conservation Cooperatives and \[X, Y, Z\] Climate Adaptation Science Centers. An alternate reference to this product can be found here: \[insert CASC ScienceBase URL\].”**

   2. **Example: “This project was co-funded by the Gulf Coast Prairie Landscape Conservation Cooperative and the South Central Climate Adaptation Science Center. An alternate reference to this product can be found here:**[**https://www.sciencebase.gov/catalog/item/5887c1c3e4b02e34393da82d**](https://www.sciencebase.gov/catalog/item/5887c1c3e4b02e34393da82d)**.”**

   3. **The CASC will include a parallel statement in the Summary field for their ScienceBase record \(and link back to the LCC record\).**
6. **Since the CASC metadata is outside the LCC communities in ScienceBase, you must manually associate the LCC/CASC projects both in mdEditorAssociatedand directly on ScienceBase.**

**  
**

**Associations in mdEditor\(see Figure 11\).**

1. 1. **Make the normal project/product association back to the LCC version of the project record you created.**

   2. **Manually associate the LCC/CASC product as an “alternate” relationship in theAssociatedtab.**

   3. 1. **Populate the association type as “alternate”.**

      2. **Enter the appropriate resource type.**

      3. **Copy the CASC’s product title to populate the title field.**

      4. **Enter the CASC as the “administrator” in the Responsible Parties section.**

      5. **Add the CASC ScienceBase item URL to the Online Resource section. This is important to provide discovery and access to items outside of the LCC Science Catalog.**

      6. **Add the ScienceBase and/or Digital Object Identifier of the CASC product.**



![](https://lh5.googleusercontent.com/4EADVJYG-c8gq2il2fU-ttIyN7ly3IxNBpO_eIxQ9DGHzFGZzQcdUpPV5M4DgP6-GVj44iFOWzberaOTSSoHcjVklZExfx8-GUtYMlT5UaZrnKorcKqQqZdD0o7Z8y6lH7XGudjz)

![](https://lh4.googleusercontent.com/DTpBB7E9FNNuJsQZbdlMUeaZvUyynlp4k1bI_kxF4suv7pvLb_AmBXZx5AJkGzdPwmFNRdYZ0keeWyudeFn7-4i7Jt-YGSq_j3ZrOTyQ_R-nUMzCTunOoi3-QPS7nfvVxoG_9561)

**Figure 11: Example of mdEditor entry in Associated tab for LCC/CASC co-funded project. This is entered in the LCC project record’s Associated tab to indicate this is an “alternate” reference to a CASC project.**

**  
**

**Associations in ScienceBase. The only associations that ScienceBase recognizes from mdJSON are parentProject/product relationships so it will not recognize the “alternate” association created in mdEditor. This association must be added by hand directly in ScienceBase.**

1. **Log in to your ScienceBase account to edit the appropriate LCC ScienceBase item. Click “Associate an Item” from the right side column of the ScienceBase page. Add an “alternate” association to the CASC ScienceBase item \(see Figure 12 example\).**



![](https://lh3.googleusercontent.com/Y-WE_OLGwFwOsKRuYWCH4-PEBFF26VqhLpmJmbUIItDxpHMKZWDzDsASf8fK5Wz8auONqa97fi5Yw5VK2VfEIOkJfRTzVugHpEFOc2rNrJX83G06vL7eEYqzatSrsDXbGJ_NDAub)

**Figure 12: Example of LCC product record for an LCC/CASC co-funded product. The association created directly on ScienceBase identifies this GCP LCC product record as an “alternate” of the South Central CASC product record.**

1. **Include the CASC weblinks and identifiers that you just entered in the mdEditorAssociatedtab in two places:**

2. 1. **Main/Citation/Online Resource\(Required\):Name the link with “X Climate Adaptation Science Center ScienceBase Project Page” \(Required\).**

   2. **Distribution\(Required\): List the role of the CASC as “owner”. The Distribution links are critical for providing access to the actual data/tool/etc.**

**  
**

### **LCC/CASC Co-Funded Examples**

**The following are real examples of LCC and CASC co-funded projects and products. The links go directly to the ScienceBase records so you can download their mdJSON to explore how these were done.**

**  
**

**Gulf Coast Prairie LCC / South Central CASC example:**

**Project Record:**

* **LCC item:**[**https://www.sciencebase.gov/catalog/item/587e5cd5e4b0a765aab5ebab**](https://www.sciencebase.gov/catalog/item/587e5cd5e4b0a765aab5ebab)

* **CASC item:**[**https://www.sciencebase.gov/catalog/item/5818f601e4b0bb36a4c90743**](https://www.sciencebase.gov/catalog/item/5818f601e4b0bb36a4c90743)

**  
**

**Product Record:**

* **LCC item:**[**https://www.sciencebase.gov/catalog/item/5a78be62e4b00f54eb1e849c**](https://www.sciencebase.gov/catalog/item/5a78be62e4b00f54eb1e849c)

* **CASC item:**[**https://www.sciencebase.gov/catalog/item/5887c1c3e4b02e34393da82d**](https://www.sciencebase.gov/catalog/item/5887c1c3e4b02e34393da82d)

**  
**

**UMGL LCC / Northeast CASC example:**

**Project Record:**

* **LCC item:**[**https://www.sciencebase.gov/catalog/item/59fb44f5e4b0531197b16290**](https://www.sciencebase.gov/catalog/item/59fb44f5e4b0531197b16290)

* **CASC item:**[**https://www.sciencebase.gov/catalog/item/500708cee4b0abf7ce733ff1**](https://www.sciencebase.gov/catalog/item/500708cee4b0abf7ce733ff1)



