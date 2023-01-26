---
layout: default
title: Programs Used
parent: Digital Preservation Administration
nav_order: 1
---

# Programs Used

Digital preservation work requires many specialized command line or GUI-based tools and a knowledge of how to operate and modify those tools to fit changing needs. The following programs are installed on the digital preservation workstation by default. Following each program is a brief explanation of their purpose.  

- [7-Zip](https://www.7-zip.org/) 
    - _Usage Notes:_ Supports unzipping more diverse formats than default Windows Explorer.
    - _Install Notes:_ Standard install.   
- [Brunnhilde](https://github.com/tw4l/brunnhilde)
    - _Usage Notes:_ A reporting tool for digital preservation which bundles usage of tools such as the following, some of which must be installed separately:   
    - _Install Notes:_ Run "pip install brunnhilde" after all dependencies seen below are installed.
    - [Siegfried](https://www.itforarchivists.com/siegfried/)   
        - _Usage Notes:_ A file signature-based file format identification tool. 
        - _Install Notes:_ Download and extract folder of files. Move folder to program files and add to PATH. Run sf -update before using brunnhilde.
    - [ClamAV](https://www.clamav.net/)   
        - _Usage Notes:_ Provides virus scanning for items being analyzed using Siegfried and Brunnhilde.
        - _Install Notes:_ Download release and add extracted folder to Program Files. Add path to PATH. Move clamd.conf.sample and freshclam.conf.sample to root directory. Edit both files to remove .sample from the file name and delete the line of text reading "Example". Run freshclam on command line as administrator to verify install and update database.
    - [bulk_extractor](https://github.com/simsong/bulk_extractor)   
        - _Usage Notes:_ Supports identification of Personally Identifiable Information (PII) from files. 
        - _Install Notes:_ Standard install, no special instructions. 
    - [The Sleuth Kit](https://www.sleuthkit.org/) (TSK)'s [tsk_recover](http://www.sleuthkit.org/sleuthkit/man/tsk_recover.html) 
        - _Usage Notes:_ Supports extraction of files from disk images.  
        - _Install Notes:_ Download, extract, and add to program files. Add bin subfolder path to PATH.
- [Bulk Rename Utility](https://www.bulkrenameutility.co.uk/)  
    - _Usage Notes:_ Supports renaming of files in bulk.
    - _Install Notes:_ Standard install.
- [Exact Audio Copy](https://www.exactaudiocopy.de/)   
    - _Usage Notes:_ Supports extraction of audio files from CD-DA formatted discs.
    - _Install Notes:_ Standard install.
- [Exiftool](https://exiftool.org/)      
    - _Usage Notes:_ Supports extraction of embedded Exif metadata in files.  
    - _Install Notes:_ Download Windows executable, add to Program Files, add to PATH.
- [FastStone Image Viewer](https://www.faststone.org/) 
    - _Usage Notes:_ Supports viewing and batch operations on image files, including renaming, rotation, and file format conversion.  
    - _Install Notes:_ Standard install.
- [FFmpeg](https://ffmpeg.org/)  
    - _Usage Notes:_ Used as an extension of Handbrake for commands Handbrake cannot support. The Association of Moving Image Archivists has a [helpful guide](https://amiaopensource.github.io/ffmprovisr/) to FFmpeg.
    - _Install Notes:_ Download release, unzip folder, add to Program Files, and add the bin subfolder to the PATH.  
- [FTK Imager](https://www.exterro.com/ftk-imager#:~:text=FTK%C2%AE%20Imager%20is%20a,(FTK%C2%AE)%20is%20warranted.)
    - _Usage Notes:_ Supports file system identification and analysis, disk imaging, and content extraction from items and disk images.  
    - _Install Notes:_ Standard install, but must enter email and name to download.
- [Handbrake](https://handbrake.fr/) 
    - _Usage Notes:_ Supports reformatting and file conversion of various audiovisual files.  
    - _Install Notes:_ Standard install. Upon starting the program for the first time, you must follow the .NET install link to install .NET if it is not already installed. This only has to be done once.
- [HFS Explorer](https://www.catacombae.org/hfsexplorer/) 
    - _Usage Notes:_ Supports reading of Mac-formatted hard disks and disk images.
    - _Install Notes:_ Standard install, but must also install Java SE Development Kit before running the program.
- [IsoBuster](https://www.isobuster.com/) (Free Version) 
    - _Usage Notes:_ Supports examination of media items, including file system identification and analysis.  
    - _Install Notes:_ Standard install. Must click Free funct. only when using IsoBuster for the first time.
- [LibreOffice](https://www.libreoffice.org/)
    - _Usage Notes:_ Supports viewing and migrating a variety of file formats.
    - _Install Notes:_ Standard install.
- [Spirion IdentityFinder](https://www.spirion.com/) 
    - _Usage Notes:_ Supports identifying and redacting PII from files.
    - _Install Notes:_ N/A, installed on all university machines as it is part of a license. 
- [Teracopy](https://www.codesector.com/teracopy)   
    - _Usage Notes:_ Supports copying, movement, and checksum generation and validation pre and post copying and movement of files. 
    - _Install Notes:_ Standard install.
- [Universal Viewer](https://uvviewsoft.com/uviewer/download.htm) 
    - _Usage Notes:_ Supports viewing of diverse file formats for review and description.
    - _Install Notes:_ Must download, extract, and add to program files. No installer--simply add a shortcut to the Viewer file in the root directory for easy access from the desktop.
- [Python](https://www.python.org/)
    - _Usage Notes:_ Programming language that, when used with external libraries, supports a variety of preservation activities. Python is a mandatory install for some of the programs mentioned here.
    - _Install Notes:_ Add to PATH.
- [Visual Studio Code](https://code.visualstudio.com/) and the [Python Extension](https://marketplace.visualstudio.com/items?itemName=ms-python.python)
    - _Usage Notes:_ Software to write, edit, and run code.
    - _Install Notes:_ Standard install for VS Code. Once in VS Code, go to extensions, search "python", and select the Microsoft created python extension.
- [VLC Media Player](https://www.videolan.org/)
    - _Usage Notes:_ Supports playback of nearly all audio and video formats.
    - _Install Notes:_ Standard install.
- [WizTree](https://diskanalyzer.com/) 
    - _Usage Notes:_ Supports GUI-based analysis of file systems and formats. 
    - _Install Notes:_ Standard install.

Additionally, iteratively improving workflows and staying up to date on new tools is key to a successful digital preservation program. The following programs have yet to be added to the workstation and implemented as part of digital archives workflows, but are currently being assessed:  

- [Bagger](https://github.com/LibraryOfCongress/bagger) 
    - GUI-based platform to “bag” files for preservation. 
- [Windows Subsystem for Linux](https://ubuntu.com/wsl) 
    - Provides a Bash command line to take advantage of non-Windows command line commands.  
- [QCTools](https://mediaarea.net/QCTools)   
    - Provides more systematic quality control of digitized audio and video files.  

