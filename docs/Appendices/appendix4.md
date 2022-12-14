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

<table>
<thead>
  <tr>
    <th>Functional Area</th>
    <th>Action </th>
    <th>Notes </th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Storage </td>
    <td>Have two complete copies in separate locations  </td>
    <td style="background-color: #c6f5cc">As documented in the <a href="https://elizajames.github.io/digital-preservation-documentation/docs/Digital-Preservation-Administration/storage-and-backups/">Storage &amp; Backups</a> section, backups of the Z: drive are also stored at HSL.  </td>
  </tr>
  <tr>
    <td>Storage </td>
    <td>Document all storage media where content is stored </td>
    <td style="background-color: #c6f5cc">This document outlines the processes for documenting incoming storage media and transmitting content to the Z: drive. Documentation and content is stored on the Z: drive.  </td>
  </tr>
  <tr>
    <td>Storage </td>
    <td>Put content into a stable storage </td>
    <td style="background-color: #c6f5cc">Content is extracted from all unstable media where possible in-house; media that cannot be transferred is documented and used to advocate for additional equipment.  </td>
  </tr>
  <tr>
    <td>Integrity </td>
    <td>Verify integrity information if it has been provided with the content  </td>
    <td style="background-color: #c6f5cc">Integrity information will be verified whenever it is provided using Teracopy. </td>
  </tr>
  <tr>
    <td>Integrity </td>
    <td>Generate integrity information if not provided with the content </td>
    <td style="background-color: #c6f5cc">Integrity information using md5 checksums is generated for content using siegfried upon accession.  </td>
  </tr>
  <tr>
    <td>Integrity </td>
    <td>Virus check all content; isolate content for quarantine as needed </td>
    <td style="background-color: #c6f5cc">All content is scanned using clamAV upon accession, which includes content ingest from storage media. Content flagged is quarantined and monitored by the Digital Archivist before being uploaded to secure storage.  </td>
  </tr>
  <tr>
    <td>Control </td>
    <td>Determine the human and software agents that should be authorized to read, write, move, and delete content </td>
    <td style="background-color: #c6f5cc">A <a href="https://elizajames.github.io/digital-preservation-documentation/docs/Appendices/appendix2/#permissions-list">permissions document</a> consolidates who has read and write (including move and delete) permissions. The Digital Archivist authorizes the use permissions given to new users.  </td>
  </tr>
  <tr>
    <td>Metadata </td>
    <td>Create inventory of content, also documenting current storage locations </td>
    <td style="background-color: #c6f5cc">Content inventories are stored with content in a metadata folder and generated using siegfried. Storage locations are isolated to a single location: the Z: drive.  </td>
  </tr>
  <tr>
    <td>Metadata </td>
    <td>Backup inventory and store at least one copy separately from content  </td>
    <td style="background-color: lightgoldenrodyellow">An inventory of storage media, not necessarily a detailed listing of the files contained on that media (pending processing level), is in ArchivesSpace. A detailed inventory of file-level information is currently not stored separately from content, but options are being examined as of 10/2022. </td>
  </tr>
  <tr>
    <td>Content </td>
    <td>Document file formats and other essential content characteristics including how and when these were identified  </td>
    <td style="background-color: #c6f5cc">File formats and characteristics are generated using siegfried and are stored in a metadata folder with the content. The date is stored as part of the brunnhilde report generated at the same time.  </td>
  </tr>
</tbody>
</table>

### Level 2 – Protector your content 

