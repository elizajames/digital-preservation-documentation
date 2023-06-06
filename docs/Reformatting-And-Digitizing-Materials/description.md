---
layout: default
title: Description
parent: Reformatting and Digitizing Materials
nav_order: 4
---

# Description

For items that are going to be made publicly available and uploaded to the relevant section of WVU Digital Collections, metadata is assigned according to the metadata profile in [Appendix 3](https://elizajames.github.io/digital-preservation-documentation/docs/Appendices/appendix3/). Description may be completed at the item, folder, or collection level as determined by the [Digitization Project Planning document](https://elizajames.github.io/digital-preservation-documentation/assets/files/DigitizationPlanningForm.docx) for the collection being digitized. Metadata may be input directly into the WVRHC digital repository or, in the case of collections where materials may benefit from batch uploading, can be input into the [Digital Repository Metadata Spreadsheet](https://elizajames.github.io/digital-preservation-documentation/assets/files/Digital_Repository_Metadata_Template.xlsx).----

For items that are going to be made publicly accessible through description in ArchivesSpace----- 

If an item is only being digitized for a reference request or are not being uploaded to the digital repository because of various restrictions, follow the----

## Upload to Digital Repository

_Cannot complete the upload portion of this section yet as the replacement digital repository is still in development by Systems Development._ 

_Relevant sections: metadata in [Appendix 3](https://elizajames.github.io/digital-preservation-documentation/docs/Appendices/appendix3/)_ 

_Once an item has been added to the digital repository it must be linked to ArchivesSpace as documented in the subsequen section—cannot do this portion of the workflow yet as the digital repository is not operational. Example of process here:  [Creating digital objects in ArchivesSpace and Islandora - ArchivesSpace Online Forum 2021](https://www.youtube.com/watch?v=1eX3ryz6TxU&t=2s)_

## Create Digital Objects in ArchivesSpace for Digitized Content

### Intro 

Creating Digital Objects in ArchivesSpace requires making descriptive choices based on the digitized materials you are trying to describe and how in-depth the source collection for a set of digitized materials is processed. 

Within ArchivesSpace, Digital Objects can be complex and have multiple levels. This means that you can, if desired, create a Digital Object representing a box that also contains folders that in turn contain items, though typically this level of detail is not desired. 

For instance, if you have digitized an entire collection consisting of ten items and there are no Archival Objects on the Resource Record that describes each item individually, you likely want to describe the digitized materials in a single Digital Object rather than ten Digital Objects for ease of use. If the Resource Record is incredibly detailed and contains folder level description, you likely want to mirror this description in your Digital Object. When making your choices, be sure to make a decision that will be replicable should additional materials from the collection be digitized later on. 

### Example Digital Object Records 

- Materials on Server: 
   - Simple object for an entire collection consisting of one letter that has been digitized: [Achilles Dew, Letter to President Lincoln](https://archives.lib.wvu.edu/repositories/2/digital_objects/2188)
   - Simple object for the entirety of a box of materials (item level description in Resource Record): [Andrew C. Lyons, Architect, Drawings for Buildings in Fairmont, West Virginia, Box 17](https://archives.lib.wvu.edu/repositories/2/digital_objects/2410)
   - Complex object for 19 cassettes with file names serving as titles for digital object subcomponents to minimize manual description: [Cassette Sound Recordings of Knotts' Autobiography](https://archives.lib.wvu.edu/repositories/2/digital_objects/2643)
- Materials in MFCS: 
   - Simple object for materials from many source locations: [Photographs from Frances Packette Todd Papers](https://archives.lib.wvu.edu/repositories/2/digital_objects/227)

### Digital Object Instructions

__Note:__ If you want to create a Digital Object with more than one level of description, use the bulk importer or create the Digital Object using the instructions below and go back and edit and add the additional levels of description.

For audiovisual materials with digitized versions, create a digital object in ArchivesSpace attached to the existing archival object containing digitized material using the following instructions: 

1. Navigate to the appropriate Resource record for the collection or Archival Object for folder or item as relevant. 
2. Click Edit.  
3. Under Instances, click "Add Digital Object." 
4. In the Digital Object tab, click "Create."  
5. In the Digital Object screen, enter the following (bolded fields are mandatory):  
    * __Title__: use the same title as the Archival Object or Collection or generate a short title indicative of what has been digitized.
    * __Identifier__: Use the folder name for the identifier (e.g., 4050_vhs_001).  
      * If you have consolidated several similar items, either consolidate the identifier as 4050_vhs_001-010 (read this as: collection 4050, VHS numbers 1 through 10) being sure to use a General Note to outline what precisely has been digitized or 4050_vhs with additional component sub-digital objects for each VHS (bulk upload is helpful here!). If you’ve digitized the entire collection, use 4050_entirecollection.
    * __Conditions Governing Access__*(pick from one of the following as appropriate)*:
      * Use where all materials are available in MFCS/online only: Researchers may access digitized materials materials by visiting the link attached to each item or by requesting to view the materials in person by appointment or remotely by contacting the West Virginia & Regional History Center reference department at https://westvirginia.libanswers.com/wvrhc.
      * Use where availability of materials is mixed (some in MFCS and on server): Researchers may access digitized materials materials by visiting the link attached to each item or by requesting to view the materials in person by appointment or remotely by contacting the West Virginia & Regional History Center reference department at https://westvirginia.libanswers.com/wvrhc.
      * Use where materials are on server only: Researchers may access digitized materials materials by requesting to view the materials in person by appointment or remotely by contacting the West Virginia & Regional History Center reference department at https://westvirginia.libanswers.com/wvrhc.
    * __Extent__
        * Portion, select: Whole 
        * Number: Numeric value for quantity of files in GB
              * If the files are in MB or KB, use the [MB to GB](https://www.unitconverters.net/data-storage/mb-to-gb.htm) converter or [KB to GB](https://www.unitconverters.net/data-storage/kb-to-gb.htm) converter as relevant. Round to two decimal places or, for smaller collections, the first non-zero digit if beyond two digits (example: 0.00003 GB).  
        * Type, select: Gigabytes 
        * Container Summary: format as "1,000 .tif files", using the number and format of files for the applicable item. Audio and video files would use their respective file formats.
    * Notes -> General Content: Add any additional information necessary to ensure that it’s clear what has been digitized. This is particularly useful for minimally processed collections. Examples: “Box 3 folder 4 has been digitized.”, “Two letters from box 5 folder 2 have been digitized; the rest of the material in the folder has not been digitized.”, “The source locations for these materials were not noted.” 
    * Digital Object Type: choose the appropriate type from the fixed menu. Note that you are describing the original object, not the file format. For instance, a digitized letter would be “text” rather than “still image.”
    * Language: choose the correct language 
    * Date information includes:  
        * Expression, formatted as: YYYY-MM-DD, YYYY-MM, YYYY, undated 
        * Date Type, select: Single 
        * Label, select: Creation 
    * Agent Links: link the appropriate agent and role (usually creator) 
    * File Versions -> File URI (Only use for materials that are able to be linked to online.): Paste the URL for an item or a URL that links to search results for a group of items from a collection. Example: https://wvhistoryonview.org/?utf8=%E2%9C%93&search_field=all_fields&q=%22A%26M+9%22
6. Click Save on the Digital Object box. Then click save on the main Resource Record or Archival Object Record. If you don’t click save on the Resource Record or Archival Object Record the Digital Object will be created but not be correctly linked to the record and you’ll have to go back and relink the Digital Object.
