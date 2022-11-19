---
layout: default
title: Notes on Adherence to Digital Preservation Standards
parent: Appendices
nav_order: 4
---

# Appendix 4: Notes on Adherence to Digital Preservation Standards
{: .fs-6 .fw-300 }

## On this page
{: .no_toc .text-delta }

1. TOC
{:toc}

The following models and ancillary documents were used to frame the digital preservation program and specific actions within that program: 

- [National Digital Stewardship Alliance Levels of Digital Preservation](https://ndsa.org/publications/levels-of-digital-preservation/) 
- [Digital Preservation Coalition Rapid Assessment Model](https://www.dpconline.org/digipres/dpc-ram) 
- [Reference Model for an Open Archival Information System (OAIS)](https://public.ccsds.org/pubs/650x0m2.pdf) 
- [Audit and Certification of Trustworthy Digital Repositories](https://public.ccsds.org/pubs/652x0m1.pdf)  
- [The Center for Research Libraries Trustworthy Repositories Audit & Certification: Criteria and Checklist](https://www.crl.edu/sites/default/files/d6/attachments/pages/trac_0.pdf)

## National Digital Stewardship Alliance (NDSA) Levels of Digital Preservation 

The [NDSA Levels of Digital Preservation](https://ndsa.org/publications/levels-of-digital-preservation/) is broken down into five functional areas and four levels, with each level indicating specific actions for storage, integrity, control, metadata, and content considerations. Adherence to the levels is indicated by green, yellow, and red highlighted notes. Green indicates adherence, yellow indicates in-progress work toward adherence, and red indicates work toward that item has not yet begun. 

### Level 1 – Know your content 

|       __Functional Area__  |                                                         __Action__                                                     |                                                                                                                                                    __Notes__                                                                                                                                                 |
|------------------------|:------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|
|     Storage            |   Have two complete copies in separate locations                                                                   |   <span style="background-color: # lightgreen">As documented in the Storage & Backups section, backups of the Z: drive are also stored at HSL.</span>                                                                                                                                                                                                        |
|     Storage            |   Document all storage media where content is stored                                                               |   <span style="background-color: # lightgreen">This document outlines the processes for documenting incoming storage media and transmitting content to the Z: drive. Documentation and content is stored on the Z: drive.<span>                                                                                                                             |
|     Storage            |   Put content into a stable storage                                                                                |   Content is extracted from all unstable media where possible in-house; media that cannot be transferred is documented and used to advocate for additional equipment.                                                                                                                                    |
|     Integrity          |   Verify integrity information if it has been provided with the content                                            |   Integrity information will be verified whenever it is provided using Teracopy.                                                                                                                                                                                                                         |
|     Integrity          |   Generate integrity information if not provided with the content                                                  |   Integrity information using md5 checksums is generated for content using siegfried upon accession.                                                                                                                                                                                                     |
|     Integrity          |   Virus check all content; isolate content for quarantine as needed                                                |   All content is scanned using clamAV upon accession, which includes content ingest from storage media. Content flagged is quarantined and monitored by the Digital Archivist before being uploaded to secure storage.                                                                                   |
|     Control            |   Determine the human and software agents that should be authorized to read, write, move, and delete content       |   A permissions document consolidates who has read and write (including move and delete) permissions. The Digital Archivist authorizes the use permissions given to new users.                                                                                                                           |
|     Metadata           |   Create inventory of content, also documenting current storage locations                                          |   Content inventories are stored with content in a metadata folder and generated using siegfried. Storage locations are isolated to a single location: the Z: drive.                                                                                                                                     |
|     Metadata           |   Backup inventory and store at least one copy separately from content                                             |   An inventory of storage media, not necessarily a detailed listing of the files contained on that media (pending processing level), is in ArchivesSpace. A detailed inventory of file-level information is currently not stored separately from content, but options are being examined as of 10/2022.  |
|     Content            |   Document file formats and other essential content characteristics including how and when these were identified   |   File formats and characteristics are generated using siegfried and are stored in a metadata folder with the content. The date is stored as part of the brunnhilde report generated at the same time.                                                                                                   |

### Level 2 – Protector your content 

### Level 3 – Monitor your content 

### Level 4 – Sustain your content 

## Digital Preservation Coalition Rapid Assessment Model 

## Reference Model for an Open Archival Information System (OAIS) 

<img src="https://elizajames.github.io/digital-preservation-documentation/assets/images/media_main_manual/image22.png" alt="Overview of OAIS functional entities">

<img src="https://elizajames.github.io/digital-preservation-documentation/assets/images/media_main_manual/image23.png" alt="OAIS ingest functional entity">

<img src="https://elizajames.github.io/digital-preservation-documentation/assets/images/media_main_manual/image16.png" alt="OAIS archival storage functional entity">

<img src="https://elizajames.github.io/digital-preservation-documentation/assets/images/media_main_manual/image25.png" alt="OAIS data management functional entity">

<img src="https://elizajames.github.io/digital-preservation-documentation/assets/images/media_main_manual/image17.png" alt="OAIS administration functional entity">

<img src="https://elizajames.github.io/digital-preservation-documentation/assets/images/media_main_manual/image18.png" alt="OAIS preservation planning functional entity">

<img src="https://elizajames.github.io/digital-preservation-documentation/assets/images/media_main_manual/image19.png" alt="OAIS access functional entity">

<img src="https://elizajames.github.io/digital-preservation-documentation/assets/images/media_main_manual/image1a.png" alt="OAIS archival information package detailed view">

The above diagram maps to our information package structure, outlined in the Accessioning Media Workflow, used internally as follows:  

Package Description: The information intended for use by Access Aids. 

This is the information uploaded to ArchivesSpace; information may be organized prior to being uploaded to ArchivesSpace using the Born Digital Processing Spreadsheet. 

Packaging Information: The information that is used to bind and identify the components of an Information Package. For example, it may be the ISO 9660 volume and directory information used on a CD-ROM to provide the content of several files containing Content Information and Preservation Description Information. 

This information is initially documented in the Digital Media Inventory Template and expanded in the Brunnhilde report stored in the Metadata folder in the collection folder.  

Content Information: A set of information that is the original target of preservation or that includes part or all of that information. It is an Information Object composed of its Content Data Object and its Representation Information. 

Data Object: Either a Physical Object or a Digital Object. 

This information is stored in the Content folder in the folder containing digital collections content and metadata on the Z: drive.  

Representation Information: The information that maps a Data Object into more meaningful concepts. One example is JPEG software which is used to render a JPEG file. 

Structure Information: The Representation Information that imparts meaning about how other information is organized. 

Documented through description processes or self-documented through strategic file naming where applicable.  

Semantic Information: The Representation Information that further describes the meaning beyond that provided by the Structure Information. 

Documented using Siegfried as part of Brunnhilde for file characterization and stored in the Metadata folder for the collection. 

Preservation Description Information: The information which is necessary for adequate preservation of the Content Information. 

Reference Information: The information that is used as an identifier for the Content Information. 

This information is initially documented at the media item or transfer level in the Digital Media Inventory Template and included in ArchivesSpace;  single files are yet given individual identifiers beyond checksums. 

Provenance Information: The information that documents the history of the Content Information. 

Documented in accession records in ArchivesSpace at the time of transfer of ownership. 

Context Information: The information that documents the relationships of the Content Information to its environment. This includes why the Content Information was created and how it relates to other Content Information objects. 

Documented through processing and description processes and stored in ArchivesSpace. 

Fixity Information: The information which documents the mechanisms that ensure that the Content Information object has not been altered in an undocumented manner. 

Documented through Siegfried as part of Brunnhilde and stored in the Metadata folder for the collection. 

Access Rights Information: The information that identifies the access restrictions pertaining to the Content Information, including the legal framework, licensing terms, and access control. 

Documented in ArchivesSpace as part of processing and description processes.  

As the digital preservation program is fairly new, only a high level overview of OAIS compliance is available. The portion of the OAIS standard related to repository responsibilities will be outlined in the Audit and Certification of Trustworthy Digital Repositories section, currently a work in progress. 

## Audit and Certification of Trustworthy Digital Repositories (future area of work) 

In the future, this section will include an overview of WVRHC adherence to the [Audit and Certification of Trustworthy Digital Repositories (CCSDS 652.0-M-1)](https://public.ccsds.org/Pubs/652x0m1.pdf) set of recommended practices to implement the [Open Archival Information System (OAIS) Reference Model (ISO 14721)](https://public.ccsds.org/pubs/650x0m2.pdf). As a complement to the former document, the [Trustworthy Repositories Audit & Certification: Criteria and Checklist](https://www.crl.edu/sites/default/files/d6/attachments/pages/trac_0.pdf) document by OCLC and The Center for Research Libraries was also used to determine compliance with CCSDS 652.0-M-1. Adherence to these standards will be used as a tool for institutional accountability.   