<table>
<thead>
  <tr>
    <th>Functional Area </th>
    <th>Action </th>
    <th>Notes </th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Storage </td>
    <td>Have three complete copies with at least one copy in a separate geographic location </td>
    <td style="background-color: lightgoldenrodyellow">Two complete copies are stored at the Downtown Library (see the <a href="https://elizajames.github.io/digital-preservation-documentation/docs/Digital-Preservation-Administration/storage-and-backups/">Storage &amp; Backups section</a>). A third copy is planned to be deployed to Amazon Glacier but is in the planning stages.  </td>
  </tr>
  <tr>
    <td>Storage </td>
    <td>Document storage and storage media indicating the resources and dependencies they require to function </td>
    <td style="background-color: #c6f5cc">Resource and dependency information is maintained by Systems Infrastructure. Changes or issues are conveyed to the Digital Archivist and addressed in tandem. </td>
  </tr>
  <tr>
    <td>Integrity </td>
    <td>Verify integrity information when moving or copying content </td>
    <td style="background-color: #c6f5cc">Integrity information is verified when copying or moving content using Teracopy. A record of the verified checksums is stored in the logs folder for a collection. </td>
  </tr>
  <tr>
    <td>Integrity </td>
    <td>Use write-blockers when working with original media </td>
    <td style="background-color: #c6f5cc">Write blockers are used with media upon content extraction.  </td>
  </tr>
  <tr>
    <td>Integrity </td>
    <td>Back up integrity information and store copy in a separate location from the content </td>
    <td style="background-color: lightgoldenrodyellow">A detailed inventory of file-level information, including integrity information, is currently not stored separately from content. Options for separate storage are being examined as of 10/2022.   </td>
  </tr>
  <tr>
    <td>Control </td>
    <td>Document the human and software agents authorized to read, write, move, and delete content and apply these </td>
    <td style="background-color: #c6f5cc">A  <a href="https://elizajames.github.io/digital-preservation-documentation/docs/Appendices/appendix2/#permissions-list">permissions document</a> consolidates who has read and write (including move and delete) permissions. The Digital Archivist authorizes the use permissions given to new users. </td>
  </tr>
  <tr>
    <td>Metadata </td>
    <td>Store enough metadata to know what the content is (this might include some combination of administrative, technical, descriptive, preservation, and structural) </td>
    <td style="background-color: #c6f5cc">Metadata stored on Z: includes information not only about the files, but also about the media carriers, including technical, preservation, descriptive, and structural metadata. Additional administrative and descriptive metadata is stored in ArchivesSpace.  </td>
  </tr>
  <tr>
    <td>Content </td>
    <td>Verify file formats and other essential content characteristics </td>
    <td style="background-color: lightgoldenrodyellow">File formats are verified and any issues are currently flagged by siegfried. Issues are currently addressed at the time of scheduled access by a user, though options for addressing issues with file formats are currently being explored as part of processing.  </td>
  </tr>
  <tr>
    <td>Content </td>
    <td>Build relationships with content creators to encourage sustainable file choices </td>
    <td style="background-color: #c6f5cc">This document includes a section on preferred file formats for donors. Where possible, discussions with content creators occur prior to transfer and accession using these preferred file formats. </td>
  </tr>
</tbody>
</table>

### Level 3 – Monitor your content 

<table>
<thead>
  <tr>
    <th>Functional Area </th>
    <th>Action </th>
    <th>Notes </th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Storage </td>
    <td>Have at least one copy in a geographic location with a different disaster threat than the other copies </td>
    <td style="background-color: lightgoldenrodyellow">Implementation of Level 2 Storage actions as outlined in the Level 2 table will also meet this Level 3 Storage action. </td>
  </tr>
  <tr>
    <td>Storage </td>
    <td>Have at least one copy on a different storage media type </td>
    <td style="background-color: lightgoldenrodyellow">Implementation of Level 2 Storage actions as outlined in the Level 2 table will also meet this Level 3 Storage action. </td>
  </tr>
  <tr>
    <td>Storage </td>
    <td>Track the obsolescence of storage and media </td>
    <td style="background-color: #c6f5cc">Server hardware migrations and management is maintained by Systems Infrastructure. Changes, such as migrating to new servers and refreshing server hardware, are conveyed to the Digital Archivist and addressed in tandem according to a predetermined schedule. Collections content is extracted from all unstable storage media where possible in-house; media that cannot be transferred is documented and used to advocate for additional equipment. </td>
  </tr>
  <tr>
    <td>Integrity </td>
    <td>Verify integrity information of content at fixed intervals </td>
    <td style="background-color: #FFCCCB">Action will be implemented in the future—currently, collection processing and generation of checksums must occur before verifying integrity information.  </td>
  </tr>
  <tr>
    <td>Integrity </td>
    <td>Document integrity information verification processes and outcomes </td>
    <td style="background-color: #FFCCCB">Action will be implemented in the future—currently, collection processing and generation of checksums must occur before verifying integrity information. </td>
  </tr>
  <tr>
    <td>Integrity </td>
    <td>Perform audit of integrity information on demand </td>
    <td style="background-color: #c6f5cc">Integrity information is verified on demand using Teracopy. A record of the verified checksums is stored in the logs folder for a collection. </td>
  </tr>
  <tr>
    <td>Control </td>
    <td>Maintain logs and identify the human and software agents that performed actions on content </td>
    <td style="background-color: #FFCCCB">Action will be implemented in the future—this information is currently held by Systems Infrastructure. </td>
  </tr>
  <tr>
    <td>Metadata </td>
    <td>Determine what metadata standards to apply  </td>
    <td style="background-color: #c6f5cc">Metadata standards and implementations are outlined in the <a href="https://elizajames.github.io/digital-preservation-documentation/docs/Born-Digital-Materials/description/">Description section</a> for born digital materials in this document. </td>
  </tr>
  <tr>
    <td>Metadata </td>
    <td>Find and fill gaps in your metadata to meet those standards </td>
    <td style="background-color: lightgoldenrodyellow">Currently in progress—legacy processed collections are being reprocessed and new collections processed according to the metadata standards and implementations outlined in the <a href="https://elizajames.github.io/digital-preservation-documentation/docs/Born-Digital-Materials/description/">Description section</a> for born digital materials in this document. </td>
  </tr>
  <tr>
    <td>Content </td>
    <td>Monitor for obsolescence, and changes in technologies on which content is dependent </td>
    <td style="background-color: #FFCCCB">Action will be implemented in the future. </td>
  </tr>
</tbody>
</table>

### Level 4 – Sustain your content 

