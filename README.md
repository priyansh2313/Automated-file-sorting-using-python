# Automated-file-sorting-using-python

#Key Features



Real-Time Monitoring: The program continuously watches the Downloads folder for new files.
Automatic Sorting: Files are instantly moved to appropriate subfolders (Audio, Video, Images, Documents) based on their file types.
Broad File Type Support: Recognizes and sorts a wide range of file types:
Audio: .mp3, .wav, .aac, .flac, etc.
Video: .mp4, .mkv, .avi, .mov, etc.
Images: .jpg, .png, .gif, .bmp, etc.
Documents: .pdf, .docx, .xlsx, .pptx, etc.
Customizable: Easily add or modify file types and categories to suit specific needs.
Implementation Details
The project is written in Python, using the watchdog library to detect changes in the Downloads folder. When a new file is detected, it is classified based on its extension and moved to the corresponding subfolder.












Key components include:

FileMonitor Class: Utilizes watchdog to track changes.


EventHandler Class: Manages file system events and processes files.


FileSorter Function: Classifies and moves files to the appropriate subfolders.









Technologies Used

Python: Core programming language.


watchdog: For real-time file system event monitoring.


os and shutil: For file manipulation and directory operations.



How It Works
Setup: Initialize the watchdog observer to monitor the Downloads folder.
Event Handling: The event handler classifies incoming files based on their extensions.
File Sorting: Files are moved to respective subfolders (Audio, Video, Images, Documents).
Continuous Operation: The observer ensures the Downloads folder remains organized at all times.
Impact









DISCLAIMER: U have to first create folders for repsective music , images , documents foe the arrangement anywhere on your pc 
