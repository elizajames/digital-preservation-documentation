---
layout: default
title: Imaging and Born Digital Content Acquisition 
parent: Born Digital Materials
nav_order: 7
---

# Imaging and Born Digital Content Acquisition Procedures
{: .fs-6 .fw-300 }

## On this page
{: .no_toc .text-delta }

1. TOC
{:toc}

## Format Workflows

All workflows in this document assume a collection or accession has been formally received by the West Virginia & Regional History Center and is accompanied by a Deed of Gift or Loan. Ideally, all materials will have an accession number and, if applicable, an A&M number. If an item or set of items does not have an accession number, talk to the Accessioning Archivist.  

The DVD, CD, IsoBuster, and FTK Imager workflows are greatly informed by Annie Schweikert’s [work on optical media at NYU](https://archive.nyu.edu/handle/2451/43877). 

### Digital Transfer

Sometimes donors have a limited quantity of content and would like to transfer their materials exclusively digitally rather than via a hard drive or other physical media. Depending on the quantity, this transfer may be via email or a file share such as Box, OneDrive, or Google Drive.  

The following workflows outlines two transfer methods: Ideal and Acceptable.  

- The Ideal method is best for donors with technical expertise or content that is highly valuable and needs to retain as much built-in metadata as possible.  
- The Acceptable method is best for donors with limited technical expertise or content that only needs to maintain most metadata. 

#### Donor Guidance
 
##### Ideal Workflow

This section outlines an ideal workflow for donors with moderate technical expertise who are donating highly valuable content. 

_A workflow using Exactly is in-progress_

##### Acceptable Workflow

This workflow requires minimal technical expertise and maintains most metadata. The instructions below can be forwarded directly to donors.  

__Windows Users__

1. Locate the file or folder that you want to zip. 
2. Right-click the file or folder, click “Send to” in the menu that pops up, and then select “Compressed (zipped) folder.”  
3. Name the compressed folder something that is descriptive of the content—such as including your name and the date of the transfer. 
4. If the compressed item is small enough to email, attach it and email it to the archivist you’ve been working with. If it is too large, upload it to the link provided to you by the archivist and let the archivist know you’ve uploaded it.  
    * Note: the Archivist receiving the materials must create a folder in OneDrive that has edit permissions for non-WVU users. The URL for this folder should then be sent to the donor. 

__Apple Users__

1. Locate the file or folder that you want to zip.  
2. Control-click it or tap it using two fingers, then choose Compress from the shortcut menu. 
3. If you compress a single item, the compressed file has the name of the original item with the .zip extension. If you compress multiple items at once, the compressed file is called Archive.zip. Rename the compressed folder something that is descriptive of the content—such as including your name and the date of the transfer. 
4. If the compressed item is small enough to email, attach it and email it to the archivist you’ve been working with. If it is too large, upload it to the link provided to you by the archivist and let the archivist know you’ve uploaded it. 
    * Note: the Archivist receiving the materials must create a folder in OneDrive that has edit permissions for non-WVU users. The URL for this folder should then be sent to the donor. 

#### Procedures Upon Arrival to WVRHC

1. Once the content has been deposited to a shared space or sent via email, add information about the transfer to the digital media inventory for the collection or accession, found in the Administration folder for the collection or accession. If there is no folder for the collection or accession, consult the Born-Digital Materials Accessioning procedures to create a folder.  
2. Create two folders on the desktop using the media item’s identifier identified in the digital media inventory: identifier_content and identifier_metadata. The word “identifier” should be the identifier for the item, not the word identifier.  Example: 2828_disc_1_content  
3. Download the .zip file to your desktop.  
4. Unzip the file by selecting the .zip file, clicking the Extract/Compressed Folder Tools (boxed in red on the left) option on the toolbar at the top and then selecting Extract All. Extract the content to the identifier_content folder on the desktop.  

5. Run the following command on the command line, being sure that the input directory is the identifier_content folder and the output directory is the identifier_metadata folder. 
    - brunnhilde.py -b -z --ssn_mode=2 [input directory, or content folder for item] [output directory, or File Metadata folder for item]  
    - Example: brunnhilde.py -b -z --ssn_mode=2 C:\Working Files\2828_disc_1_content C:\Working Files\2828_disc_1_metadata 
    - Note: if an item is flagged as a virus by ClamAV (visible on the command line output), contact the Digital Archivist with the identifier for the item and immediately delete all content on the desktop and empty the Recycling Bin. Update the PREMIS spreadsheet in the Administrative folder within the folder for the collection or accession to include the event of Quarantine (if necessary) for the item. Do not continue to any additional steps.  
6. Move the identifier_content folder to the Content folder for the collection or accession and the identifier_metadata folder to the Metadata folder within the Administration folder within the accession or collection folder using the TeraCopy instructions. Remove _content and _metadata from the folder names. 
7. Update the PREMIS spreadsheet in the Administrative folder within the folder for the collection or accession to include the events for Brunnhilde report, Replication, and/or Quarantine (if necessary) for the item.  

### CDs and DVDs

#### CD-DA

#### All Other CD and DVD Formats

### 3.5 Inch Floppy Disks

### Thumb Drives, Internal Hard Drives, External Hard Drives, and Memory Cards

#### Thumb Drives and External Hard Drives

#### Internal Hard Drives

#### Memory Cards

## Hardware Workflows

### Tableau Forensic Bridge

## Software Workflows

### FTK Imager

#### Imaging an Item

#### Viewing a Disk Image or Media Item

#### Extracting Content from a Disk Image or Media Item

### IsoBuster

#### Identifying the Format of a Disc

#### Imaging an Item

#### Viewing a Disk Image or Media Item

#### Troubleshooting Potential Errors

### HFS Explorer

### Exact Audio Copy

#### Extracting Content

### Teracopy

### Command Line Tools

#### Tree

#### Brunnhilde

### Exactly