---
layout: default
title: Description
parent: Audiovisual Materials
nav_order: 3
---

# Description
{: .fs-6 .fw-300 }

## On this page
{: .no_toc .text-delta }

1. TOC
{:toc}

## Introduction

All description will adhere to the Archives & Manuscripts Unit Manual with select extensions and modifications for audiovisual materials outlined below. 

Use the [Audiovisual Media Inventory Spreadsheet](https://elizajames.github.io/digital-preservation-documentation/assets/files/AudiovisualMediaInventoryTemplate.xlsx) to create an archival object in ArchivesSpace for each audiovisual item. The following fields should be used at the item level if applicable. The only mandatory fields are Title and Extent (with subparts): 

|       __Field in ArchivesSpace__         |           __Content Standard__       |                                                              __Example__                                                           |
|--------------------------------------|:--------------------------------:|:------------------------------------------------------------------------------------------------------------------------------:|
|     Title                            |   DACS                           |   Title of item, taken from the item or generated based on the content, such as: Press conference on Energy in Charleston, WV  |
|     Component Unique Identifier      |   Local naming convention        |   Use identifier generated in the [Audiovisual Media Inventory Spreadsheet](https://elizajames.github.io/digital-preservation-documentation/assets/files/AudiovisualMediaInventoryTemplate.xlsx), such as: 4050_vhs_0753                                  |
|     Level of Description             |   EAD                            |   Use the following value: Item                                                                                                |
|     Date (Expression)	                |   DACS                           |   YYYY-MM-DD, YYYY-MM, YYYY, or undated                                                                                        |
|     Date (Label)                     |   ArchivesSpace controlled list  |   Use the following value: Creation                                                                                            |
|     Date (Type)                      |   ArchivesSpace controlled list  |   Use the following value: Single                                                                                              |
|     Extent (Portion)                 |   Numeric value                  |   Use the following value: Whole                                                                                               |
|     Extent (Number)                  |   ArchivesSpace controlled list  |   Input the number of items associated with the archival object                                                                |
|     Extent (Type)                    |   ArchivesSpace controlled list  |   Select the format for the item                                                                                               |
|     Scope and Contents Note          |   DACS                           |   Describe the contents of the item: WVU vs. Clemson football game                                                             |
|     Instance Type                    |   ArchivesSpace controlled list  |   Select from: Moving Images or Audio                                                                                          |
|     Physical Details and Dimensions  |   Local                          |   Additional extent information should be added if prior descriptive information is inadequate                                 |
|     Top Container                    |   Local                          |   Select the correct box number.                                                                                               |

In addition to standard collection descriptive practices, the following audiovisual-specific values should be used at the collection and series levels: 

|       __Name__                         |                               __Notes__                           |                                                                                                                                                                                                                                                __Example__                                                                                                                                                                                                                                             |
|------------------------------------|:-------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|
|     Conditions Governing Access    |   Use where all materials are not digitized                   |   Include the following text: Audiovisual recordings must be digitized for research access. Researchers must contact the West Virginia & Regional History Center reference department at wvrhcref@mail.wvu.edu.                                                                                                                                                                                                                                                                                    |
|     Conditions Governing Access    |   Use where all materials are digitized                       |   Include the following text: Researchers may access digitized audiovisual materials by requesting to view the materials in person by appointment or remotely by contacting the West Virginia & Regional History Center reference department at wvrhcref@mail.wvu.edu.                                                                                                                                                                                                                             |
|     Conditions Governing Access    |   Use where digitization status within a collection is mixed  |   Include the following text: Researchers may access digitized audiovisual materials by requesting to view the materials in person by appointment or remotely by contacting the West Virginia & Regional History Center reference department at wvrhcref@mail.wvu.edu. Materials that are not digitized must be digitized prior to research access. Researchers must contact the West Virginia & Regional History Center reference department at wvrhcref@mail.wvu.edu to request digitization.    |

## Upload to Digital Repository and Link to ArchivesSpace

_Cannot complete the upload portion of this section yet as the digital repository is still in development by Systems Development._ 

_Once an item has been added to the digital repository it must be linked to ArchivesSpace—cannot do this portion of the workflow yet as the digital repository is not operational. Example of process here: [Creating digital objects in ArchivesSpace and Islandora - ArchivesSpace Online Forum 2021](https://www.youtube.com/watch?v=1eX3ryz6TxU&t=2s)_

_Initial ArchivesSpace instructions so that users know what items we have digitized:_ 

For audiovisual materials with digitized versions, create a digital object in ArchivesSpace attached to the existing archival object containing digitized material using the following instructions: 

1. Navigate to the appropriate Resource record for the collection and Archival Object (folder or item).  
2. Click Edit.  
3. Under Instances, click "Add Digital Object." 
4. In the Digital Object tab, click "Create."  
5. In the Digital Object screen, enter the following (bolded fields are mandatory):  
    * __Title__: use the same title as the Archival Object 
    * __Identifier__: Use the file name minus the file extension (e.g., 4050_vhs_001) 
    * __Conditions Governing Access__: Researchers may access digitized audiovisual materials by requesting to view the materials in person by appointment or remotely by contacting the West Virginia & Regional History Center reference department at wvrhcref@mail.wvu.edu. (This is for temporary use until we get a digital repository up and running) 
    * Digital Object Type: choose the appropriate type from the fixed menu 
    * Language: choose the correct language 
    * Date information includes:  
        * Expression, formatted as: YYYY-MM-DD, YYYY-MM, YYYY, undated 
        * Date Type, select: Single 
        * Label, select: Creation 
    * Agent Links: link the appropriate agent and role (usually creator) 
    * *File Versions – TBD, waiting on digital repository, would support thumbnails etc*
6. Click Save. 