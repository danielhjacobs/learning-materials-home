# Transferring Data with Cyberduck

Cyberduck is a 3rd party software (available as freeware) tool that
allows you to drag-and-drop large and/or multiple files between your local computer and the
Data Store. Cyberduck can also be used to rename files and browse other
shared or public Data Store locations. 

------------------------------------------------------------------------

## Download and first-time configuration of Cyberduck

1.  Download Cyberduck at the [Cyberduck Website](https://cyberduck.io/download/); follow the installation instructions
    for your operating system.
2.  Download the [CyVerse connection profile](https://cyverse.atlassian.net/wiki/download/attachments/241869843/CyVerseDataStore.cyberduckprofile?version=1&modificationDate=1568640173000&cacheVersion=1&api=v2) Double-click on the downloaded file to open the installed Cyberduck software.
 3.  In the Cyberduck configuration window, enter your **CyVerse
    username** in the field 'iPlant username'.
4.  Under 'Advanced Options' ensure the 'Transfer Files' option is set
    to **'Open Multiple Connections'**. Close this window - your
    entries will be automatically saved.
    ![cyberduck_config](../assets/ds/cyberduck_config.png){ width="600" }
 5.  Double-click on the Data Store bookmark in the Cyberduck window.
    Enter your CyVerse credentials.
    ![cyberduck_bookmark](../assets/ds/cyberduck_bookmark.png){ width="600" }


You should now be connected to the CyVerse Data Store and viewing the
contents of your home directory.

!!! Tip

        At the top of your Cyberduck window you can see your location within the
        Data Store. From Cyberduck's 'Go' menu, you can select 'Go to
        folder' to navigate to any other Data Store location that is public or
        shared with you.
        ![cyberduck_window](../assets/ds/cyberduck_window.png){ width="600" }

------------------------------------------------------------------------

## Upload from local computer to Data Store using Cyberduck

!!! Warning

        When uploading your data to the Data Store, avoid naming
        files/folders with names containing spaces (e.g., experiment
        one.fastq) or special characters (e.g., ``~ ` ! @ #
        $ % ^ & * ( ) + = { } [ ] | : ; " ' < > , ? / and \``). The Apps on
        the Discovery Environment and most command line applications will
        typically not tolerate these characters. For long file/folder names, 
        we recommend using underscore(s) (e.g., experiment_one.fastq) instead of spaces.

1.  Double-click on the Data Store bookmark to connect to the Data
    Store.
2.  Select file(s)/folder(s) from your local machine and drag them
    into the Cyberduck window. (You may drag directly into an existing
    folder or from the Cyberduck 'File' menu, create a new folder).
3.  A 'Transfers' window will appear. Monitor the upload to
    completion.
    ![cyberduck_transfers](../assets/ds/cyberduck_transfers.png){ width="600" }

------------------------------------------------------------------------

## Download from Data Store to local computer using Cyberduck

1.  Double-click on the Data Store bookmark to connect to the Data
    Store.
2.  Select file(s)/folder(s) in the Data Store (Cyberduck window) and
    drag them to a location on your local computer.
3.  A 'Transfers' window will appear. Monitor the download to
    completion.

!!! Tip

        In the Cyberduck 'File' menu, there are several more functionalities.
        You can directly specify files and folders to move without
        dragging and dropping them. You can also 'synchronize' folders - 
        copying only items that are missing in a folder rather than copying all
        contents.


