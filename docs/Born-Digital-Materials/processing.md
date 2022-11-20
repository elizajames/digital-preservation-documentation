---
layout: default
title: Processing
parent: Born Digital Materials
nav_order: 3
---

# Processing
{: .fs-6 .fw-300 }

## On this page
{: .no_toc .text-delta }

1. TOC
{:toc}

## Processing Overview

For born digital materials at the WVRHC, processing is the act of turning the Submission Information Package (SIP) into an Archival Information Package (AIP) and Dissemination Information Package (DIP). An AIP is the set of files and metadata that will be put into preservation storage while a DIP is the set of files that will be made available to a user. Typically, at the WVRHC, AIPs and DIPs are identical unless the file formats present in the original collection are unfriendly to users, there are materials that require redaction, or there are materials that are restricted by the donor. The act of processing materials will identify files impacted by these considerations and outline methods of acting on the files.  

Processing for a collection is initiated based on A&M unit priorities. Hybrid collections, or collections with both physical and digital media, require coordination between the Digital Archivist and individual processing the physical A&M collection to coordinate descriptive processes. Fully born digital collections are prioritized primarily by the Digital Archivist with the A&M unit providing input on which collections must be processed sooner based on donor commitments or loan agreements.  

When digital material exists alongside records in other formats, it is important that decisions and actions in processing the digital material consider and respect the organization of the whole collection. This means that, where possible, processing decisions should stray away from isolating and placing born digital materials in a separate series and instead integrating description and processing of those materials into the larger organization of the collection. The general principles of archival theory and management (original order, provenance, aggregate description) apply to born digital materials to the same degree that they apply to analog materials. This means that, in most cases, materials will not have their files renamed nor will they be manually moved except in exceptional circumstances. These circumstances should always be documented.  

Born digital materials already contain much of their own description and can be computationally processed in ways that analog materials cannot. Where possible, let computers do the tasks that they are best at and focus processing efforts on the tasks at which humans excel--namely, analysis of content and context. Arrangement and description work should typically focus on higher-level folders in a directory structure or on a piece of media as a whole, as determined during appraisal. Manual arrangement and description of individual files is the exception and should be undertaken only in extraordinary cases.  

## Processing Workflow

Before starting to process an accession, an Archives & Manuscript collection number is needed. Request a number from Accessioning Archivist or Head of Archives & Manuscripts. Once a collection number has been assigned, generate a resource record for the collection from the original accession. If adding an accession to an existing resource record/collection, simply link the accession record to the resource record.  

Move the accession folder containing the materials from the Z:\Backlog folder to the Z:\A&M folder. If a new collection with no other accessions, rename the top-level folder to the A&M number and rename folder-level references in the Born Digital Content and Administration\Metadata folder to replace the accession number with the new Archives & Manuscripts number. If the materials are an accrual, maintain the accession number but prefix it with the A&M number and an underscore. The Bulk Rename Utility program is helpful for collections with many folders that need to be renamed to minimize manual renaming.   

All processing work must be completed on a copy of the files to mitigate the possibility of modifying the original files. For small collections of materials, copying the materials to the processor’s desktop should be sufficient. For larger collections, contact the Digital Archivist for a drive containing the materials that can be used for processing.  

