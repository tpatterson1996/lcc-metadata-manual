# sbJSON

This method should be used when you have an existing ScienceBase item that has not yet been edited in mdEditor. The ScienceBase item may or may not have the ScienceBase Project facet. Importing the metadata from ScienceBase allows you to use the existing metadata and and not start from scratch in mdEditor.

## ScienceBase

1. In the "Import from Online URL field," paste: [https://api.sciencebase.gov/sbmd-service/mdjson/](https://api.sciencebase.gov/sbmd-service/mdjson/)

   You can set default import URL to the "ScienceBase API link" in the Settings section and it will pre-populate this field. Refer to the [Settings](../../settings.md) section.

2. Copy and paste the **ScienceBase ID \(SBID\)** of the item that you wish to import at the end of the URL in the import field, and click the **Import** button.

   The SBID is the string of letters and numbers at the end of the item’s ScienceBase URL. For example, "5a70c2d6e4b0a9a2e9dafbdf" would be the SBID for the item at the URL [https://www.sciencebase.gov/catalog/item/5a70c2d6e4b0a9a2e9dafbdf](https://www.sciencebase.gov/catalog/item/5a70c2d6e4b0a9a2e9dafbdf)

   ![](../../.gitbook/assets/import_sbjson.PNG)

3. Review the selected information. If there is more than one copy of the same metadata record or contact, use the "preview JSON" button to choose the record or contact with the most complete information.
4. Select the records and contacts you want to import.
5. Click on the right hand button “**Click to Import Data.**”



   Once you have imported a ScienceBase item and edited the metadata in mdEditor, you must always edit the metadata in mdEditor and re-publish to ScienceBase.

