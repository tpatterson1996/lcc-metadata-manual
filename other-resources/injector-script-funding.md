# Injector Script: Funding

The following tutorial was developed by Matt Heller using the mdEditor File Injector script he developed, which can be used to do bulk edits on your mdEditor files. This demo specifically walks through how to add a contact with the role of "administrator" to funding allocations.

A recording of this demo is available for viewing at: [https://mmancusa.webex.com/mmancusa/ldr.php?RCID=b368e65eafffc4c076e9a4993f438b42](https://mmancusa.webex.com/mmancusa/ldr.php?RCID=b368e65eafffc4c076e9a4993f438b42)

## You will need:

1. Access to some mdEditor files. Note: these must be mdEditor files, NOT the mdJSON files attached to the SB items.
2. Python installed on your PC.
   * If you have ArcGIS installed, there is a good chance Python is installed.

## Steps

### \(1\) Download script and other helpful files from GitHub.

a. Go to [https://github.com/mmheller/mdEditorFileInjector](https://github.com/mmheller/mdEditorFileInjector) and download all the files.

![](../.gitbook/assets/injector_download_script%20%281%29.png)

b. Unzip to any folder.

![](../.gitbook/assets/injector_unzip%20%281%29.png)

### \(2\) Gather some mdEditor files for the demo test.

a. Create a folder named **Demo** somewhere convenient.

![](../.gitbook/assets/injector_demo_folder%20%281%29.png)

b. Copy/paste 2-5 of YOUR mdEditor files into the Demo folder.

![](../.gitbook/assets/injector_demo_files.png)

### \(3\) Build the string that will have the necessary arguments to run the script.

a. Open any text editor \(e.g., notepad\) and enter the following letters with Dashes on separate lines \(**–C –D –F –f –T –O**\).

![](../.gitbook/assets/injector_script_1.png)

For reference, the final version will look like this. Follow the specific steps below to write each line.

![](../.gitbook/assets/injector_script_2%20%281%29.png)

b. Enter the path to the Demo folder in line **–C**. Note: all files and files in subfolders will be processed by the script. No original files will be edited, copies will always be made.

![](../.gitbook/assets/injector_demo_path_paste.png)

c. Enter **“metadata\|funding”** in line **–D**. This is the location in the JSON that we’re telling the script to look for finding JSON text. Note: be sure to add double quotes for this argument.

d. For line **–F**

1. Copy/paste the path to the unzipped folder with all the injector script files.
2. AND copy/paste the file name **inject\_FundingAdministrator.txt**

![](../.gitbook/assets/injector_copy_path.png)

![](../.gitbook/assets/injector_coopy_filename.png)

Make sure to separate the path and filename with a back slash. This holds all the text we will inject.

e. For line **–f**, do the same thing but with the file name **find\_FundingAdminstrator.txt**. This holds all the text the script uses to find text to replace.

f. Add **False** to the **–T** line. This indicates we’re not adding new contacts to the available contacts list.

g. Add **6** to the **–O** line. This specifies the option for the more complex find/replace.

![](../.gitbook/assets/injector_script_2.png)

### \(4\) Edit the _inject\_FundingAdministrator.txt_ file with the Contact ID of your choice.

a. Open mdEditor, clear the cache, and then import one of the mdEditor files from the demo folder.

b. However you want to do it, copy the Contact ID of your choice.

![](../.gitbook/assets/injector_contactid.png)

c. Open **inject\_FundingAdministrator.txt** in a text editor and overwrite the Contact ID value in the file. Save and then close the file.

![](../.gitbook/assets/injector_contactid_save.png)

{% hint style="info" %}
Note: The Contact ID you enter must be the same for all the mdEditor files you want to run through the processor \(or are in the demo folder\). If you have different Contact IDs to inject across different records, you must do these in separate iterations of the script with only the relevant mdEditor files for each contact ID. _If you have different Contact IDs to add **within the same record**, you cannot use the script and must edit those records manually in mdEditor._
{% endhint %}

### \(5\) Open the _find\_FundingAdminstrator.txt_ file.

Make sure it says:

![](../.gitbook/assets/injector_matchingfalse.png)

### \(6\) Inspect one or more of the mdEditor files in mdEditor.

a. Go to Funding. Choose an allocation where match is not selected and click "More." Then click "Edit" for the allocation. Scroll down and notice no entries under “Other Contacts.”

![](../.gitbook/assets/injector_othercontacts_none.png)

### \(7\) Run the script.

a. Back in the text editor, add two blank lines in the beginning.

![](../.gitbook/assets/injector_script_blanklines.png)

b. Find the path to your python.exe and enter in the 1st line. Example: **C:\Python27\ArcGISx6410.6\python.exe**

c. Find the path to your .py injector script file and enter in the 2nd line. Note: this will be in the folder you downloaded and unzipped. Example: **C:\Temp\mdEditorFileInjector-master\mdEditorFileInjector\_v1.py**

![](../.gitbook/assets/injector_script_4.png)

d. Remove all the carriage returns and extra spaces, and save if desired. Note: if any of your file paths have spaces, make sure to enclose the full path/filename with double quotes.

![](../.gitbook/assets/injector_script_5.png)

e. Open a DOS prompt.

![](../.gitbook/assets/injector_dosprompt%20%281%29.png)

f. Copy/paste the text from your text editor into the command prompt to run.

![](../.gitbook/assets/injector_dos_paste%20%281%29.png)

### \(8\) Inspect the results.

a. Open mdEditor and clear the cache.

b. Click Import. Go to the demo folder and into the new folder created. Note: each time the process runs it will create a new folder and add new files to this folder.

![](../.gitbook/assets/injector_newfiles%20%281%29.png)

c. Select one of the new files to import.

d. Go to Funding. Choose an allocation where match is not selected and click "More." Then click "Edit" for the allocation. Scroll down and notice a new entry under “Other Contacts.”

![](../.gitbook/assets/injector_othercontacts_updated.png)

Note: If it errors out, there’s a problem. Go to the demo folder and into the new folder created and do the following:

1. Note the filename that is a problem
2. Remove the file from the demo folder 
3. Delete the new folder and files created from the last run
4. Rerun