Open the [PREMIS Spreadsheet](https://elizajames.github.io/digital-preservation-documentation/assets/files/PREMISSpreadsheet.xlsx) for the collection and review the Appraisal events. Follow the general set of principles for each level outlined in the following table: 

|       __Level of Processing and Description__  |                                                                                                        __Principles__                                                                                                    |
|--------------------------------------------|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|
|     Minimal                                |   Restrict processing actions to the media item level or actions that can be easily conducted in bulk.                                                                                                               |
|     Enhanced                               |   Restrict processing actions to folder level within the media item, ideally the top-level folder within the media item, or actions that can be easily conducted in bulk with minimal manual intervention (if any).  |
|     Intensive                              |   Processing actions may be conducted at the item level using manual intervention.                                                                                                                                   |

## Create Access Copies of Disk Images 

If disk imaging was required for an item, you will need to extract a copy of the files for user access. Within the folder for an item in the Born Digital_Content folder for the collection, retain the disk image in the folder named for the item’s identifier but create a new folder titled with the identifier followed by _DIP. The _DIP folder is where the extracted content will be stored. 

<img src="https://elizajames.github.io/digital-preservation-documentation/assets/images/media_main_manual/image10.png" alt="Comparison of folder containing AIP and folder containing DIP in file explorer">

To extract the content, follow the FTK Imager instructions for Extracting Content from a Disk Image or Media Item in the [Imaging and Born Digital Content Acquisition Procedures](https://elizajames.github.io/digital-preservation-documentation/docs/Born-Digital-Materials/imaging-and-content-acquisition/). Note: any disk images containing Mac file systems, such as Hierarchical File System  Plus (HFS+), Hierarchical File System (HFS), or Macintosh File System (MFS), cannot be extracted this way. Forward the Digital Archivist the identifier for the item containing those file systems.  

Any processing activities that involve modifying the files in the _DIP in any way must be recorded in the PREMIS Spreadsheet.  

### Troubleshooting Disk Images

Issues with disk images may occur depending on the condition of the original item at the time it was imaged. These issues may include problems such as:  

- Problems mounting the image in FTKImager 
    - Option 1: Use OSFMount or another method of mounting the disk image 
    - Option 2: Re-image the original item 
- Problems with extracting files 
    - Option 1: Use brunnhilde 
    - Option 2: Use tsk_recover 

## Assess Content

As preservation and accessioning actions are completed, they will be recorded in the [PREMIS Spreadsheet](https://elizajames.github.io/digital-preservation-documentation/assets/files/PREMISSpreadsheet.xlsx) and saved within the Administration folder for the accession. The spreadsheet records all preservation actions, or [events](https://www.loc.gov/standards/premis/v3/preservation-events.pdf), in the [PREMIS data model](https://www.loc.gov/standards/premis/v3/preservation-events.pdf), taken on the collection. Events related to the processing process may include: 

- Decryption 
- Deletion 
- Filename change 
- Information package creation 
- Modification 
- Recovery 
- Redaction 
- Replication 
- Unpacking 

Much of the information needed for processing will be taken from the folder containing the report for the media item. The folder is found within the Metadata folder within the Administration folder for a collection. The folder is named with the identifier for the media item and is structured as follows:  

<img src="https://elizajames.github.io/digital-preservation-documentation/assets/images/media_main_manual/image11.png" alt="Preview of the output of brunnhilde">

The relevant files and folders are:  

- report.html 
    - Contains an overview of the content of the media item. 
- bulk_extrator  
    - Contains .txt reports of types of sensitive data and compressed materials in the media item.  
- bulk_extractor\unzip_carved\ 
    - Contains an extract of all files found in .zip folders present on the media item.  

In the bulk_extractor folder, check to see if the unzip_carved.txt and unrar_carved.txt files are present. A brief description of what is in these files is below. 

|       __Bulk_Extractor Scanner Name__  |           __Output__ __File__        |                                                                                                      Description                                                                                                  |
|------------------------------------|:----------------------------:|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|
|     zip                            |   zip.txt, unzip_carved.txt  |   A file containing information regarding every ZIP file component found on the media. Will find zlib-compressed regions.                                                                                         |
|     rar                            |   rar.txt, unrar_carved.txt  |   RAR components in unencrypted archives are decrypted and processed. Encrypted RAR file are carved. RAR is a proprietary archive file format that supports data compression, error recovery and file spanning.   |

If items are present in either text file, go to the original materials on the Z: drive and extract the files from the .zip or .rar folders identified using 7-Zip. Extract the files to the same location, retaining the folder name, and delete the original zipped folder. Make an Unpacking and Deletion event for the items in the [PREMIS Spreadsheet](https://elizajames.github.io/digital-preservation-documentation/assets/files/PREMISSpreadsheet.xlsx), being sure to refer to the specific folder path impacted in the notes.  

Go back to the copy of the files, not the Z: drive originals. For items that have Enhanced or Intensive processing statuses, determine whether the intellectual arrangement of materials warrants moving electronic files into new arrangements for preservation and access. This should occur only in rare circumstances. If weeding is conducted, such as deleting files that have 0 bytes or are "empty", make a Deletion event for the item(s) in the [PREMIS Spreadsheet](https://elizajames.github.io/digital-preservation-documentation/assets/files/PREMISSpreadsheet.xlsx), being sure to refer to the specific folder path and items impacted in the notes as well as the rationale behind the actions. Alternatively, for materials that are moved, create a Modification event in the [PREMIS Spreadsheet](https://elizajames.github.io/digital-preservation-documentation/assets/files/PREMISSpreadsheet.xlsx) and explain in detail the actions taken on the media item, the impacted files and file path, and the rationale behind those actions. 

If any items are to be restricted by donor request, create a Policy Assignment event in the [PREMIS Spreadsheet](https://elizajames.github.io/digital-preservation-documentation/assets/files/PREMISSpreadsheet.xlsx) and explain in detail the actions taken on the media item, the impacted files and file path, and the rationale behind those actions. The Policy Assignment event should discuss the restriction and any relevant expiration dates. 

## Duplicate File Identification

Duplicate files are usually ignored except in specific circumstances. If there is only a small number of duplicate files and the file sizes are small, ignore them. If there are a large number of duplicate files and/or the file sizes are large (in excess of several GB), assess the contextual and informational value of duplicate content within the copy of materials being used for processing to determine if duplicates should be weeded. For files that are derivatives, such as a JPG and TIFF copy of the same item, both copies are typically retained. 

In the Metadata folder for a collection, a list of duplicate files can be found on the Duplicates tab in the report.html file for the item or by opening siegfried.csv in Excel, selecting the md5 column, and selecting __Conditional Formatting__ from the home tab then __Highlight Cells Rules -> Duplicate Values__. 

If weeding is conducted, make a Deletion event for the item(s) in the [PREMIS Spreadsheet](https://elizajames.github.io/digital-preservation-documentation/assets/files/PREMISSpreadsheet.xlsx), being sure to refer to the specific folder path and items impacted in the notes as well as the rationale behind the actions. 

## Identification and Redaction or Deletion of Private and Personally Identifiable Information 

Brunnhilde, the software used as part of the accessioning process, comes bundled with bulk_extractor, a program that identifies personally identifiable information (PII) found in digital files. To determine whether PII is present in the files for a media item, navigate to the  bulk_extractor folder in the folder containing the report for the media item. The folder is found within the Metadata folder within the Administration folder for a collection. 

Examine the Output Files in the below table associated with the accounts and email Bulk_Extractor Scanners. Examine the files ending in _histogram to see the text that potentially matched as possible PII and the files without _histogram to see the files that correspond to the possible PII text. If there are a small number of files that need to be checked or redacted, this may be conducted manually. If there are a large number of files, contact the Digital Archivist with the item’s identifier and move on to the next item.  

|       __Bulk_Extractor Scanner Name__  |                                                          __Output File__                                                      |                                                                                                                  __Description__                                                                                                               |
|------------------------------------|:-------------------------------------------------------------------------------------------------------------------------:|:------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|
|     accounts                       |   telephone.txt, telephone_histogram.txt, ccn.txt, ccn_histogram.txt,  ccn_track2.txt, ccn_track2_histogram.txt, pii.txt  |   Credit card numbers, credit card track 2 information (the magnetic stripe data track read by ATMs and credit card checkers), phone numbers, and other formatted numbers. Useful for tracking how a device's user(s) conducted business.  |
|     email                          |   email.txt, email_histogram.txt                                                                                          |   Discovers email addresses.                                                                                                                                                                                                               |

Confirm through examination that the files contain credit card numbers, bank account numbers, and social security numbers (seen in the CCN reports and PII report) that should be redacted or considered for full restrictions. If files that need to be redacted or restricted are present in the collection, use Teracopy to copy all unredacted or restricted files to a new folder in the Born Digital Content folder named with the identifier for the item followed by _restrictedfiles (see below). Any media item that has restricted or redacted files in a _restrictedfiles folder should have an accompanying .txt file containing the original file path for the item. The main collection folder will contain the redacted versions of the files.  

The technique for redacting for the files depends on the original file type, but for common formats such as PDF, Word, or other text formats, delete the original content to be redacted and replace it with __[REDACTED]__. Create a Modification, Replication, and Policy Assignment event in the [PREMIS Spreadsheet](https://elizajames.github.io/digital-preservation-documentation/assets/files/PREMISSpreadsheet.xlsx) and explain in detail the actions taken on the media item, the impacted files and file path, and the rationale behind those actions. The Policy Assignment event should discuss the restriction and any relevant expiration dates. 

<img src="https://elizajames.github.io/digital-preservation-documentation/assets/images/media_main_manual/image12.png" alt="Sample display of restricted files">

## AIP Creation

If the files for any media items have been modified, including for materials which have only had files extracted from the disk image, run the same Brunnhilde command (seen below) on the content for the media item to output to the Metadata folder using the item identifier followed by _processed.  

Once all materials have been processed, run the following command on the entire folder for the collection, inclusive of the Administration, Born Digital Content, and Digitized Content folders.  

```py
brunnhilde.py - n [input directory, or entire collection folder] [output directory, or Administration folder for the collection]   
```

Save the output in a folder named as the A&M number for the collection followed by _processed in the Metadata folder in the Administration folder for the collection. 

*Future goals: bag and validate these materials using bagit https://github.com/LibraryOfCongress/bagit-python and consider options for file format migration*

## DIP Creation 

Unless there are redacted or restricted materials or files requiring normalization or extraction (for instance, from disk images), the DIP is identical to the AIP and no further actions need to be taken. If separate DIP files were created during the process of processing, they are named with the identifier for the item followed by _DIP (see below). This folder should be in the Born_Digital_Content folder for the collection.  

<img src="https://elizajames.github.io/digital-preservation-documentation/assets/images/media_main_manual/image10.png" alt="Sample display of DIP files">

Before moving on, check off the relevant tasks in the [Born Digital Processing Checklist](https://elizajames.github.io/digital-preservation-documentation/assets/files/BornDigitalProcessingChecklist.docx) for the collection.