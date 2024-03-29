Note: This Python script has been compiled as a executable file and works on Windows operating systems.


Therefore "Decremental Files Sync Selected Dir Win.exe" would perform the following actions:

1. It starts by prompting the user to select a Source directory, and then it asks the user to select a Destination dir.

2. It verifies if it runs as administrator and if not, it will try to run it as the admin.

3. It identifies all the files in the Source directory (including in all sub-folder levels).

3. It asks for the Destination directory and therefore you can choose the parent directory you need.

4. It starts cloning, copying the files decrementally, while keeping the directory structure from the Source directory.






Full Description:

The term “Decrementally” means that the script would process the files in a decreasing order of file size:
The script would start with cloning the largest size files and proceed to clone the smaller, and smaller file size, ending with the smallest.
This is useful when you want files copied on a USB drive and you want to avoid it becoming fragmented (copying files from the biggest size to the smallest will not fragment the drive).

Therefore this Python script copies files from the user-selected Source directory to a user-selected Destination directory. The files are copied in descending order of their sizes.

Features:

Admin Privileges: The script checks if it has admin privileges and if not, it tries to grant itself administrator rights.

Folder Dialog: It uses the a specific library to open a dialog for the user to select the destination directory.

File Copy: It then copies files from the Source to the Destination directory.
File Size Sorting: It creates a list of tuples with file sizes and their respective paths, sorts this list in descending order, and then copies the files accordingly.

Directory Creation: If the destination sub-directories do not exist, it creates the respective directories, according to the Source directory hierarchy.
Directory Structure Preservation: The script maintains the directory structure of the sub-folders in the Source directory when copying files to the Destination directory.

Usage:

As a user you can run "Decremental Files Sync Selected Dir Win.exe" from any location. A dialog box will appear for you to select the Source directory, and then also a Destination directory.
The script will then copy the files in descending order of their sizes, preserving the directories structure of the Source directory. If the Destination sub-directories do not exist, it will create them.

Please note that this script requires admin privileges to run. If it does not have admin privileges, it will try to grant required privileges to run, if they are declined by the system the script will exit.

This script is particularly useful when you want to copy files onto a USB drive and want to avoid fragmentation. Copying files from the largest to the smallest size will not fragment the drive and for some Booting USB drives that's mandatory.

Disclaimer: Please use this script responsibly. Always ensure you have a backup of important files and folders.
The author is not responsible for any loss of data. Use at your own consideration.
