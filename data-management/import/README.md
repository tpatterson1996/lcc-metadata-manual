# Import

The Import function loads an mdEditor or mdJSON file into the current mdEditor session. You can also import existing ScienceBase metadata or FGDC \(Federal Geographic Data Committee\) metadata into mdEditor to create mdJSON.

## General Import Settings

### Replace vs. Merge

The **Replace/Merge** toggle allows you to either replace or merge the imported records with the records currently loaded in mdEditor. In most instances you should select "Merge." An exception is when you want to import Settings associated with an mdEditor file \(see below\).

{% hint style="danger" %}
Selecting "Replace" will remove all metadata records currently in mdEditor and leave only the newly-imported files. If you are importing a record to add to the existing records, choose "Merge."
{% endhint %}

### Import Settings

Only mdEditor files store Settings information; mdJSON files do not. You must import Settings to retain metadata repository information, default ScienceBase parent identifier, and auto-save preference. To import the Settings with an mdEditor file, set the import to "Replace" \(be sure you have already saved a backup copy of any files currently in mdEditor\). Set the mode back to "Merge” once you’ve finished importing the Settings.

If you have records already loaded into mdEditor with all desired Settings, then you do not need to re-import Settings when you import additional mdEditor files.

See next sections for specific file format import guidance on [mdJSON](mdjson.md), [sbJSON](sbjson.md), and [FGDC](fgdc.md) metadata.

