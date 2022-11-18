---
layout: default
title: Programs Used
parent: Digital Preservation Administration
nav_order: 1
---

# Programs Used

Digital preservation work requires many specialized command line or GUI-based tools and a knowledge of how to operate and modify those tools to fit changing needs. The following programs are installed on the digital preservation workstation by default. Following each program is a brief explanation of their purpose.  

- [7-Zip](https://www.7-zip.org/) 
    - Supports unzipping more diverse formats than default Windows Explorer.  
- [Brunnhilde](https://github.com/tw4l/brunnhilde), a reporting tool for digital preservation which bundles usage of tools such as the following, some of which must be installed separately:   
    - [Siegfried](https://www.itforarchivists.com/siegfried/)   
        - A file signature-based file format identification tool. 
    - [ClamAV](https://www.clamav.net/)   
        - Provides virus scanning for items being analyzed using Siegfried and Brunnhilde 
    - [bulk_extractor](https://github.com/simsong/bulk_extractor)   
        - Supports identification of Personally Identifiable Information (PII) from files.  
    - [The Sleuth Kit](https://www.sleuthkit.org/) (TSK)'s [tsk_recover](http://www.sleuthkit.org/sleuthkit/man/tsk_recover.html) 
        - Supports extraction of files from disk images.  
- [Bulk Rename Utility](https://www.bulkrenameutility.co.uk/)  
    - Supports renaming of files in bulk.  
- [Exact Audio Copy](https://www.exactaudiocopy.de/)   
    - Supports extraction of audio files from CD-DA formatted discs.  
- [Exiftool](https://exiftool.org/)      
    - Supports extraction of embedded Exif metadata in files.  
- [FastStone Image Viewer](https://www.faststone.org/) 
    - Supports viewing and batch operations on image files, including renaming, rotation, and file format conversion.  
- [FFmpeg](https://ffmpeg.org/)  
    - Used as an extension of Handbrake for commands Handbrake cannot support. The Association of Moving Image Archivists has a [helpful guide](https://amiaopensource.github.io/ffmprovisr/) to FFmpeg.  
- [FTK Imager](https://www.exterro.com/ftk-imager#:~:text=FTK%C2%AE%20Imager%20is%20a,(FTK%C2%AE)%20is%20warranted.)
    - Supports file system identification and analysis, disk imaging, and content extraction from items and disk images.  
- [Handbrake](https://handbrake.fr/) 
    - Supports reformatting and file conversion of various audiovisual files.  
- [HFS Explorer](https://www.catacombae.org/hfsexplorer/) 
    - Supports reading of Mac-formatted hard disks and disk images 
- [IsoBuster](https://www.isobuster.com/) (Free Version) 
    - Supports examination of media items, including file system identification and analysis.  
- [LibreOffice](https://www.libreoffice.org/)
    - Supports viewing and migrating a variety of file formats.
- [Spirion IdentityFinder](https://www.spirion.com/) 
    - Supports identifying and redacting PII from files.  
- [Teracopy](https://www.codesector.com/teracopy)   
    - Supports copying, movement, and checksum generation and validation pre and post copying and movement of files. 
- [Universal Viewer](https://uvviewsoft.com/uviewer/download.htm) 
    - Supports viewing of diverse file formats for review and description. 
- [Python](https://www.python.org/)
    - Programming language that, when used with external libraries, supports a variety of preservation activities. Python is a mandatory install for some of the programs mentioned here.  
- [Visual Studio Code](https://code.visualstudio.com/) and the [Python Extension](https://marketplace.visualstudio.com/items?itemName=ms-python.python)
    - Software to write, edit, and run code 
- [VLC Media Player](https://www.videolan.org/)
    - Supports playback of nearly all audio and video formats.  
- [WizTree](https://diskanalyzer.com/) 
    - Supports GUI-based analysis of file systems and formats. 

Additionally, iteratively improving workflows and staying up to date on new tools is key to a successful digital preservation program. The following programs have yet to be added to the workstation and implemented as part of digital archives workflows, but are currently being assessed:  

- [Bagger](https://github.com/LibraryOfCongress/bagger) 
    - GUI-based platform to “bag” files for preservation. 
- [Windows Subsystem for Linux](https://ubuntu.com/wsl) 
    - Provides a Bash command line to take advantage of non-Windows command line commands.  
- [Exactly](https://github.com/WeAreAVP/uk-exactly) 
    - GUI-based platform to “bag” files for preservation. 
- [QCTools](https://mediaarea.net/QCTools)   
    - Provides more systematic quality control of digitized audio and video files.  

