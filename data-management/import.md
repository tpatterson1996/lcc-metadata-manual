# Import \(![](/assets/symbol_sign-in_16.png)\)

---

The Import function will allow the contents of an mdEditor or [mdJSON](https://github.com/adiwg/mdJson-schemas/blob/master/test/draft-04.json) file to be incorporated into the current metadata record. The Import functionality lets you load the most recently edited records and load records that were exported from another browser.

---

## Import Existing mdJSON

![](/assets/import_window.png)

1. You can click the **Import Data **button to import a local file, or simply drag and drop files onto the button. Files can also be imported using the **Import from Online URL **functionality.

2. Review what was imported. Click the “preview JSON” buttons to sort between multiple entries of the same contact, and decide which version to keep. \(If there is more than one copy of a record/contact, choose the record or contact with the most complete information\).

3. Select the records and contacts you want to import, and then click on the right hand button “**Click to Import Data**” to import the selected records. If there is more than one of the same record, use the "preview JSON" button to choose the record or contact with the more complete information.

> Note: The **Replace/Merge **toggle allows you to either replace or merge the imported records with the records currently loaded in mdEditor. In most instances you should select "Merge." If you want to import the Settings associated with a record, you should set the import to “Replace” \(and set the mode back to "Merge” once you’ve finished importing the settings\).

![](/assets/import_data.png)

---

## Import ScienceBase Items

This function should be used when you have existing ScienceBase items that have not yet been edited in mdEditor. Importing from ScienceBase will allow you to use the existing metadata and and not start from scratch in mdEditor.

### ScienceBase Import Method 1:

1. **Copy the ScienceBase ID \(SBID\)** from an existing ScienceBase item 
   The SBID is the string of letters/numbers at the end of the item’s ScienceBase URL 
   * For Example,  "5947e765e4b062508e34424" would be the SBID for an item at the URL [https://www.sciencebase.gov/catalog/item/5947e765e4b062508e34424a](https://www.sciencebase.gov/catalog/item/5947e765e4b062508e34424a\)
2. Go to the ScienceBase API address: [https://api.sciencebase.gov/sbmd-service/mdjson/,](https://api.sciencebase.gov/sbmd-service/mdjson/) add the SBID to end of this link, and hit enter. You should see mdJSON text as below.  If not, press enter to search again.

   ## ![](/assets/raw_text_screenshot.png)

3. Right-click in the text area and select “save as” and add “.json” to the end of the file name. This will download the JSON file to your computer.

4. You can either drag the JSON file to the drop box in mdEditor from the download link visible in your browser or from the location on your computer where you saved the file.

5. Review what was imported. Click the “preview JSON” buttons to sort between multiple entries of the same contact, and decide which version to keep.

6. Select the Records and Contacts you want to Import.

7. Click on the right-hand button “**Click to Import Data**” to import the selected records.

### ScienceBase Import Method 2

Use this method for items where no mdJSON already exists, may or may not have ScienceBase Project facet.

1. In Import URL field, paste: [https://api.sciencebase.gov/sbmd-service/mdjson/](https://api.sciencebase.gov/sbmd-service/mdjson/)
   > **NOTE:** You can set default import URL to the "ScienceBase API link" in settings section and it will pre-populate this field. Please refer to the [Settings](/settings.md) section of this manual.
2. Copy and paste the **ScienceBase ID \(SBID\) **of the item that you are trying to import at the end of the URL in the import field, and click the **Import** button.
   * The SBID is the string of letters and numbers at the end of the item’s ScienceBase URL. For example,  "5a70c2d6e4b0a9a2e9dafbdf" would be the SBID for an item at the URL [https://www.sciencebase.gov/catalog/item/5a70c2d6e4b0a9a2e9dafbdf](https://www.sciencebase.gov/catalog/item/5a70c2d6e4b0a9a2e9dafbdf) 
3. Review what was imported. Click the “preview JSON” buttons to sort between multiple entries of the same contact, and decide which version to keep. 
4. Select the Records and Contacts you want to Import.
5. Click on the right-hand button “**Click to Import Data**” to import the selected records.

---





