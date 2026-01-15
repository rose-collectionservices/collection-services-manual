
# Accessioning
Last revised April 2025. 
Content owner: Laura Starratt

* [3.1 Scope of Accessioning Workflow](#31-scope-of-accessioning-workflow)
* [3.2 Moving from Acquisition to Accessioning](#32-moving-from-acquisition-to-accessioning)
	* [3.2.1 Tracking New Acquisitions in Airtable](#321-tracking-new-acquisitions-in-airtable)
	* [3.2.2 Tracking of Special Formats](#322-tracking-of-special-formats)
* [3.3 Accessioning Workflow](#33-accessioning-workflow)
	* [3.3.1 Acquisition Paperwork and CL-2 Files](#331-acquisition-paperwork-and-cl-2-files)
	* [3.3.2 Locate Physical Materials](#332-locate-physical-materials)
	* [3.3.3 Update the Accession Record in ArchivesSpace](#333-update-the-accession-record-in-archivesspace)
		* [3.3.3.1 Add Event Records](#3331-add-event-records)
  		* [3.3.3.2 Remove Accession Record Instances](#3332-remove-accession-record-instances)
* [3.4 Arrangement and Description at the Point of Accessioning](#34-arrangement-and-description-at-the-point-of-accessioning)
	* [3.4.1 Processing Paper-based Materials](#341-processing-paper-based-materials)
	* [3.4.2 Processing Audiovisual Materials](#342-processing-audiovisual-materials)
   	* [3.4.3 Processing Born-digital Materials](#343-processing-born-digital-materials)
		* [3.4.3.1 Disposition of Computer Equipment](#3431-disposition-of-computer-equipment)
		* [3.4.3.2 Digital Accessioning Workflows](#3432-digital-accessioning-workflows)
   	* [3.4.4 Separating Publications for Cataloging](#344-separating-publications-for-cataloging)
 * [3.5 Label and Barcode the boxes](#35-label-and-barcode-the-boxes)
* [3.6 Creating Access Points at the Point of Accessioning](#36-creating-access-points-at-the-point-of-accessioning)
* [3.6.1 Spawning a New Resource Record](#361-spawning-a-new-resource-record)
	* [3.6.2 Updating an Existing Resource Record](#362-updating-an-existing-resource-record)
	* [3.6.3 Recording Physical Information](#363-recording-physical-information)
* [3.7 Cataloging at the Point of Accessioning](#37-cataloging-at-the-point-of-accessioning)
	* [3.7.1 MARC Records in OCLC Connexion](#371-marc-records-in-oclc-connexion)
	* [3.7.2 ALMA](#372-alma)
* [3.8 Tracking Accession Workflow and Output](#38-tracking-accession-workflow-and-output)
* [3.9 Create the CL-2 File](#39-create-the-cl-2-file)
* [3.9.1 Creating a Manuscript Collection File](#391-creating-a-manuscript-collection-file)
* [3.9.1.1 Legacy Electronic Collection File](#3911-legacy-electronic-collection-file)
	* [3.9.2 Creating an EUA Collection File](#392-creating-an-eua-collection-file)
* [3.10 Accessioning Checklist](#310-accessioning-checklist)


Accessioning is the formal act of taking legal and physical control of an archival or manuscript collection. Formally, accessioning establishes the authenticity of the material through documenting the chain of custody. It also gives the Rose Library administrative and custodial control over collections and shows that the library is acting in good faith when accepting archival material by documenting the transfer and its terms.

## 3.1 Scope of Accessioning Workflow
This section of the manual describes the accessioning tasks performed by processing archivists after acquisitions are received and recorded. Because the Rose Library aims to make all new acquisitions available to researchers following the accessioning of new acquisitions, archivists implement minimal processing at the point of accessioning; at minimum, the material must be described at the collection level, although more granular processing at the point of accessioning may be done in some cases (e.g., where the collection is quite small, or researcher interest is high). Information about decisions on levels of arrangement at this stage is found in [5.1 Levels of Arrangement and Description](<https://github.com/rose-collectionservices/collection-services-manual/tree/master/05-LEVELS OF ARRANGEMENT AND DESCRIPTION#51-levels-of-arrangement-and-description>). The [Accessioning Checklist](<https://github.com/rose-collectionservices/collection-services-manual/tree/master/03-ACCESSIONING#36-accessioning-checklist>) at the end of this section, therefore, includes tasks that are not part of traditional accessioning. 

The portion of the accessioning workflow outlined in this section primarily focuses on documenting the ownership and custody of collection materials through workflow tracking and collection management systems. The system of record for accessions is [ArchivesSpace](<https://archives.libraries.emory.edu/staff)/>), and [Airtable](<https://airtable.com/appxehhHnKmdPpzld/tblVOysdj8gmTooGt/viwM1W5reGNIwQRe3?blocks=hide>) is used to manage the workflow from the acquisitions through accessioning stages. The [Acquisitions folder in Sharepoint](<https://emory.sharepoint.com/:f:/r/sites/EUVRoseLibrary/Shared Documents/Acquisitions?csf=1&web=1&e=5W2pNF>) is the system of record for acquisitions paperwork until that paperwork is filed in the CL-2 file, and information is linked from there to both ArchivesSpace and Airtable for access during the accessioning workflow.

## 3.2 Moving from Acquisition to Accessioning
_Note: This workflow was fully implemented for Fiscal Year 2019 (FY19). Collection material received prior to FY19 will be recorded in ArchivesSpace but may not follow current process._

There is overlap between the acquisition and accessioning workflow, but generally, the Acquisitions workflow is completed by the Head of Processing, Associate Director, or University Archivist and documents the physical and legal transfer of materials to the Library and the creation and signing of transfer paperwork such as deeds of gift and sale and other appropriate documentation of sale, gift, or transfer. 

Prior to accessioning, the Head of Processing or University Archivist creates a preliminary ArchivesSpace accession record (see 2.2.3 Creating the ArchivesSpace preliminary accession record) and makes information available to Collections Archivists in the Airtable Acquisitions and Accessioning table’s "Accessioning To-Be-Assigned" view. 

_If the information is not found in the “Accessioning To-Be Assigned,” confirm that stage is correctly set in the Airtable "Potential and/or Not Yet Received" view._

When acquisitions are ready to move to the accessioning stage?:
*	Head of Processing assigns new accessioning projects to Collection Archivists (adding the record to their personal views in Airtable) based on current workloads and specific expertise when possible
	*	Hybrid collections – those that include a combination of paper, audiovisual, and/or born digital materials -- can be assigned to Collection Archivists who will consult with the Digital Archivist
	*	Collections comprising exclusively digital material (in the form of digital media, computer equipment, file transfers, or web archives) are assigned to a digital archivist.The Digital Archivist should accession wholly digital acquisitions (and drives?)
*	Information from curators (including notes taken by the Head of Processing during monthly Acquisition Strategies meetings and [Collection Information Sheets](<https://emory.sharepoint.com/:f:/r/sites/EUVRoseLibrary/Shared Documents/Collection Development/Collection Information Sheets?csf=1&web=1&e=bQxH3V>) is passed on to the archivists responsible for the accessions

### 3.2.1 Tracking New Acquisitions in Airtable
_For more background information about Airtable, see [2.3.2 Airtable](<>)_

Once an accession has been assigned to an archivist, it will appear in their personal view (see 2.3.2 Airtable for more information including how to adjust your personal view). At this stage, an Airtable record should, at minimum, include the following fields: (see table in 2.3.2.1 Manuscript and Book Acquisitions in Airtable for more information on content)
*	Creator
*	Accessioning Record Title (which refers to the accession title, not a collection title) 
*	Accession number
*	Stage
*	Location
*	Paperwork
*	Extent information (including linear feet and/or number of items)

_If any of these fields are incomplete, contact the Head of Processing to complete the 2.2 Acquisition workflow._

At this initial point, the Collection archivist will confirm the following in Airtable:
*	That the accession number is entered and correct
*	The Assigned To field includes your name
*	That Paperwork field links to the correct file in the [Sharepoint Acquisition folder](<https://emory.sharepoint.com/:f:/r/sites/EUVRoseLibrary/Shared Documents/Acquisitions?csf=1&web=1&e=MpfOmW>)
*	That, if establishing a new collection, what the next available collection number is via either the [Manuscript Register](<https://emory.sharepoint.com/:x:/r/sites/EUVRoseLibrary/Shared%20Documents/Cataloging%20and%20Collection%20Processing/Stacks%20Management/Registers%20and%20Inventories/Manuscript%20Register.xlsx?d=w870976b852d84f80b0d6490280b167e5&csf=1&web=1&e=9NhESE>) or the [EUA Series Register](<https://emory.sharepoint.com/:x:/r/sites/EUVRoseLibrary/Shared%20Documents/Cataloging%20and%20Collection%20Processing/Stacks%20Management/Registers%20and%20Inventories/EUA%20Register.xlsx?d=w2f2db20ced8147f5bd839feedd092db1&csf=1&web=1&e=VElGec>)

Airtable checklist (optional, but recommended)
*	Click on the Accessioning Checklist tab in the Acquisitions and Accessioning base and navigate to “(yourname)’s View” under the "My personal views" view.
*	Click on the (+) at the bottom right of the screen to add a checklist
*	Type the title of the accession. [This is a free text field where you can enter whatever title you like, including the accession number if it’s an easier reference. You will link to the Airtable record in the next step.]
*	Click on Add record. Start typing the name of the accession (as found in the Airtable record) and a suggested list will come up. Click on the correct record to link the checklist to the appropriate record. 
	*	_In cases where there are multiple accessions with similar, if not the same, accession titles, confirm that you have linked to the correct accession record by clicking through the record once you have attached it. Scroll to the bottom of that record, click on the button to “Show (#) fields” and search for the Accession record number to confirm that you have linked to the correct accession. If you’ve chosen the wrong accession record, go back to the checklist and hover over the box in the Acquisitions & Accessioning Table Link until the “x” appears. -Identifying the "Date of Invoice" can also help you select the correct record as it displays in the selection_
*	As you go through the accessioning process, complete the steps in the Airtable checklist and confirm by clicking the checkboxes.

### 3.2.2 Tracking of Special Formats
*	Add information regarding any known born-digital media and/or hardware to the born-digital inventory, which is stored in the [Digital Archives Tab](<https://emory.sharepoint.com/:x:/r/sites/BoxDeletedUsers14/Shared%20Documents/aczebla_emory_edu/MARBL_Master%20SHELF%20LIST/Shelf%20List.xlsx?d=wf0968fe689044379898108b0228a3a62&csf=1&web=1&e=izc57O&nav=MTVfezAwMDAwMDAwLTAwMDEtMDAwMC0wMzAwLTAwMDAwMDAwMDAwMH0>) of the  Master Shelf List.
*	Audiovisual materials should be included in the AV Inventory.

## 3.3 Accessioning Workflow
### 3.3.1 Acquisition Paperwork and CL-2 Files
Confirm that you have the necessary acquisitions paperwork. 

As part of the acquisition workflow, the Head of Processing will
*	Link the deeds and other acquisitions paperwork (found in the Sharepoint Acquisitions folder) to: 
	*	The ArchivesSpace Accession Record under External Documents
	*	The Airtable record in the Acquisitions & Accessions base in the Paperwork field.
*	Either print out the electronic copy or include the original paperwork with the collection material
*	Write the accession number on the paperwork

Hard copies of the paperwork should be located with the accession materials, but if there is no documentation on the accession (either paper or digital), contact the Head of Processing as the materials may not be ready to move forward with accessioning.

If only the digital copy of the acquisition paperwork is available, print out a copy of the paperwork and write the accession number on the top of the page. These materials will be included in the collection files that are commonly called “CL-2 files” for manuscript collections.  

When the accession is an addition to an established collection, review the documentation in the CL-2 file for background information on the papers or any conflicting information regarding disposition or restrictions. 

For information about creating CL-2 files , (see 3.7 Create the CL-2 File).

### 3.3.2 Locate Physical Materials
Confirm you have all the containers before you start the accession process. Check acquisitions documentation for any mention of file transfers or other digital content not already accounted for and make a plan to discuss born digital materials with the Digital Archivist.

The location for the physical materials is found in either:
*	Airtable Location field
*	ArchivesSpace Instance sub-record. 

Other options for identifying locations for acquisitions:
*	[Master Shelf List Pending Acquisitions](<https://emory.sharepoint.com/:x:/r/sites/BoxDeletedUsers14/Shared Documents/aczebla_emory_edu/MARBL_Master SHELF LIST/Shelf List.xlsx?d=wf0968fe689044379898108b0228a3a62&csf=1&web=1&e=PL48Rv&nav=MTVfezAwMDAwMDAwLTAwMDEtMDAwMC0wMjAwLTAwMDAwMDAwMDAwMH0>) tab. While this tab is no longer in current use, legacy information on accessions before 2022 may be found here.
*	Format-based shelves including the OP, XOP, OBV, LP shelves may contain mis-shelved accessioning 

In legacy acquisitions – those acquired and documented before 2022 - the containers may not be standard boxes and labels could be hidden. 

### 3.3.3 Update the Accession Record in ArchivesSpace
Typically, the Head of Processing or University Archivist will create the preliminary ArchivesSpace Accession Record before assigning the accession to a Collection archivist. Collection archivists should refer back to [2.3.3 Preliminary ArchivesSpace Accession Record] for additional information on updating any incomplete fields in the accession record, but the most common updates include: 
*	Content description
*	Extents
*	Dates
*	Related Resource Record

#### 3.3.3.1 Add Event Records
Confirm the Custody Transfer and Agreement Signed event records are added (see 2.2.3.10 Event Records for more information) by clicking on the view option for the Accession Record and scrolling to the bottom. Content for these records is usually found in the acquisition paperwork in either Airtable or ArchivesSpace or within fields in Airtable. 

The Accession event record should not be added until the collection is going through the accession workflow. This record identifies the action taken by the archivist at this point and signifies, in ArchivesSpace, that accessioning has been completed.
*	Open the Accession Record.
*	Click on Add Event and select Accession from the drop-down menu in the top right. 
*	Complete the record using the field guidelines below and save the record:

| Accession Event Fields                                        | Content                                                                                                                                                                                                                                                       |
|----------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|Basic Information|<ul>Type: accession (from drop down menu)</ul><ul>_Outcome: Fulfilled (from drop down menu)</ul>_|
|Event Date/Time|<ul>Date/Time specifier: UTC Timestamp (from drop down menu)</ul><ul>UTC Timestamp: date the material arrived on-site in YYYY-MM-DD format</ul><ul> Hours, minutes, and seconds not required</ul>|
|Agent Links|<ul>Role: archivist (from drop down menu)</ul><ul>Agents: name of archivist accessioning (from drop down menu)</ul>|
|Record Links|<ul>Role: Source (should be autofilled, but if not, select from drop down menu)</ul><ul>Record: accession record that this custody record was pulled from (should be autofilled, but if not, select from drop down menu) </ul>

#### 3.3.3.2 Remove Accession Record Instances
Remove all instances in the Accession record.  

To individually remove instances, click on the x in the top right-hand corner of the Instance sub-record, and click on “Confirm Removal.” There will be no further confirmation.

To bulk remove instances, use the Manage Top Containers option via the Accession search field.  Follow directions in [16. ArchivesSpace](<https://github.com/rose-collectionservices/collection-services-manual/tree/master/16-ARCHIVESSPACE#archivesspace>)

## 3.4 Arrangement and Description at the Point of Accessioning
As mentioned in 3.1 Scope of Accessioning Workflow, the Rose Library’s workflow for accessioning includes minimal level processing (and, in some cases, more granular processing) including the spawning of a Resource Record for access. 

If you are establishing a new collection, use the [Manuscript Register](<https://emory.sharepoint.com/:x:/r/sites/EUVRoseLibrary/Shared%20Documents/Cataloging%20and%20Collection%20Processing/Stacks%20Management/Registers%20and%20Inventories/Manuscript%20Register.xlsx?d=w870976b852d84f80b0d6490280b167e5&csf=1&web=1&e=9NhESE>) or the [EUA Series Register](<https://emory.sharepoint.com/:x:/r/sites/EUVRoseLibrary/Shared%20Documents/Cataloging%20and%20Collection%20Processing/Stacks%20Management/Registers%20and%20Inventories/EUA%20Register.xlsx?d=w2f2db20ced8147f5bd839feedd092db1&csf=1&web=1&e=VElGec>) to identify the next collection number for the new collection.

### 3.4.1 Processing Paper-based Materials
See the following sections:
*	[5.1 Rose Library Levels of Arrangement and Description](<https://github.com/rose-collectionservices/collection-services-manual/tree/master/05-LEVELS%20OF%20ARRANGEMENT%20AND%20DESCRIPTION#51-levels-of-arrangement-and-description>).
	*	Use, at the minimum, [Collection-level arrangement](<https://github.com/rose-collectionservices/collection-services-manual/tree/master/05-LEVELS%20OF%20ARRANGEMENT%20AND%20DESCRIPTION#512-collection-level>)
*	[10. Physical Processing](<https://github.com/rose-collectionservices/collection-services-manual/tree/master/10-PHYSICAL%20PROCESSING#physical-processing>)
  


### 3.4.2 Processing Audiovisual Materials
See the following sections:
*	[10.7.3 Quick Guide to Audiovisual materials](<https://github.com/rose-collectionservices/collection-services-manual/tree/master/10-PHYSICAL%20PROCESSING#1073-processing-audiovisual-media>)
	*	Including additions to the [AV inventory](<https://airtable.com/appeplPMjN4DSeF3K?>) _current link directly to inventory_
*	For more granular processing, see [11.2 Audiovisual materials](<https://github.com/rose-collectionservices/collection-services-manual/tree/master/11-FORMAT%20SPECIFIC%20PROCEDURES#112-audiovisual-materials>)

### 3.4.3 Processing Born-digital Materials
See the following sections:
*	[10.7.4 Quick Guide to Digital Media](<https://github.com/rose-collectionservices/collection-services-manual/tree/master/10-PHYSICAL%20PROCESSING#1073-processing-audiovisual-media>)
	*	Refer to controlled vocabulary to describe digital media (see [10.7.4.1 Digital Media Controlled Vocabulary](<https://github.com/rose-collectionservices/collection-services-manual/tree/master/10-PHYSICAL%20PROCESSING#10741-digital-media-controlled-vocabulary>))
*	[11.3 Born-digital Materials](<https://github.com/rose-collectionservices/collection-services-manual/tree/master/11-FORMAT%20SPECIFIC%20PROCEDURES#113-born-digital-materials>)
*	[Rose Library Digital Archives Manual](<https://github.com/rose-collectionservices/digital-archives?tab=readme-ov-file#rose-library-digital-archives-manual>)

#### 3.4.3.1 Disposition of Computer Equipment
Typically, if we receive laptops or personal computers, we will only retain the internal hard drives following processing. The Digital Archivist will send all other hardware and casings to surplus. You should therefore describe laptops and computers as “hard disks” in accession records (see  [10.7.4.1 Digital Media Controlled Vocabulary](<https://github.com/rose-collectionservices/collection-services-manual/tree/master/10-PHYSICAL%20PROCESSING#10741-digital-media-controlled-vocabulary>)). If we do have reason to keep the entire computer (either because it features labels and markings intentionally added by the donor/creator that contribute significant meaning or because the entire computer will be required to access and transfer files), describe it as either “computer” or “laptop computer." **Consult with the digital archivist if you are unsure of which term to use**.

Apart from exceptional cases, you should not accession computer peripherals (monitors, keyboards, etc.), networking hardware (routers, for example), and other electronic components not used to store data unless:
*	They feature labels and markings intentionally added by the donor/creator that contribute significant meaning to the collection. These should not be labels or markings that simply denote ownership or give instruction on use or function (i.e., “Dorothy’s mouse” or “plug in here”).
*	In cases where the associated hardware is particularly old or obscure and it has been deemed likely, following consultation with a digital archivist, this equipment will be required in order to access and transfer digital files from the associated hardware.

If you have questions about whether a piece of equipment or media should be accessioned, consult with the Digital Archivist.

#### 3.4.3.2 Digital Accessioning Workflows
 Like all collection material, born-digital media and files should not be accessioned until paperwork has been completed. The workflow will vary slightly depending on the method of transfer or if the born-digital material is part of a hybrid collection. 
 
 *	Check the acquisitions documentation for mention of file transfers, significant organizational or personal websites (see [11.4 Web archives](<https://github.com/rose-collectionservices/collection-services-manual/tree/master/11-FORMAT%20SPECIFIC%20PROCEDURES#114-web-archives>) for selection criteria), or other digital content not already accounted for. With a digital archivist, make a plan to incorporate these materials into the accession and resource records.
 *	Upon identifying and documenting the presence of digital content and records baseline description, the collection archivist will reach out to a member of the Digital Archives team to retrieve the content of physical media and transfer or capture other content. 

*	If the acquisition includes known born-digital media and/or hardware:
	*	The collection archivist accessions the born-digital media and/or hardware with the rest of the collection, following the steps in the [10.7.4 Quick Guide to Digital Media](<https://github.com/rose-collectionservices/collection-services-manual/tree/master/10-PHYSICAL%20PROCESSING#1073-processing-audiovisual-media>) and using [10.7.4.1 Digital Media Controlled Vocabulary](<https://github.com/rose-collectionservices/collection-services-manual/tree/master/10-PHYSICAL%20PROCESSING#10741-digital-media-controlled-vocabulary>) to describe what is included.
 	*	Collection archivists should keep smaller pieces of born-digital media such as floppy disks or flash drives with the collection when moved to the stacks or sent to the LSC.
  	*	This information must be recorded in [Born-digital Inventory](<https://emory.sharepoint.com/:x:/r/sites/BoxDeletedUsers14/Shared%20Documents/aczebla_emory_edu/MARBL_Master%20SHELF%20LIST/Shelf%20List.xlsx?d=wf0968fe689044379898108b0228a3a62&csf=1&web=1&e=gWF3Ft&nav=MTVfezAwMDAwMDAwLTAwMDEtMDAwMC0wMzAwLTAwMDAwMDAwMDAwMH0>) and shared with the Digital Archivist.
  	*	While the collection archivist may proceed with the accessioning workflow at this point, the collection will not be considered fully accessioned until the Digital Archivist completes the [Tier 1 digital processing workflow](<https://github.com/rose-collectionservices/digital-archives/blob/master/Processing%20Tiers/Tier%201.md>) and updates the accession and resource records accordingly. 

*	If the acquisition is comprised exclusively of born-digital media and/or hardware:
	*	Following the steps in the [10.7.4 Quick Guide to Digital Media](<https://github.com/rose-collectionservices/collection-services-manual/tree/master/10-PHYSICAL%20PROCESSING#1073-processing-audiovisual-media>), the Digital Archivist accessions the born-digital media and/or hardware.
	*	When possible, the Digital Archivist will also image disks, create digital object records, and ingest preservation copies into the digital repository at the point of accessioning.

*	If the acquisition includes a file transfer or websites:
	*	Collection archivist will check the acquisitions documentation for mention of file transfers, significant organizational or personal websites (see [11.4 Web Archives](<https://github.com/rose-collectionservices/collection-services-manual/tree/master/11-FORMAT%20SPECIFIC%20PROCEDURES#114-web-archives>) for selection criteria) or any other unaccounted for digital content.
 	*	The Digital Archivist moves the transferred files to a temporary storage location on the digital archive lab’s local hard drives or the LIBSAFE Go accessioning node.
	*	The Digital Archivist includes this information in the [Born-digital Inventory](<https://emory.sharepoint.com/:x:/r/sites/BoxDeletedUsers14/Shared%20Documents/aczebla_emory_edu/MARBL_Master%20SHELF%20LIST/Shelf%20List.xlsx?d=wf0968fe689044379898108b0228a3a62&csf=1&web=1&e=gWF3Ft&nav=MTVfezAwMDAwMDAwLTAwMDEtMDAwMC0wMzAwLTAwMDAwMDAwMDAwMH0>) and notes whether they have ingested the files into the digital repository, sharing this information with the collection archivist (or, if not assigned, with the Head of Processing to include in the acquisition notes).
	*	The collection archivist accessions the file transfer with the rest of the collection, using the term “digital files” from [10.7.4.1 Digital Media Controlled Vocabulary](<https://github.com/rose-collectionservices/collection-services-manual/tree/master/10-PHYSICAL%20PROCESSING#10741-digital-media-controlled-vocabulary>) to describe what is included.
	*	If there are websites related to the collection that requiring tracking as part of our web archiving program, please complete this form. [link to documentation that doesn’t exist yet]

### 3.4.4 Separating Publications for Cataloging
See [10.5.2 Separating materials/Publications](<https://github.com/rose-collectionservices/collection-services-manual/tree/master/10-PHYSICAL PROCESSING#1052-publications)

## 3.5 Label and Barcode the boxes
Once the finding aid is completed and reviewed, complete procedures found in [10. Physical Processing](<https://github.com/rose-collectionservices/collection-services-manual/tree/master/10-PHYSICAL PROCESSING#physical-processing>) including:
*	[10.9 Labeling boxes](<https://github.com/rose-collectionservices/collection-services-manual/tree/master/10-PHYSICAL PROCESSING#109-labeling-boxes>)
	*	[13.2.2 Box naming conventions based on shelving locations](<https://github.com/rose-collectionservices/collection-services-manual/tree/master/13-STACKS MANAGEMENT#1312-box-naming-conventions-based-on-shelving-locations>)
*	[10.10 Barcoding boxes](<https://github.com/rose-collectionservices/collection-services-manual/tree/master/10-PHYSICAL PROCESSING#1010-barcoding-boxes>)
	*	File the barcode folder in the appropriate filing cabinet in 973B.

## 3.6 Creating Access Points at the Point of Accessioning
### 3.6.1 Spawning a New Resource Record
If the newly accessioned collection establishes a new collection, follow the procedures listed in the ArchivesSpace wiki for [Spawn Resource Record from Accession Record](<https://archivesspace.atlassian.net/wiki/spaces/ArchivesSpaceUserManual/pages/893878578/Creating+a+Minimal+Resource+Record>)

_Confirm that the Publish button is not checked._

You will then complete the following:
*	Confirm the content in the Resource Record is correct and add required information as explained in [5.1 Levels of Arrangement and Description](<https://github.com/rose-collectionservices/collection-services-manual/tree/master/05-LEVELS%20OF%20ARRANGEMENT%20AND%20DESCRIPTION#51-levels-of-arrangement-and-description>) and according to [6.1 Finding Aids](<https://github.com/rose-collectionservices/collection-services-manual/tree/master/06-DESCRIPTION#61-finding-aids>)
*	Add Archival Objects to the Resource Record
	*	Individually: (see To create resource archival object records under _[ArchivesSpace Resource Records: Archival Objects](<https://archivesspace.atlassian.net/wiki/x/-gBLNQ>)_)
		*	Required: Title, Level of Description (file), Click Publish?, Dates, Instances
		*	Optional, but suggested when adding to miscellany collections: Accession Links,
		*	_[Creating a Top container if a new box is created](<https://archivesspace.atlassian.net/wiki/x/DQBSNQ>)_
	*	[Via spreadsheet](<https://emory.sharepoint.com/:w:/r/sites/EUVRoseLibrary/Shared Documents/Cataloging and Collection Processing/Collection Processing/Manuals/ArchivesSpace/Guide_load via spreadsheet_ASpace.docx?d=w7768e7be34cb42cc987a5e44adc46353&csf=1&web=1&e=TyMgcK>) (more information found at _[ArchivesSpace Importing Archival Objects from Excel or CSV File](<https://archivesspace.atlassian.net/wiki/x/LoD4RQ>)_)
o	Using the_ [Rapid Data Entry (RDE) Tool](<https://archivesspace.atlassian.net/wiki/x/VwFJNQ>) _(also see [How to Create an RDE Template](<https://emory.sharepoint.com/:w:/r/sites/EUVRoseLibrary/Shared Documents/Cataloging and Collection Processing/Collection Processing/Manuals/ArchivesSpace/Guide_Create RDE template_ASpace.docx?d=w44b5e20a2e0a422e9aaaa94cee5c19d5&csf=1&web=1&e=oE8PzO>))
•	If the accession establishes a new collection, or there is a significant addition, the finding aid should be sent for review via the procedures found in [6.3 Reviewing and Editing Finding Aids](<https://github.com/rose-collectionservices/collection-services-manual/tree/master/06-DESCRIPTION#63-reviewing-and-editing-finding-aids>)
•	Once a finding aid has been reviewed and/or all changes to the resource record have been finalized, publish the resource record.

### 3.6.2 Updating an Existing Resource Record
*	Add Archival Objects to the Resource Record in the process most relevant to your materials (e.g., if there are items or a single folder, add the archival object individually)
	*	Individually (see _To create resource archival object records_ under_ [ArchivesSpace Resource Records: Archival Objects](<https://archivesspace.atlassian.net/wiki/x/-gBLNQ>)_)
		*	Required: Title, Level of Description (file), Click _Publish?_, Dates, Instances
		*	Optional, but suggested: Accession Links
		*	_[Creating a Top container if a new box is created](<https://archivesspace.atlassian.net/wiki/x/DQBSNQ>)_
	*	[Via spreadsheet](<https://emory.sharepoint.com/:w:/r/sites/EUVRoseLibrary/Shared Documents/Cataloging and Collection Processing/Collection Processing/Manuals/ArchivesSpace/Guide_load via spreadsheet_ASpace.docx?d=w7768e7be34cb42cc987a5e44adc46353&csf=1&web=1&e=TyMgcK>) (more information found at_ [ArchivesSpace Importing Archival Objects from Excel or CSV File_](<https://archivesspace.atlassian.net/wiki/x/LoD4RQ>)_)
	*	_[Using the Rapid Data Entry (RDE) Tool](<https://archivesspace.atlassian.net/wiki/x/VwFJNQ>)_ (also see_ [How to Create an RDE Template](<https://archivesspace.atlassian.net/wiki/x/VwFJNQ>)_)
*	Update [Collection-level Dates](<https://github.com/rose-collectionservices/collection-services-manual/tree/master/06-DESCRIPTION#617-dates>), [Extents](<https://github.com/rose-collectionservices/collection-services-manual/tree/master/06-DESCRIPTION#618-extent>), and other notes if necessary
*	Publish Resource Record

### 3.6.3 Recording Physical Information
*	Update information in ArchivesSpace via [Top Container Management](<>)
	*	_[Barcodes](<https://archivesspace.atlassian.net/wiki/spaces/ArchivesSpaceUserManual/pages/894402619/Performing+Bulk+Operations+on+Top+Containers#Add-or-change-barcodes-associated-with-top-containers>)
	*	[Shelf Locations](<https://archivesspace.atlassian.net/wiki/spaces/ArchivesSpaceUserManual/pages/894402619/Performing+Bulk+Operations+on+Top+Containers#Update-container-locations-for-containers-stored-at-a-single-location>)
	*	[Container profiles](<https://archivesspace.atlassian.net/wiki/spaces/ArchivesSpaceUserManual/pages/894402619/Performing+Bulk+Operations+on+Top+Containers#Update-container-profiles>)_

*	Update information in [Shelf List](<https://emory.sharepoint.com/:x:/r/sites/BoxDeletedUsers14/_layouts/15/Doc.aspx?sourcedoc=%7BF0968FE6-8904-4379-8981-08B0228A3A62%7D&file=Shelf%20List.xlsx&action=default&mobileredirect=true>) (see tabs for Manuscript, EUA, Digital Archives, and AV Drives) according to [13.1.3 Master Shelf List](<https://github.com/rose-collectionservices/collection-services-manual/tree/master/13-STACKS%20MANAGEMENT#131-systems-of-record-for-location-management>)
	*	Main Entry/Title
	*	Extents
	*	Locations
	*	Restrictions

*	Update information in [Airtable](<https://airtable.com/appxehhHnKmdPpzld?>)
	*	If you used the Airtable checklist (information found in 3.2.1 Tracking New Acquisitions through Airtable), mark the collection as “complete” by using the checkbox at the bottom
	*	In the Acquisition and Accessioning table, confirm that Stage is updated to “Accessioning and/or Cataloging Completed” via the drop-down menu
	*	Update the Linear Feet, MSS Items and Extent Type as well as any other Special Format fields
	*	Enter the current date in the Accession Date field

## 3.7 Cataloging at the Point of Accessioning
### 3.7.1 MARC Records in OCLC Connexion
Create an OCLC catalog record for newly established collections using the workflow found in [17.1.2 Creating an OCLC Catalog Record for Archival Collections](<https://github.com/rose-collectionservices/collection-services-manual/tree/master/17-CATALOGING#1712-creating-an-oclc-catalog-record-for-archival-collections>).

Updating the OCLC catalog record for acquisitions that are additions primarily consists of updating the extent and date, but other updates may be necessary depending on the addition.

### 3.7.2 ALMA
As part of the OCLC Connexion workflow, the created/updated record is exported to ALMA. However, holdings and item records must also be created or updated in Alma using the workflow found in [17.2.2 Creating Alma holdings records and item records for archival collections](<https://github.com/rose-collectionservices/collection-services-manual/tree/master/17-CATALOGING#1722-creating-alma-holdings-records-and-item-records-for-archival-collections>). **Be sure to use the correct holdings location based on the final location of the materials**. 


### 3.8 Tracking Accession Workflow and Output
*	Update the processing statistics in the [Sharepoint Annual Processing Reports](<https://emory.sharepoint.com/:x:/r/sites/EUVRoseLibrary/Shared%20Documents/Reports%20and%20Statistics/Collection%20Services/Manuscript%20Processing%20Statistics/Annual%20Processing%20Reports.xlsx?d=we8382d29282646d8a17b240c1a701e96&csf=1&web=1&e=Vf16FH>) file
*	Announce new collections or significant additions on the #collections Slack channel
*	Inform or request that curators inform donors and/or creators that new collections are now open

## 3.9 Create the CL-2 File
After the collections archivist has finished an accession, the acquisitions paperwork must be placed in a collection file. 

### 3.9.1 Creating a Manuscript Collection File
The Collections Archivist will create a CL-2 file, if one is not already established: 
*	Write the creator and MSS number on the top of a letter-sized folder (add photo) 
*	If there is not a physical copy of the acquisition paperwork, print out a copy from the Sharepoint Acquisitions folder (locating via ArchivesSpace external documents field)
*	Confirm that the accession number has been written on top of the acquisitions paperwork before placing it in the folder
*	File the folder alphabetically by creator in the CL-2 cabinets in the L9 BizHub room 

(For more information about Collection Files, see TBD)

#### 3.9.1.1 Legacy Electronic Collection File
There are [legacy collection files in Sharepoint](<https://emory.sharepoint.com/:f:/r/sites/EUVRoseLibrary/Shared%20Documents/Cataloging%20and%20Collection%20Processing/CL%20Files/CL-2%20Permanent%20Manuscript%20Collection%20Files?csf=1&web=1&e=9CyCXr>) that include information that overlaps with the physical CL-2 files. These files are not currently supported or updated, but they do contain information that may not be found elsewhere.

### 3.9.2 Creating an EUA Collection File
See [Precustodial and Acquisitions Workflows](https://emory.sharepoint.com/:w:/s/EUVRoseLibrary/IQCg4fP_o5YpR4mzNfEr09pXAdtaOGhxzqFdrBmgyv2oAao?e=8Tbbbw)

## 3.10 Accessioning Checklist
See [18.5 Checklist for MSS accessioning](https://github.com/rose-collectionservices/collection-services-manual/tree/master/18-PROCEDURE%20GUIDES%20AND%20CHECKLISTS#185-checklist-for-mss-accessioning)













 


