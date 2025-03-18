
# Accessioning workflow [Not complete]

Content owner:Laura Starratt


* [3.1 Scope of Accessioning Workflow](#31-scope-of-accessioning-workflow)
* [3.2 Moving from Acquisition to Accessioning](#32-Moving-from-Acquisition-to-Accessioning)
	* [3.2.1 Tracking New Acquisitions in Airtable](#321-Tracking-New-Acquisitions-in-Airtable)
	* [3.2.2 Tracking of Special Formats (Audiovisual, Born Digital, Web)](#322-Tracking-of-Special-Formats-(Audiovisual,-Born-Digital,-Web))
* [3.3 Accessioning Workflow](#33-Accessioning-workflow)
	* [3.3.1 Acquisition Paperwork and CL-2 Files](#331-Acquisition-paperwork-and-CL-2-files)
	* [3.3.2 Locate Physical Materials](#332-Locate-Physical-Materials)
	* [3.3.3 Update the Accession Record in ArchivesSpace](#333-Update-the-accession-record-in-ArchivesSpace)
		* [3.3.3.1 Add Event Records](#3331-add-event-records)
  		* [3.3.3.2 Remove Accession Record Instances](#3332-Remove-Accession-Record-Instances)
* [3.4 Processing at the Point of Accessioning](#34-Processing-at-the-Point-of-Accessioning)
	* [3.4.1 Arranging and Rehousing Collections](#341-Arranging-and-Rehousing-Collections)
		* [3.4.1.1 Paper-based Materials](#3411-paper-based-materials)
   		* [3.4.1.2 Audiovisual Materials](#3412-Audiovisual-Materials)
		* [3.4.1.3 Born-digital Materials](#3413-Born-digital-Materials)
			* [3.4.1.3.1 Digital content not on physical media](#34132-digital-content-not-on-physical-media)
   			* [3.4.1.3.2 Handoff to Digital Archives](#34132-handoff-to-Digital-Archives)
 		* [3.4.1.4 Published Materials/Cataloging](#3414-Published-Materials/Cataloging)
	* [3.4.2 Describing Collections](#342-Describing-Collections)
		* [3.4.2.1 Spawning a New Resource Record](#3421-Spawning-a-New-Resource-Record)
		* [3.4.2.2 Updating a Resource Record](#3422-Updating-a-Resource-Record)
	* [3.4.3 Finding Aid Review](#343-Finding-Aid-Review)
* [3.5 Cataloging at the Point of Accessioning](#35-Cataloging-at-the-Point-of-Accessioning)
	* [3.5.1 MARC Records in OCLC Connexion](#351-MARC-records-in-OCLC-Connexion)
	* [3.5.2 ALMA](#352-ALMA)
* [3.6 Finalizing the Accession](#36-Finalizing-the-Accession)
	* [3.6.1 Label and Barcode](#361-Label-and-barcode)
	* [3.6.2 Stacks Management](#362-Stacks-Management)
	* [3.6.3 Tracking Accession Workflow and Output](#363-Tracking-accession-workflow-and-output)
* [3.7 Create the CL-2 File](#37-Create-the-CL-2-File)
	* [3.7.1 Creating a Manuscript Collection File (CL-2 Files)](#371-Creating-a-manuscript-collection-file-CL-2-files)
		* [3.7.1.1 “Legacy” Electronic CL-2 File (Vital Docs Folder)](#3711-“Legacy”-Electronic-CL-2-File-(Vital-Docs-Folder))
	* [3.7.2 Creating an EUA Collection file (CL-2 Files)](#372-Creating-an-EUA-collection-file-(CL-2-files))
	* [3.7.3 Using Collection Files (CL-2 files)](#373-Using-collection-files-(CL-2-files))
* [3.8 Accessioning Checklist](#38-Accessioning-Checklist)

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
_For more background information about Airtable, see [2.3.2 Airtable](<>) _

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

Airtable checklist (optional, but recommended)
*	Click on the Accessioning Checklist tab in the Acquisitions and Accessioning base and navigate to “(yourname)’s View” under the "My personal views" view.
*	Click on the (+) at the bottom right of the screen to add a checklist
*	Type the title of the accession. [This is a free text field where you can enter whatever title you like, including the accession number if it’s an easier reference. You will link to the Airtable record in the next step.]
*	Click on Add record. Start typing the name of the accession (as found in the Airtable record) and a suggested list will come up. Click on the correct record to link the checklist to the appropriate record. 
	*	_In cases where there are multiple accessions with similar, if not the same, accession titles, confirm that you have linked to the correct accession record by clicking through the record once you have attached it. Scroll to the bottom of that record, click on the button to “Show (#) fields” and search for the Accession record number to confirm that you have linked to the correct accession. If you’ve chosen the wrong accession record, go back to the checklist and hover over the box in the Acquisitions & Accessioning Table Link until the “x” appears. -Identifying the "Date of Invoice" can also help you select the correct record as it displays in the selection_
*	As you go through the accessioning process, complete the steps in the Airtable checklist and confirm by clicking the checkboxes.

### 3.2.2 Tracking of Special Formats (Audiovisual, Born Digital, Web)
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

For information about creating CL-2 files , (see ## Section to be Created about CL-2 files).

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

#### 3.3.3.1 Events
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

## 3.4 Processing at the Point of Accessioning
As mentioned in 3.1 Scope of Accessioning Workflow, the Rose Library’s workflow for accessioning includes minimal level processing (and, in some cases, more granular processing) as well as creating a spawned Resource Record for access.  

### 3.4.1 Arranging and Rehousing Collections
#### 3.4.1.1 Paper-based Materials
See the following sections:
*	[5.1 Rose Library Levels of Arrangement and Description](<https://github.com/rose-collectionservices/collection-services-manual/tree/master/05-LEVELS%20OF%20ARRANGEMENT%20AND%20DESCRIPTION#51-levels-of-arrangement-and-description>).
	*	Use, at the minimum, [Collection-level arrangement](<https://github.com/rose-collectionservices/collection-services-manual/tree/master/05-LEVELS%20OF%20ARRANGEMENT%20AND%20DESCRIPTION#512-collection-level>)
*	[10. Physical Processing](<https://github.com/rose-collectionservices/collection-services-manual/tree/master/10-PHYSICAL%20PROCESSING#physical-processing>)

#### 3.4.1.2 Audiovisual Materials
See the following sections:
*	[10.7.3 Quick Guide to Audiovisual materials](<https://github.com/rose-collectionservices/collection-services-manual/tree/master/10-PHYSICAL%20PROCESSING#1073-processing-audiovisual-media>)
	*	Including additions to the AV inventory 
*	For more granular processing, see [11.2 Audiovisual materials](<https://github.com/rose-collectionservices/collection-services-manual/tree/master/11-FORMAT%20SPECIFIC%20PROCEDURES#112-audiovisual-materials>)

#### 3.4.1.3 Born-digital Materials
See the following sections:
*	[10.7.4 Quick Guide to Digital Media](<https://github.com/rose-collectionservices/collection-services-manual/tree/master/10-PHYSICAL%20PROCESSING#1073-processing-audiovisual-media>)
	*	Refer to controlled vocabulary to describe digital media (see [10.7.4.1 Digital Media Controlled Vocabulary](<https://github.com/rose-collectionservices/collection-services-manual/tree/master/10-PHYSICAL%20PROCESSING#10741-digital-media-controlled-vocabulary>)
*	[11.3 Born-digital Materials](<https://github.com/rose-collectionservices/collection-services-manual/tree/master/11-FORMAT%20SPECIFIC%20PROCEDURES#113-born-digital-materials>)
*	[Rose Library Digital Archives Manual](<https://github.com/rose-collectionservices/digital-archives?tab=readme-ov-file#rose-library-digital-archives-manual>)

Typically, if we receive laptops or personal computers, we will only retain the internal hard drives following processing. The Digital Archivist will send all other hardware and casings to surplus. You should therefore describe laptops and computers as “hard disks” in accession records (see 10.7.4.1 Digital media controlled vocabulary). If we do have reason to keep the entire computer (either because it features labels and markings intentionally added by the donor/creator that contribute significant meaning or because the entire computer will be required to access and transfer files), describe it as either “computer” or “laptop computer." Consult with the digital archivist if you are unsure of which term to use.

Apart from exceptional cases, you should not accession computer peripherals (monitors, keyboards, etc.), networking hardware (routers, for example), and other electronic components not used to store data unless:
*	They feature labels and markings intentionally added by the donor/creator that contribute significant meaning to the collection. These should not be labels or markings that simply denote ownership or give instruction on use or function (i.e., “Dorothy’s mouse” or “plug in here”).
*	In cases where the associated hardware is particularly old or obscure and it has been deemed likely, following consultation with a digital archivist, this equipment will be required in order to access and transfer digital files from the associated hardware.

If you have questions about whether a piece of equipment or media should be accessioned, consult with the digital archivist.

##### 3.4.1.3.1 Digital content not on physical media
In addition to accessioning any digital media following the instructions in the quick guide, check the acquisitions documentation for mention of file transfers, significant organizational or personal websites (see [11.4 Web Archives](<https://github.com/rose-collectionservices/collection-services-manual/tree/master/11-FORMAT%20SPECIFIC%20PROCEDURES#114-web-archives>) for selection criteria), or other digital content not already accounted for. With the digital archivist, make a plan to incorporate these materials into the accession and resource records.

##### 3.4.1.3.2 Handoff to Digital Archives
After a collection archivist documents the presence of digital content and records baseline description, a member of the Digital Archives team is responsible for retrieving the content of physical media and transferring or capturing other content. The handoff from a collection archivist to a digital archivist is accomplished by recording the digital content in the shelf list and/or discussing the collection directly. 

While the collection archivist may proceed with the workflow at this point, the collection will not be fully accessioned until a digital archivist completes the Tier 1 digital processing workflow and updates the accession and resource records accordingly. 

#### 3.4.1.4 Published Materials/Cataloging
See [10.5.2 Separating materials/Publications](<https://github.com/rose-collectionservices/collection-services-manual/tree/master/10-PHYSICAL PROCESSING#1052-publications)

### 3.4.2 Describing Collections
#### 3.4.2.1 Spawning a New Resource Record
If the newly accessioned collection establishes a new collection, follow the procedures listed in the ArchivesSpace wiki for Spawn Resource Record from Accession Record

_Confirm that the Publish button is not checked._

You will then complete the following:
*	Confirm the content in the Resource Record is correct and add required information as explained in 5.1 Levels of Arrangement and Description and according to 6.1 Finding Aids
*	Add Archival Objects to the Resource Record
	*	Individually: (see To create resource archival object records under ArchivesSpace Resource Records: Archival Objects)
		*	Required: Title, Level of Description (file), Click Publish?, Dates, Instances
		*	Optional, but suggested when adding to miscellany collections: Accession Links,
		*	Creating a Top container if a new box is created
	*	Via spreadsheet (more information found at ArchivesSpace Importing Archival Objects from Excel or CSV File)
o	Using the Rapid Data Entry (RDE) Tool (also see How to Create an RDE Template)
•	If the accession establishes a new collection, or there is a significant addition, the finding aid should be sent for review via the procedures found in 6.3 Reviewing and editing finding aids
•	Once a finding aid has been reviewed and/or all changes to the resource record have been finalized, publish the resource record.

#### 3.4.2.2 Updating a Resource Record
### 3.4.3 Finding Aid Review
## 3.5 Cataloging at the Point of Accessioning
### 3.5.1 MARC Records in OCLC Connexion
### 3.5.2 ALMA
## 3.6 Finalizing the Accession
### 3.6.1 Label and Barcode
### 3.6.2 Stacks Management
### 3.6.3 Tracking Accession Workflow and Output
## 3.7 Create the CL-2 File
### 3.7.1 Creating a Manuscript Collection File (CL-2 files)
#### 3.7.1.1 “Legacy” Electronic CL-2 File (Vital Docs Folder)
### 3.7.2 Creating an EUA Collection File (CL-2 Files)
### 3.7.3 Using Collection Files (CL-2 Files)
## 3.8 Accessioning Checklist














 


