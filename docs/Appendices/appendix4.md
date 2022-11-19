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