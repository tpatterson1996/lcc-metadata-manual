# How to Publish

**BEST PRACTICE**: Always refresh your browser before you access the publishing menu to ensure that you are using the most updated version of mdEditor. However, if you have already moved items around in the publishing outline \(see below for details\), you will lose this information once you refresh.

## **Publishing Overview**

**Step 1:** Login to ScienceBase

**Step 2:** Move Records in the Publishing Outline

**Step 3:** Submit for Publishing

**Step 4**: Review Records on ScienceBase

**Step 5**: Review Entries in the LCC Science Catalog

### Step 1: Login to ScienceBase

1. Click the **Publish** button from the top menu in mdEditor.
2. You will be asked to select a _publishing service_. Click on ScienceBase.
3. A login window will appear on the right side of the screen - enter your ScienceBase ID and password, and click **Login**. When you are logged in, the login window will display who you are logged in as. _The current user must have read/write permissions on ScienceBase for any items to be published \(including parent items\)_. You cannot publish until you are logged in.

#### The mdEditor Publishing Outline:

You will see a list of every valid record in mdEditor in the publishing outline with its ScienceBase Identifier \(if the record already exists on ScienceBase\) and its parent ScienceBase Identifier \(if present in the metadata\). This publishing outline shows records in a parent-child relationship and reflects what you would see when you publish to ScienceBase.

{% hint style="info" %}
Remember: Parent-Child relationships refer to how the records are organized and displayed on ScienceBase. This is different than the Project and Product associations identified within the metadata records.
{% endhint %}

* Records **without parent IDs** already in their metadata will appear directly under the ScienceBase header in the publishing outline. These records will be published under the default parent identifier you established in the settings. The Default parent identifier is listed in the ScienceBase header, which is hyperlinked to the record on ScienceBase.
* Records **with parent IDs** identified in their metadata will appear below a thick blue line and will be published under the parent ID listed in their metadata.

> ![](../.gitbook/assets/publish_screenshot_2.png)

Items directly below the ScienceBase header will be published under the ScienceBase item identified in your settings as “Default Parent Identifier.” Items below the blue line will be published under the parent ID specified in the metadata.

For example, if the _Default Parent Identifier_ is your LCC Community, then projects at the _root level_ in the publishing outline will be added directly under your LCC Community, but products nested under a project in the outline will be added as a direct child item to the project item on ScienceBase. Items listed at the root level in the publishing outline don't have a parentID that correspond with a record loaded in mdEditor \(_Note: you could have other parent IDs identified in those records, but those records aren't loaded in mdEditor\)_

### Notes on Moving Records

You can drag and drop records to establish the parent-child relationship, eliminating the need to establish the relationship in ScienceBase. This will also allow you to move items around \(e.g., move a product from one project to another\) and have that change be reflected on ScienceBase. _Remember, this is only about parent-child relationships on ScienceBase, not about project-product associations._

{% hint style="danger" %}
If you do not want these parent IDs to change, **do not** drag and drop these records in the publishing outline.
{% endhint %}

#### **General Notes on Parent IDs**:

* If you move a product under a different project, it will update that product’s parent ID.
* Parent IDs established through the relationships in the publishing outline will overwrite existing parent IDs in the metadata.
* Dragging and dropping a record onto the ScienceBase header at the top will set that record’s parent ID to the default parent ID you identified in Settings.
* If you have existing parent IDs in your metadata \(and want to keep them as is\), **do not** drag and drop those records onto the ScienceBase header-- this will erase the existing parent ID and insert what you have set as the default parent identifier.

### Step 2: Move Records in the Publishing Outline

_Before you move records in the publishing outline please select your scenario below and follow the corresponding guidance._

#### Scenario A

_You **do not have** items on ScienceBase yet, and your desired parent-child relationship is to have each product as a direct child of a project item on ScienceBase:_

* Your records will all display under the ScienceBase header in the publishing outline. 
  * These items will be published as a direct child item under the SB item identified in your settings under “Default Parent Identifier.”
* You can **drag and drop** records in the publishing outline to establish parent-child relationships for ScienceBase.
* You can **nest** items in as many levels as you desire \(the most common is a product nested under a project\).
* To move a record back to the root level, drag and drop it on the top line that says “ScienceBase Default”.

#### Scenario B

_You **have** existing parent-child relationships on ScienceBase and/or you have intermediate folder\(s\) between project items and products \(i.e., products are not direct child items of Project Items - this is not recommended\)._

* If you have parent-child relationships already established on ScienceBase \(and those IDs are reflected in the mdEditor records\), you likely do not want to move the records around in the publishing outline.
* If your products are housed in a “Products” folder on ScienceBase \(or other intermediate folders between the project item and the products\), then your products **will not** be nested under projects in the publishing outline. 
  * The parent ID for those products is the “Products” folder \(which would not have a record in mdEditor\). If this is your situation, do not change the structure in the publishing outline and publish as is \(i.e., with every item organized at the root level in the outline\).

### Step 3: Submit for Publishing

1. To select a record to publish, click on it and it will turn green \(click again to un-select it\).

   You cannot publish a record without a parent ID. Sending a non-existent parent ID to ScienceBase will return an error. If your records contain parent IDs in the metadata, you can choose to publish products without publishing their associated projects at the same time.

2. mdEditor will publish your records sequentially, starting with the top record \(it will publish the project first, then the products nested below it\).
   * If you are publishing to your _default parent identifier_ or if you have changed any project-product relationships in the publishing outline, you will see the updated parent IDs appear in the outline as publishing occurs. If you’re publishing to the existing locations on ScienceBase, the IDs won’t change.
   * These new/updated IDs will be injected directly into the mdJSON file in mdEditor. However, these updated IDs will not be included in the mdJSON file that is attached to ScienceBase as part of the publishing process. You would have to publish the record a second time to update the mdJSON file attached on ScienceBase.
3. Upon successfully publishing to ScienceBase, the third column will display a date and time. The record's ScienceBase ID will be displayed in the first column, and the Parent ID will be displayed in the second column. If there are any errors during publishing, they will be noted in the third column.

### Step 4: Review Records on ScienceBase

1. Once publishing is done, refresh ScienceBase to ensure everything is showing up how you expected it would show up.
   * SB items should have an mdJSON and XML file attached
   * SB items should be in the location reflected in the mdEditor publishing outline
2. You can re-publish records as needed \(e.g., after updating or correcting metadata\).

### Step 5: Review Entries in the LCC Science Catalog

The Science Catalog updates overnight so you should review newly-published records the day after you publish to ScienceBase. This will be one of your best quality control checks.

