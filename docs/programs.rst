Special Program/File Considerations
=====

Programs with large or multiple project files
------------
*Note - When a cloud storage account is connected any file you work on is directly synchronized with the Cloud.*

If you work on a single Excel or text file performance shouldn’t be impacted. However, if you open or save big projects that contain multiple files, libraries, segments or if the file sizes are excessive it might take a lot longer or even time out when try to Build projects or save big catalogs. 

In these cases we suggest the following workflow:

1. Copy the files from your Google/OneDrive to your Temporary folder and then open

    .. image:: _static/cloud_to_temp.png

2. Once you are done with your work save and copy the files back from Temporary files to your Google/OneDrive

    .. image:: _static/temp_to_cloud.png

3. Wait for a few minutes to allow those files to be uploaded to your Cloud location before terminating your AppStream session


Adobe Premier Pro File Import
------------

When importing files from cloud storage the import window will **NOT** be show your cloud storage under **This PC**. In order to access your cloud files you can navigate to the **M: drive** and your files will be there.