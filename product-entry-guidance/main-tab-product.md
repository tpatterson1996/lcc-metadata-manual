# Product Entry Guidance: Main Tab

---

The **Main **tab allows for the creation and/or editing of primary metadata.

---

| Quick Reference: Product Main Tab | Required?|
| :--- |:--- |
| Basic Information: Title, Status | Required |
| Resource Type | Required |
| Point of Contact | Required |
| Citation: Title, Responsible Parties, Online Resource | Required |
| Citation: Identifier | Best Practice |
| Citation: Alternative Titles, Date | Optional|
| Description: Abstract | Required |
| Time Period: Start Date, End Date | Required |

---

## Basic Information

### Record ID (Required)
Will be auto-generated but can be edited.

### Title (Required)
Enter as informative a title as possible. Good titles, when they appear in a search, will be understood and/or traceable.

### Status (Required)
The **Status** drop-down menu allows you to select the status of your product. Choose status ONLY from the four following options: _completed_, _ongoing_, _proposed_, or _accepted_.

![](/assets/main_screenshot_updated.png)

---

## Default Locale

**Default Locale **allows for the selection of **Language**, **Character Set**, and **Country**. English, UTF-8, and USA will be selected by default, but you may change them if necessary.

![](/assets/default_locale.png)

---

## Resource Types (Required)

The Resource Type should be automatically filled in with the resource type you selected when you created your record. Name is optional - you can leave this blank.


{% hint style='info' %} Products must have a specific resource type selected (not just "product"). {% endhint %}


---

## Point of Contacts

Adding a point of contact gives LCC staff information on who to contact should they have a question regarding your project or product. From the **Role **drop-down menu, select **pointOfContact**. From the **Contacts **drop-down menu, select a contact from the list of contacts. See the [Contacts](/product-entry-guidance/contact-entry-guidance.md) section for information on creating contacts.

| Role | Contact |Required?|
| :--- | :--- |:--- |
| pointOfContact | LCC Network Data Steward |Required|
| pointOfContact | Your LCC  | Required |
| principalInvestigator | The Project PI | Best Practice|

{% hint style='info' %}The LCC Network Data Steward will serve as the long term contact/backup. This way, users have a point-of-contact even if there is a positional change within an organization. The LCC Network Data Steward should be included in addition to any point of contact that you want to add from your organization. {% endhint %}


{% hint style='info' %}NOTE: For products that will be sent to data.gov, ensure that the LCC Network Data Steward is listed as the first point of contact \(\#0\). Data.gov only displays the first point of contact and we want the default contact to be the network data steward.{% endhint %}

![](/assets/point_of_contacts.png)

---

## Citation

The **Citation** lets users know pertinent information about your project or product such as responsible parties, internal and ScienceBase identifiers, and any online resources that may relate to your item. Adding information in the citation will also allow users to find your item when they search for items that contain said information.

#### ![](/assets/citation_updated.png)

The following fields are required in citation:

#### Title \(Auto-Generated\) 
Added automatically based on the title of your record.

#### Alternate Title \(Optional\) 
Add an alternate title.

#### Dates \(Optional\) 
Enter _acquisition_, _creation_, _revision_, or another date reference from the picklist and then enter the date.

#### Responsible Parties \(Required\) 
This must include a point of contact, but may also include other responsible parties such as funders \(including your LCC\), partners, collaborators, and contributors. Collaborators could be intellectual participants while contributors could be intellectual and financial participants.

| Role | Contact | Required? |
| :--- | :--- | :--- |
| pointofContact | LCC Network Data Steward | Required |
| administrator | Your LCC | Required |
| principalInvestigator | The Project PI | Best Practice|



  

#### Online Resource \(Required, if Available\) 
Enter the Name and URL for the location where users can find the product project homepage on your LCC website

{% hint style='tip' %} The URLs to access and download products must be included in the Distribution tab. Distribution Links is the only online resource that data.gov reads so without a URL there, users have no way to access the actual product from data.gov.{% endhint %}


#### Identifier (Best Practice) 
Enter a unique identifier for your project or product.

Best Practice: Use the identifier that your LCC is already using, or create something unique that is easily identifiable. 

   {% hint style='info' %} If you know your item's ScienceBase ID, you may add it here. If your item does not have a ScienceBase ID, ScienceBase will create one automatically upon publishing. If you edit an item that is already on ScienceBase without using its existing ID, a duplicate item will be created. Consult the [Publish](/publish.md) section of this manual to learn more.{% endhint %}
  
   {% hint style='info' %} If the product metadata was created by copying some other mdEditor metadata record, this identifier needs to be edited/changed since it will reflect the copied record identifier. Only the mdEditor UUID changes to represent a new record when an item is copied. Consult the [Copy Records](/data-management/copy-records.md) section of this manual to learn how to make a copy.{% endhint %}

  * The following identifiers are optional but you may add them: 
    * _Digital Object Identifier \(DOI\)_
    * _Funding identifier_
    * _Archive Folder Name._

---

## Description

**Description **allows for the addition of the** Abstract **as well as a Short Abstract, Purpose, Supplemental Information, and an Environment Description.

#### Abstract \(Required\) 
Enter an Abstract

  {% hint style='tip' %}Tip: Write your abstracts for projects in the present tense if   the project is underway and past tense if it has been completed.{% endhint %}

#### Short Abstract \(Optional\) 
Enter a short description, limited to 300 characters, if desired

#### Supplemental Information \(Optional\) 
Enter comments, if desired. 

![](/assets/description_lcc.png)

---

## Time Period

**Time Period** refers to project start and end date, or the date that the product was applicable \(e.g., time that a map is valid, date of publication, date of presentation\).

* **Required**: For each project, add a start date and end date.

![](/assets/time_period.png)

> For more information, consult the [**Record Main**](https://adiwg.gitbooks.io/mdeditor/content/record/edit/main.html) section of the mdEditor manual.