<table>
<thead>
  <tr>
    <th>Functional Area </th>
    <th>Action </th>
    <th>Notes </th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Storage </td>
    <td>Have at least three copies in geographic locations, each with a different disaster threat </td>
    <td style="background-color: #FFCCCB">Implementation toward Level 2 and Level 3 Storage actions will occur before Level 4. </td>
  </tr>
  <tr>
    <td>Storage </td>
    <td>Maximize storage diversification to avoid single points of failure </td>
    <td style="background-color: #FFCCCB">Implementation toward Level 2 and Level 3 Storage actions will occur before Level 4. </td>
  </tr>
  <tr>
    <td>Storage </td>
    <td>Have a plan and execute actions to address obsolescence of storage hardware, software, and media </td>
    <td style="background-color: #c6f5cc">Server hardware migrations and management is maintained by Systems Infrastructure. Changes, such as migrating to new servers and refreshing server hardware, are conveyed to the Digital Archivist and addressed in tandem according to a predetermined schedule. Collections content is extracted from all unstable storage media where possible in-house; media that cannot be transferred is documented and used to advocate for additional equipment.  </td>
  </tr>
  <tr>
    <td>Integrity </td>
    <td>Verify integrity information in response to specific events or activities </td>
    <td style="background-color: #c6f5cc">Integrity information is verified on demand using Teracopy. A record of the verified checksums is stored in the logs folder for a collection. </td>
  </tr>
  <tr>
    <td>Integrity </td>
    <td>Replace or repair corrupted content as necessary </td>
    <td style="background-color: #FFCCCB">Action will be implemented in the future. </td>
  </tr>
  <tr>
    <td>Control </td>
    <td>Perform periodic review of actions/access logs  </td>
    <td style="background-color: #FFCCCB">Action will be implemented in the future.  </td>
  </tr>
  <tr>
    <td>Metadata </td>
    <td>Record preservation actions associated with content and when those actions occur </td>
    <td style="background-color: #c6f5cc">Preservation actions are documented in the <a href="https://elizajames.github.io/digital-preservation-documentation/assets/files/PREMISSpreadsheet.xlsx">PREMIS Spreadsheet</a> for a collection, stored in the administration folder for that collection.  </td>
  </tr>
  <tr>
    <td>Metadata </td>
    <td>Implement metadata standards chosen </td>
    <td style="background-color: #c6f5cc">Metadata standards and implementations are outlined in the <a href="https://elizajames.github.io/digital-preservation-documentation/docs/Born-Digital-Materials/description/">Description section</a> for born digital materials in this document.  </td>
  </tr>
  <tr>
    <td>Content </td>
    <td>Perform migrations, normalizations, emulation, and similar activities that ensure content can be accessed </td>
    <td style="background-color: #c6f5cc">Migrations, normalizations, emulations, and similar activities are primarily addressed at the time of scheduled access by a user. Typically, original files are retained to minimize irreversible interventions and support changing standards in providing access to file formats. </td>
  </tr>
</tbody>
</table>

## Digital Preservation Coalition Rapid Assessment Model 

