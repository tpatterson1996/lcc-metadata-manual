# Export

The export function allows the current set of metadata records to be saved as an mdEditor or mdJSON file. The saved files can be shared with collaborators, imported into another record set, imported into another browser. Exported mdEditor files should be saved as a backup or archival copy.

## **Using Export to Backup Records**

Exporting records is the only way to save mdEditor files outside of your browser cache. You should backup by exporting an mdEditor JSON file each time you finish a work session in mdEditor or switch browsers.

### mdEditor files vs. mdJSON files

mdJSON files can be uploaded and translated to other formats via the mdTranslator application while mdEditor files are exclusive to the mdEditor application and retain all mdEditor information, including Settings.

### **Best Practices**

* For a complete backup, use the **Export All** button. This exports an mdEditor file containing all records and contacts currently loaded in mdEditor.
* When exporting products or projects, you should also export your entire contact list. If you do not export your contact list, and you later import a record that contains a contact not in your mdEditor library, you may receive an error and have to re-create and re-enter the contact to that record.
* It is particularly important that you export your records for backup before using mdEditor's **Clear Storage Cache** functionality \(clearing the storage cache will delete any records or data you have entered into the mdEditor\). Exporting ensures that your data is secure even after clearing the storage cache. Not exporting your data before clearing your cache will result in a permanent loss of records. Consult the [Settings](../settings.md) section of this manual to learn more.

## Export Options

While exporting data, there are four options available \(on the right side of the export data window\).

![](../.gitbook/assets/export_data_action_menu.png)

* **Export All**: will export everything currently loaded in mdEditor into a single file. Exports an mdEditor JSON file.
* **Export Selected**: will only export the items you have selected \(so individual records, contacts, etc.\). If nothing is selected it will be disabled \(i.e., grayed out\). This exports an mdEditor JSON file.
* **Export mdJSON**: only works for metadata records \(i.e., doesn't work for contacts\). Exports just the mdJSON file, which is a standalone JSON file you can load into mdTranslator and have translated into other metadata formats. mdJSON files imported into mdEditor are treated as new records and will not merge/update an existing record.
* Clicking the **Include Settings** switch will also export mdEditor settings \(only for mdEditor files\). Consult the [Settings](../settings.md) section of this manual to learn about settings.

{% hint style="info" %}
If you need to switch browsers for mdEditor, or want to send your settings to someone else, you can export the settings. Someone else can then re-import your settings which include the default Metadata Repositories and Publishing Settings. This will give users that you share with information on your items' folder location on ScienceBase and let users know what your default repository is. Consult the [Settings](../settings.md) section of this manual to learn about settings.
{% endhint %}

