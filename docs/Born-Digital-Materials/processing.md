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

To extract the content, follow the FTK Imager instructions for Extracting Content from a Disk Image or Media Item in the [Imaging and Born Digital Content Acquisition Procedures document](https://elizajames.github.io/digital-preservation-documentation/assets/files/ImagingAndBornDigitalContentAcquisitionProcedures.docx). Note: any disk images containing Mac file systems, such as Hierarchical File System  Plus (HFS+), Hierarchical File System (HFS), or Macintosh File System (MFS), cannot be extracted this way. Forward the Digital Archivist the identifier for the item containing those file systems.  

Any processing activities that involve modifying the files in the _DIP in any way must be recorded in the PREMIS Spreadsheet.  