While the NDSA Levels of Digital Preservation outlines specific actions, it does not include organizational and service characteristics of an archive. In [DPC RAM](https://www.dpconline.org/digipres/dpc-ram), a digital preservation program has organizational and service capabilities that are assessed at the following levels: minimal awareness, awareness, basic, managed, and optimized.  

The below table outlines steps to get to the subsequent level as progress toward the desired level. These steps will be incorporated into the WVRHC Digital Preservation Strategic Priorities document. The first instance of this document will be created in 2023.  

<table>
<thead>
  <tr>
    <th>Organizational Capabilities </th>
    <th></th>
    <th></th>
    <th></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td></td>
    <td><b>Current Level</b></td>
    <td><b>Desired Level</b></td>
    <td><b>Steps to Get to Desired Level</b></td>
  </tr>
  <tr>
    <td>A. Organizational viability: Governance, organizational structure, staffing and resourcing of digital preservation activities. </td>
    <td>Awareness</td>
    <td>Optimized</td>
    <td>
        <ol>
        <li>Awareness-&gt;Basic</li>
            <ul>
                <li>To do: Demonstrate some engagement by administration.</li>
                <li>To do: Ensure staff have assigned responsibilities and the time to undertake them.</li>
                <li>To do: Allocate a budget for digital preservation.</li> 
                <li>To do: Identify staff development requirements.</li>
            </ul>
        <li>Basic-&gt;Managed</li>
            <ul>
                <li>Will be outlined once a Basic level is achieved.</li>
            </ul>
        <li>Managed-&gt;Optimized</li>
            <ul>
                <li>Will be outlined once a Managed level is achieved.</li>
            </ul>
        </ol>
    </td>
  </tr>
  <tr>
    <td>B. Policy and strategy: Policies, strategies, and procedures which govern the operation and management of the digital archive. </td>
    <td> Basic</td>
    <td>Optimized</td>
    <td>
        <ol>
            <li>Basic-&gt;Managed</li>
                <ul>
                    <li>Completed: A digital preservation policy is aligned to organizational policies and is reviewed on an agreed upon schedule.</li>  
                    <li>Completed: A suite of documented processes and procedures for managing, and providing access to, content within the digital archive exists.</li>
                    <li>To do (in progress): Policy and procedure takes into account any relevant ethical issues.</li>  
                    <li>To do (in progress): All relevant staff are aware of digital preservation policies, strategies, and procedures.</li> 
                    <li>To do (in progress): Knowledge of current and future use cases for content informs policy and procedure (for example on collecting, preservation approaches, metadata and access).</li>
                </ul>  
            <li>Managed-&gt;Optimized</li>
                <ul>
                    <li>Will be outlined once a Managed level is achieved.</li>
                </ul> 
        </ol>
    </td>
  </tr>
  <tr>
    <td>C. Legal basis: Management of legal rights and responsibilities, compliance with relevant regulation and adherence to ethical codes related to acquiring, preserving and providing access to digital content. </td>
    <td> Awareness</td>
    <td>Optimized</td>
    <td>
        <ol>
            <li>Awareness-&gt;Basic</li>
                <ul>
                    <li>To do: Key legal rights and responsibilities, together with their owners, have been identified and documented.</li>  
                    <li>To do: Templates exist for necessary legal agreements and licenses.</li>
                    <li>To do: Relevant codes of conduct related to professional ethics are adhered to.</li>
                </ul>
            <li>Basic-&gt;Managed</li>
                <ul>
                    <li>Will be outlined once a Basic level is achieved.</li>
                </ul>
            <li>Managed-&gt;Optimized</li>
                <ul>
                    <li>Will be outlined once a Managed level is achieved.</li>
                </ul> 
        </ol>
    </td>
  </tr>
  <tr>
    <td>D. IT capability: Information Technology capabilities for supporting digital preservation activities.</td>
    <td> Basic</td>
    <td>Managed</td>
    <td>
    <ol>
        <li>Basic-&gt;Managed</li>
            <ul>
                <li>Completed (by Systems Infrastructure, Systems Development, and the Digital Archivist where applicable): IT systems are regularly patched and updated.</li>
                <li>Completed (current practice, processes can be improved): New tools and systems are deployed when required.</li>
                <li>To do: Adequate IT support is available to the digital archive.</li>
                <li>To do: IT roles and responsibilities are documented and regularly reviewed.</li>
                <li>To do (done via this manual for software and some systems, needs improvement): IT systems are comprehensively documented.</li>
                <li>To do: contracts and services with third party service providers are well managed and documented.</li>
            </ul>
        <li>Managed-&gt;Optimized</li>
            <ul>
                <li>Will be outlined once a Managed level is achieved.</li>
            </ul>
    </ol> 
    </td>
  </tr>
  <tr>
    <td>E. Continuous Improvement: Processes for the assessment of current digital preservation capabilities, the definition of goals and the monitoring of progress </td>
    <td>Awareness</td>
    <td>Optimized</td>
    <td>
        <ol>
            <li>Awareness-&gt;Basic</li>
                <ul>
                    <li>To do: An initial benchmarking exercise has been carried out.</li>
                    <li>To do: Gaps in digital preservation capability have been identified.</li>
                    <li>To do: There is an understanding of where the organization is relative to peers.</li>
                </ul>
        <li>Basic-&gt;Managed</li>
            <ul>
                <li>Will be outlined once a Basic level is achieved.</li>
            </ul>
        <li>Managed-&gt;Optimized</li>
            <ul>
                <li>Will be outlined once a Managed level is achieved.</li>
            </ul>
        </ol>
    </td>
  </tr>
  <tr>
    <td>F. Community: Engagement with and contribution to the wider digital preservation community. </td>
    <td> Awareness</td>
    <td>Managed</td>
    <td>
        <ol>
            <li>Awareness-&gt;Basic</li>
                <ul>
                    <li>To do: Networks of relevant contacts have been established.</li>
                    <li>To do: Relevant community events can be accessed.</li>
                    <li>To do: There is commitment to learn from the experience of others.</li>
                </ul>
            <li>Basic-&gt;Managed</li> 
                <ul>
                    <li>Will be outlined once a Basic level is achieved.</li>
                </ul> 
            <li>Managed-&gt;Optimized</li> 
                <ul>
                    <li>Will be outlined once a Managed level is achieved.</li>
                </ul>
        </ol>
    </td>
  </tr>
  <tr>
    <td><b>Service Capabilities</b></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>  </td>
    <td><b>Current Level</b></td>
    <td><b>Desired Level</b></td>
    <td><b>Steps to Get to Desired Level</b></td>
  </tr>
  <tr>
    <td>G. Acquisition, Transfer and Ingest: Processes to acquire or transfer content and ingest it into a digital archive. </td>
    <td> Awareness</td>
    <td>Optimized</td>
    <td>
        <ol>
            <li>Awareness-&gt;Basic</li> 
                <ul>
                    <li>Completed (this document): A documented ingest process exists.</li>
                    <li>Completed (this and ingest document): Basic guidance for donors, depositors, and record creators is available where appropriate.</li>  
                    <li>Completed (this and ingest document): Documentation and metadata is sometimes received or captured as part of the acquisition or transfer process.</li>  
                    <li>Completed (accession portion of this document): Some content is appraised as part of a manual process in line with relevant policies.</li>  
                    <li>To do: A documented process exists for selecting and capturing digital content where appropriate (for example, web archives, email archives, digitized content, etc.)</li> 
                    <li>To do (in progress, 10/2022): A working area (physical or virtual) is available for pre-ingest and ingest activities.</li> 
                </ul> 
            <li>Basic-&gt;Managed</li> 
                <ul>
                    <li>Will be outlined once a Basic level is achieved.</li>
                </ul> 
            <li>Managed-&gt;Optimized</li> 
                <ul>
                    <li>Will be outlined once a Managed level is achieved.</li>
                </ul> 
        </ol>
    </td>
  </tr>
  <tr>
    <td>H. Bitstream Preservation: Processes to ensure the storage and integrity of digital content to be preserved.</td>
    <td>Awareness</td>
    <td>Optimized</td>
    <td>
        <ol>
            <li>Awareness-&gt;Basic</li>
                <ul>
                    <li>Completed (see this manual): Dedicated storage is available to meet current preservation needs.</li>  
                    <li>Completed (see this manual): Staff know where content is stored.</li>  
                    <li>Completed (see this manual): Replication is based on simple backup regimes.</li>    
                    <li>Completed (see permissions document): There is an understanding of which staff members should be authorized to access the content.</li>  
                    <li>To do (in progress, procedures completed): Checksums are generated for all content.</li> 
                </ul>
            <li>Basic-&gt;Managed</li> 
                <ul>
                    <li>Will be outlined once a Basic level is achieved.</li>
                </ul>  
            <li>Managed-&gt;Optimized</li> 
                <ul>
                    <li>Will be outlined once a Managed level is achieved.</li>
                </ul> 
        </ol>
    </td>
  </tr>
  <tr>
    <td>I. Content Preservation: Processes to preserve the meaning or functionality of the digital content and ensure its continued accessibility and usability over time.</td>
    <td>Awareness</td>
    <td>Optimized</td>
    <td>
        <ol>
        <li>Awareness-&gt;Basic</li>
            <ul>
                <li>To do (in progress, procedures completed): File formats are identified.</li>
                <li>To do (in progress, procedures completed): Content is characterized and assessed for preservation and quality issues such as encrypted, broken, or incomplete content and invalid files.</li>
                <li>To do: There is a basic understanding of current and future users and use cases for the content.</li>
            </ul>
        <li>Basic-&gt;Managed</li>
            <ul>
                <li>Will be outlined once a Basic level is achieved.</li>
            </ul>
        <li>Managed-&gt;Optimized</li>
            <ul>
                <li>Will be outlined once a Managed level is achieved.</li>
            </ul>
        </ol>
    </td>
  </tr>
  <tr>
    <td>J. Metadata Management: Processes to create and maintain sufficient metadata to support preservation, discovery and use of preserved digital content. </td>
    <td>Awareness</td>
    <td>Optimized</td>
    <td>
        <ol>
            <li>Awareness-&gt;Basic</li>
                <ul>
                    <li>Completed (this document): An appropriate minimum descriptive metadata requirement exists.</li>
                    <li>Completed (this document): Metadata and documentation acquired with content is retained and preserved.</li>
                    <li>To do (in progress, procedures created): Content is described at collection level in a digital asset register.</li>
                    <li>To do (in progress, procedures created): Basic preservation metadata is captured at item level.</li>
                </ul>
            <li>Basic-&gt;Managed</li>
                <ul>
                <li>Will be outlined once a Basic level is achieved.</li>
                </ul>
            <li>Managed-&gt;Optimized</li>
                <ul>
                <li>Will be outlined once a Managed level is achieved.</li>
                </ul>
        </ol>
    </td>
  </tr>
  <tr>
    <td>K. Discovery and Access: Processes to enable discovery of digital content and provide access for users. </td>
    <td>Awareness</td>
    <td>Optimized</td>
    <td>
        <ol>
            <li>Awareness-&gt;Basic</li>
                <ul>
                <li>Completed: Basic resource discovery exists for some digital content.</li>
                <li>Completed: Users can view or access digital content and metadata either remotely or on-site.</li>
                <li>To do: Users’ access to digital content is recorded.</li>
                <li>To do (in progress, procedures created): Information on the accessibility of digital content is provided to users.</li>
                </ul>
            <li>Basic-&gt;Managed</li>
                <ul>
                <li>Will be outlined once a Basic level is achieved.</li>
                </ul>
            <li>Managed-&gt;Optimized</li>
                <ul>
                <li>Will be outlined once a Managed level is achieved.</li>
                </ul>
        </ol>
    </td>
  </tr>
</tbody>
</table>
<br>

## Reference Model for an Open Archival Information System (OAIS) 

To demonstrate OAIS compliance, it is critical to directly map our workflows to the functional entities and archival information package (AIP) as outlined in OAIS. Figures in this section are taken directly from the [Reference Model for an Open Archival Information System (OAIS)](https://public.ccsds.org/pubs/650x0m2.pdf). David Giaretta has also [written and created visualizations](https://wiki.dpconline.org/index.php?title=Visualizing_OAIS) that link the discrete functional entities outlined below together in a way that is helpful for envisioning OAIS as a whole system. Images of the functional entity or package overview will come before a description of WVRHC adherence. Italicized areas are areas of improvement to meet OAIS standards. 

<img src="https://elizajames.github.io/digital-preservation-documentation/assets/images/media_main_manual/image22.png" alt="Overview of OAIS functional entities">

Figure 4-1 has been included to demonstrate a simplified visual representation of how figures 4-2, 4-3, 4-4, 4-5, 4-6, and 4-7 link together.  

<img src="https://elizajames.github.io/digital-preservation-documentation/assets/images/media_main_manual/image23.png" alt="OAIS ingest functional entity">

The Ingest functional entity concerns actions related to formally accepting Submission Information Packages (SIPs) and generating Archival Information Packages (AIPs). Broadly, these areas map to the accession, appraisal, processing, and description portions of the born digital archival processing cycle outlined in this manual. Below is a detailed mapping of actions taken to adhere to these OAIS areas.  

- Receive SIPs 
    - Documented in [Imaging and Born Digital Content Acquisition Procedures](https://elizajames.github.io/digital-preservation-documentation/docs/Born-Digital-Materials/imaging-and-content-acquisition/). 
- Quality assurance on SIPs 
    - _Still establishing documentation for well-formed SIPs; currently SIPs are accepted as a simple file transfer of zipped materials to maintain as much file metadata as possible with minimal donor expertise required._ 
- Generate compliant AIP 
    - Documented in [Processing workflow](https://elizajames.github.io/digital-preservation-documentation/docs/Born-Digital-Materials/processing/). 
- Extract descriptive information from AIP 
    - Documented in [Description workflow](https://elizajames.github.io/digital-preservation-documentation/docs/Born-Digital-Materials/description/). 
- Update information and content in Archival Storage and Data Management 
    - Documented in ArchivesSpace and in the [Digital Media Inventory Template](https://elizajames.github.io/digital-preservation-documentation/assets/files/DigitalMediaInventoryTemplate.xlsx) and [PREMIS Spreadsheet](https://elizajames.github.io/digital-preservation-documentation/assets/files/PREMISSpreadsheet.xlsx) for all media item and digital transfer SIPs. 

<img src="https://elizajames.github.io/digital-preservation-documentation/assets/images/media_main_manual/image16.png" alt="OAIS archival storage functional entity">

The Archival Storage functional entity concerns actions related to storage, maintenance of content and storage infrastructure, and retrieval of AIPs. Broadly, these areas map to the access portion of the born digital archival processing cycle and the Digital Preservation Administration section in this manual. Below is a detailed mapping of actions taken to adhere to these OAIS areas. 

- Receive AIPs from the Ingest entity 
    - AIPs are not auto-generated but are created by a SIP undergoing the [Processing workflow](https://elizajames.github.io/digital-preservation-documentation/docs/Born-Digital-Materials/processing/). 
- Add the AIP to permanent storage 
    - SIPs and AIPs are automatically added to permanent storage.   
- Managing the storage hierarchy 
    - Conducted as part of [Digital Preservation Administration processes](https://elizajames.github.io/digital-preservation-documentation/digital-preservation-administration). 
- Refreshing the media on which AIPs are stored 
    - Conducted as part of [Digital Preservation Administration processes](https://elizajames.github.io/digital-preservation-documentation/digital-preservation-administration) in conjunction with Systems Infrastructure. 
- Performing routine and special error checking 
    - Routine error checking is conducted annually as part of [Digital Preservation Administration processes](https://elizajames.github.io/digital-preservation-documentation/digital-preservation-administration). 
- Providing disaster recovery capabilities 
    - Conducted as part of [Digital Preservation Administration processes](https://elizajames.github.io/digital-preservation-documentation/digital-preservation-administration) in conjunction with Systems Infrastructure.  
- Providing AIPs to the Access entity 
    - Completed as part of the [Access workflow](https://elizajames.github.io/digital-preservation-documentation/docs/Born-Digital-Materials/access/). 

<img src="https://elizajames.github.io/digital-preservation-documentation/assets/images/media_main_manual/image25.png" alt="OAIS data management functional entity">

The Data Management functional entity concerns actions related to populating, maintaining, and accessing Descriptive Information which identifies and documents Archive holdings and administrative data used to manage the archive. Broadly, these areas map to the accession, appraisal, processing, and description portions of the born digital archival processing cycle and the Digital Preservation Administration section in this manual. Below is a detailed mapping of actions taken to adhere to these OAIS areas. 

- Administering the Archive database functions (maintaining schema and view definitions, and referential integrity) 
    - Completed by the Digital Archivist as part of the annual review process for this document. 
- Performing database updates (loading new descriptive information or Archive administrative data) 
    - Completed by the Digital Archivist or designated processor as part of the [Processing workflow](https://elizajames.github.io/digital-preservation-documentation/docs/Born-Digital-Materials/processing/). 
- Performing queries on the data management data to generate query responses 
    - Completed by the Digital Archivist in response to requests/needs using ArchivesSpace and other structured data generated as part of the full born digital workflow. 
- Producing reports from these query responses 
    - Completed by the Digital Archivist in response to requests/needs using ArchivesSpace and other structured data generated as part of the full born digital workflow. 

<img src="https://elizajames.github.io/digital-preservation-documentation/assets/images/media_main_manual/image17.png" alt="OAIS administration functional entity">

The Administration functional entity concerns actions related to providing the services and functions for the overall operation of the archive system. Broadly, these areas map to the accession and access portions of the born digital archival processing cycle and the Digital Preservation Administration section in this manual. Below is a detailed mapping of actions taken to adhere to these OAIS areas. 

- Soliciting and negotiating submission agreements with producers/donors 
    - Conducted as part of the pre-accessioning process.  
- Auditing submissions to ensure that they meet Archive standards 
    - _Still establishing documentation for well-formed SIPs; currently SIPs are accepted as a simple file transfer of zipped materials to maintain as much file metadata as possible with minimal donor expertise required._
    - Submissions are audited at the point of Accession and Appraised for whether they merit inclusion in the archive.  
- Maintaining configuration management of system hardware and software 
    - Completed in coordination with Systems Infrastructure by the Digital Archivist.  
- System engineering functions to monitor and improve Archive operations 
    - Completed by the Digital Archivist and, in terms of hardware, by the Digital Archivist in coordination with Systems Infrastructure. 
- To inventory, report on, and migrate/update the contents of the Archive 
    - Completed by the Digital Archivist in coordination with relevant WVRHC employees.  
- Establishing and maintaining Archive standards and policies 
    - Completed by the Digital Archivist in coordination with other WVRHC employees as needed. 
- Providing customer support 
    - Completed by the Digital Archivist or authorized person.  
- Activating stored requests 
    - Completed by the Digital Archivist or authorized person.  

<img src="https://elizajames.github.io/digital-preservation-documentation/assets/images/media_main_manual/image18.png" alt="OAIS preservation planning functional entity">

The Preservation Planning functional entity concerns actions related to monitoring the environment of the OAIS, providing recommendations and preservation plans to ensure that the information stored in the OAIS remains accessible to, and understandable by, the Designated Community over time. Broadly, these areas map to the processing portions of the born digital archival processing cycle and the Digital Preservation Administration section in this manual. Below is a detailed mapping of actions taken to adhere to these OAIS areas.  

- Evaluating the contents of the archive and periodically recommending archival information updates 
    - Accomplished by Digital Archivist as part of daily work.  
- Recommending the migration of current archive holdings 
    - For file formats: accomplished by the Digital Archivist in response to changing needs. For hardware: accomplished by Systems Infrastructure in coordination with the Digital Archivist.  
- Developing recommendations for Archive standards and policies 
    - Accomplished by the Digital Archivist in coordination with relevant WVRHC employees.  
- Providing periodic risk analysis reports 
    - Accomplished by the Digital Archivist as part of [Digital Preservation Administration](https://elizajames.github.io/digital-preservation-documentation/digital-preservation-administration) processes. 
- Monitoring changes in the technology environment and in the Designated Community’s service requirements and knowledge 
    - Technology environment is actively monitored by the Digital Archivist, additional work needs to be done on articulating the Designated Community’s needs and knowledge.  
- Designs Information Package templates and provides design assistance and review to specialize these templates into SIPs and AIPs for specific submissions 
    - Accomplished by the Digital Archivist and documented in this manual and ancillary documentation.  
- Develops detailed Migration plans, software prototypes and test plans to enable implementation of Administration migration goals 
    - Instigated by the Digital Archivist in coordination with Systems Development, Systems Infrastructure, and relevant WVRHC employees.  

<img src="https://elizajames.github.io/digital-preservation-documentation/assets/images/media_main_manual/image19.png" alt="OAIS access functional entity">

The Access functional entity concerns actions related to providing the services and functions that support users/consumers in determining the existence, description, location and availability of information stored in the OAIS, and allowing users/consumers to request and receive information products. Broadly, these areas map to the processing, description, and access portions of the born digital archival processing cycle. Below is a detailed mapping of actions taken to adhere to these OAIS areas.  

- Communicating with users/consumers to receive requests 
    - Accomplished by Reference Staff or the Digital Archivist as part of standard processes outlined in Access procedures within each section of this document.  
- Applying controls to limit access to specially protected information 
    - Accomplished as part of [Processing procedures](https://elizajames.github.io/digital-preservation-documentation/docs/Born-Digital-Materials/processing/).  
- Coordinating the execution of requests to successful completion 
    - Accomplished by Reference Staff or the Digital Archivist as part of standard processes outlined in Access procedures within each section of this document. 
- Generating responses (Dissemination Information Packages, query responses, reports) and delivering the responses to users/consumers 
    - Accomplished by the Digital Archivist as part of standard processes outlined in Access procedures within each section of this document. Access copies are generated based upon the type of AIP. 

In addition to the above functional entities, the information objects and packages must include the following aspects and information

<img src="https://elizajames.github.io/digital-preservation-documentation/assets/images/media_main_manual/image1a.png" alt="OAIS archival information package detailed view">

The above diagram maps to our information package structure, outlined in the [Accessioning Media Workflow](https://elizajames.github.io/digital-preservation-documentation/docs/Born-Digital-Materials/accessioning/), used internally as follows:  

- __Package Description:__ The information intended for use by Access Aids. 
    - This is the information uploaded to ArchivesSpace; information may be organized prior to being uploaded to ArchivesSpace using the [Born Digital Processing Checklist](https://elizajames.github.io/digital-preservation-documentation/assets/files/BornDigitalProcessingChecklist.docx). 
- __Packaging Information:__ The information that is used to bind and identify the components of an Information Package. For example, it may be the ISO 9660 volume and directory information used on a CD-ROM to provide the content of several files containing Content Information and Preservation Description Information. 
    - This information is initially documented in the [Digital Media Inventory Template](https://elizajames.github.io/digital-preservation-documentation/assets/files/DigitalMediaInventoryTemplate.xlsx)  and expanded in the Brunnhilde report stored in the Metadata folder in the collection folder.  
- __Content Information:__ A set of information that is the original target of preservation or that includes part or all of that information. It is an Information Object composed of its Content Data Object and its Representation Information. 
    - __Data Object:__ Either a Physical Object or a Digital Object. 
        - This information is stored in the Content folder in the folder containing digital collections content and metadata on the Z: drive.  
    - __Representation Information:__ The information that maps a Data Object into more meaningful concepts. One example is JPEG software which is used to render a JPEG file. 
        - __Structure Information:__ The Representation Information that imparts meaning about how other information is organized. 
            - Documented through description processes or self-documented through strategic file naming where applicable.  
        - __Semantic Information:__ The Representation Information that further describes the meaning beyond that provided by the Structure Information. 
            - Documented using Siegfried as part of Brunnhilde for file characterization and stored in the Metadata folder for the collection. 
- __Preservation Description Information:__ The information which is necessary for adequate preservation of the Content Information. 
    - __Reference Information:__ The information that is used as an identifier for the Content Information. 
        - This information is initially documented at the media item or transfer level in the [Digital Media Inventory Template](https://elizajames.github.io/digital-preservation-documentation/assets/files/DigitalMediaInventoryTemplate.xlsx)  and included in ArchivesSpace;  single files are yet given individual identifiers beyond checksums. 
    - __Provenance Information:__ The information that documents the history of the Content Information. 
        - Documented in accession records in ArchivesSpace at the time of transfer of ownership. 
    - __Context Information:__ The information that documents the relationships of the Content Information to its environment. This includes why the Content Information was created and how it relates to other Content Information objects. 
        - Documented through processing and description processes and stored in ArchivesSpace. 
    - __Fixity Information:__ The information which documents the mechanisms that ensure that the Content Information object has not been altered in an undocumented manner. 
        - Documented through Siegfried as part of Brunnhilde and stored in the Metadata folder for the collection. 
    - __Access Rights Information:__ The information that identifies the access restrictions pertaining to the Content Information, including the legal framework, licensing terms, and access control. 
        - Documented in ArchivesSpace as part of processing and description processes.  

As the digital preservation program is fairly new, only a high level overview of OAIS compliance is available. The portion of the OAIS standard related to repository responsibilities will be outlined in the [Audit and Certification of Trustworthy Digital Repositories](https://elizajames.github.io/digital-preservation-documentation/docs/Appendices/appendix4/#audit-and-certification-of-trustworthy-digital-repositories-future-area-of-work) section, currently a work in progress. 

## Audit and Certification of Trustworthy Digital Repositories (future area of work) 

In the future, this section will include an overview of WVRHC adherence to the [Audit and Certification of Trustworthy Digital Repositories (CCSDS 652.0-M-1)](https://public.ccsds.org/Pubs/652x0m1.pdf) set of recommended practices to implement the [Open Archival Information System (OAIS) Reference Model (ISO 14721)](https://public.ccsds.org/pubs/650x0m2.pdf). As a complement to the former document, the [Trustworthy Repositories Audit & Certification: Criteria and Checklist](https://www.crl.edu/sites/default/files/d6/attachments/pages/trac_0.pdf) document by OCLC and The Center for Research Libraries was also used to determine compliance with CCSDS 652.0-M-1. Adherence to these standards will be used as a tool for institutional accountability.   