# Injector Script: Distribution Links

The following tutorial was developed by Matt Heller using the mdEditor File Injector script he developed, which can be used to do bulk edits on your mdEditor files. This demo specifically walks through how to add a Distribution Link. The injector script will look for a unique ScienceBase Identifier \(SBID\) that exists in the metadata and then build a URL for the **Distribution / Online Option** based on the SBID. The URL will be named "Product Web-page with Downloadable Files" and the Function selected will be "information."

A recording of this demo is available for viewing at: [https://mmancusa.webex.com/mmancusa/ldr.php?RCID=b1a81ed0c41871e76f205d7f2f507008](https://mmancusa.webex.com/mmancusa/ldr.php?RCID=b1a81ed0c41871e76f205d7f2f507008)

## You will need:

1. Access to some mdEditor files. Note: these must be mdEditor files, NOT the mdJSON files attached to the SB items.
2. Python installed on your PC.
   * If you have ArcGIS installed, there is a good chance Python is installed.

## Steps

### \(1\) Download script and other helpful files from GitHub.

a. Go to [https://github.com/mmheller/mdEditorFileInjector](https://github.com/mmheller/mdEditorFileInjector) and download all the files.

![](../.gitbook/assets/injector_download_script.png)

b. Unzip to any folder.

![](../.gitbook/assets/injector_unzip.png)

### \(2\) Gather some mdEditor files for the demo test.

a. Create a folder named **Demo** somewhere convenient.

![](../.gitbook/assets/injector_demo_folder.png)

b. Copy/paste 2-5 of YOUR mdEditor files into the Demo folder.

![](../.gitbook/assets/injector_demo_files%20%281%29.png)

### \(3\) Build the string that will have the necessary arguments to run the script.

a. Open any text editor \(e.g., notepad\) and enter the following letters with Dashes on separate lines \(**–C –T –O**\)

![](../.gitbook/assets/injector_script_b1.png)

b. Enter the path to the Demo folder in line **–C**. Note: all files and files in subfolders will be processed by the script. No original files will be edited, copies will always be made.

![](../.gitbook/assets/injector_demo_path_paste_2.png)

c. Add **False** to the -T line. This indicates we’re not adding new contacts to the available contacts list.

![](../.gitbook/assets/injector_script_b2.png)

d. Add **7** to the –O line. This specifies the option for the more complex find/replace

![](../.gitbook/assets/injector_script_b3.png)

### \(4\) Run the script.

a. Back in the text editor, add two blank lines in the beginning.

![](../.gitbook/assets/injector_script_b4.png)

b. Find the path to your python.exe and enter in the 1st line. Example: **C:\Python27\ArcGISx6410.6\python.exe**

c. Find the path to your .py injector script file and enter in the 2nd line. Note: this will be in the folder you downloaded and unzipped. Example: **C:\Temp\mdEditorFileInjector-master\mdEditorFileInjector\_v1.py**

![](../.gitbook/assets/injector_script_b5.png)

d. Remove all the carriage returns and extra spaces, and save if desired. Note: if any of your file paths have spaces, make sure to enclose the full path/filename with double quotes.

![](../.gitbook/assets/injector_script_b6.png)

e. Open a DOS prompt.

![](../.gitbook/assets/injector_dosprompt.png)

f. Copy/paste the text from your text editor into the command prompt to run.

![](../.gitbook/assets/injector_dos_paste.png)

### \(5\) Inspect the results.

a. Open mdEditor and clear the cache.

b. Click Import. Go to the demo folder and into the new folder created. Note: each time the process runs it will create a new folder and add new files to this folder.

![](../.gitbook/assets/injector_newfiles.png)

c. Select one of the new files to import.

d. Go to Distribution. Click Edit Distributors green button where the pointOfContact = LCC Network Data Steward.

![](../.gitbook/assets/injector_editdistributors.png)

e. Click Edit button in the Online Option section.

![](../.gitbook/assets/injector_distribution_onlineoption_edit.png)

f. Notice the injected fields. The Name of the online resource is "Product Web-Page with Downloadable Files" and the URL listed is the ScienceBase item link. The Function is "information" \(since the link is not a direct download of the data\).

![](../.gitbook/assets/injector_distribution_onlineoption.png)

Note: If it errors out, there’s a problem. Verify the LCC Network Data Steward exists and the Contact ID matches **edc6b779-3352-4a81-8430-76bcce1bfcb3**

