# LSC Ongoing Ingest Policies and Procedures for Archives and Manuscripts 

* [16.1 Determining eligibility for transfer to LSC](#161-determining-eligibility-for-transfer-to-lsc1)
* [16.2 Physical processing](#162-physical-processing2)
* [16.3 Basic minimum housing guidelines](#163-basic-minimum-housing-guidelines)
* [16.4 Basic minimum description guidelines](#164-basic-minimum-description-guidelines)
* [16.5 Labels and barcoding](#165-labels-and-barcoding)
* [16.6 Sending items to the LSC](#166-sending-items-to-the-lsc)
* [16.7 Removing boxes from the LSC](#167-removing-boxes-from-the-lsc)
* [16.8 LSC ingest checklist](#168-lsc-ingest-checklist)

## 16.1 Determining Eligibility for Transfer to LSC<a href="#anchor1"><sup>1</sup></a>

LSC is the preferred storage location for most types of collection materials and will be the default storage location for newly acquired manuscript and archival collections larger than 10 boxes, though smaller collections may also be selected for offsite storage.

No glass-based photographic material including glass-plate negatives, lantern slides, daguerreotypes, ambrotypes, and other cased images are eligible for transfer. 

No collection material that has active or previously treated mold can be transferred.  

## 16.2 Physical Processing<a href="#anchor2"><sup>2</sup></a>
 
In order for material to be safely transferred to the LSC and easily identifiable once it is there all boxes must be clearly and accurately labeled and in containers that are both ingestible by the LSC and provide adequate support and protection for the material during transfer.   

## 16.3 Basic Minimum Housing Guidelines

* Boxes containing archival materials must have adequately fitting lids.  
* Flat boxes should have lids the cover the entire box; if these boxes have half-lids that do not cover the entire box, these lids must be tied-down.  
* Records center boxes must have intact handles.  
* To the extent possible, flat boxes should also be over 3 inches tall.
* Boxes must be under 40lbs in weight.
* Boxes with archival materials must be packed fully or with spacers or by other means to ensure materials are secure through transit.  

## 16.4 Basic Minimum Description Guidelines

**For archival materials:**

* Collection-level catalog (MARC) records that includes standard required notes fields (abstract, restrictions, language, summary, etc.) and has associated item records for each container being sent to the LSC is required.
* Collection-level finding aid with complete required notes fields per DACS.
* Box-level inventory that includes basic description of format and estimated date range is **required**. General content description at the box-level and a folder-list is **preferred**.   

## 16.5 Labels and Barcoding

All boxes must be labeled.  All labels need to include owning library, Collection Number, Title, and Box Number. 

All boxes going to the LSC must be barcoded, and the barcodes will need to be added to both Alma and the Finding aid. 

Barcodes should be placed above (preferred) or adjacent to the container label as follows:  

| Container             | Barcode location                                                                                                                                                                                                                                                                                                                                                                      |
|-----------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Record center cartons | On center above container label, below box lid.                                                                                                                                                                                                                                                                                                                                       |
| Document boxes        | On bottom center of attached box lid, above container label.                                                                                                                                                                                                                                                                                                                          |
| Flat/oversize boxes   | At a minimum, one label/barcode adjacent to box label on outward facing side of box; Preferably, two labels/barcodes adjacent to box labels on adjacent sides of box (one on a short side, the other on a long side).                                                                                                                                                                 |
| Oversize folders      | Adjacent to folder label (preferably located on open side of folder); For oversize folders (architectural drawings), I’d like to recommend we change the location of the barcodes as they will increase the height of the folders. I recommend we alternate to left, middle and then right. I think the label can remain constant. We typically put them on the right but can change. |
| Other                 | Above or adjacent to box label, below box lid if unattached.                                                                                                                                                                                                                                                                                                                          |

First, affix the barcode the box, placing it according to the physical handling recommendations listed above.  Always use a barcode protector strip to reinforce the barcode and prevent damage to the barcode.   

As you barcode, place one (or, in the case of flat boxes, 2) barcodes on the container and the duplicate copy of the barcode on the barcode sheet.  Once the barcode sheet(s) is completed it will be placed in a folder and filed.  

Add the barcodes to the Alma record. To do this, first create a holdings record for the collection.  The holdings record should have MARBL in subfield b of the 852 field and MSSTK in subfield c if the collection is remaining onsite, or LSC in subfield b and RSTORM in subfield c if the collection is going to the LSC.  If a collection is split between the locations you will need to make two holdings records, one for each holdings location.  The record will look like this:  

![Figure 1: Alma holdings record](/16-LSC%20TRANSFER%20POLICIES%20AND%20PROCEDURES/Images/Figure1.jpg "Alma holdings record")

Then add item records to that holdings record for each item in the collection.  Item records will need to include the barcode, a material type of Mixed Materials, an item policy of “Non-circ, reading RM Only” and the box number should be in the Description field.  The record will look like this: 

![Figure 2: Alma item record](/16-LSC%20TRANSFER%20POLICIES%20AND%20PROCEDURES/Images/Figure2.jpg "Alma item record")

Once all barcodes are entered into Alma you will need to wait overnight and then you can run the barcode script to insert the barcodes into the EAD finding aid for the collection.<a href="#anchor3"><sup>3</sup></a>

## 16.6 Sending Items to the LSC

Make sure the holdings record in Alma indicates the LSC as the holding library and the sublocation as RSTORM (Rose- Storage-Manuscripts).  The 852 field of your holdings record should look like this: 

![Figure 3: 852 field](/16-LSC%20TRANSFER%20POLICIES%20AND%20PROCEDURES/Images/Figure3.jpg "852 field")

Update the shelf list with the new LSC location.

If it is not a brand new acquisition (so a collection that has been on site and available to researchers for a while) then post a notice in the Collections channel on Slack to let people know that the collection is moving offsite.

Update finding aid to include the new location in the access restrictions note: 

``	
<accessrestrict encodinganalog="506">
		<head>Restrictions on Access</head>
		<p>Unrestricted access.</p>
		<p>Collection stored off-site. Researchers must contact the Rose Library in advance to access this collection.</p>
	</accessrestrict>
	``
	
You will need to wait 24 hours after changing the Alma holdings record to an LSC location before you can send the physical boxes offsite (this will ensure that the automated script that loads new barcodes into the LSC inventory control system has time to run and the new barcodes get into the system). 

**Put boxes on the designated shelving in the CTR.**

If you have oversized boxes that are 20x24 or larger, email Nathan to alert him that there are oversized boxes slated for pickup. 

## 16.7 Removing Boxes from the LSC

If a barcode needs to be removed from the LSC, email the LSC listserv with the barcode(s) that need to be removed.  

If the barcode needs to be removed from Alma right click on the "actions" button in the item list and select "withdraw" to remove the item record.

## 16.8 LSC Ingest Checklist

![Figure 4: LSC Ingest Checklist](/16-LSC%20TRANSFER%20POLICIES%20AND%20PROCEDURES/Images/LSC-Ingest-checklist.jpg "LSC Ingest Checklist")


*Footnotes:*

<a id="anchor1">[1]</a> For a full set of guidelines and criteria for sending material to the LSC please see the Rose-LSC Policy and Criteria Document [LINK] and [16.3 Basic Minimum Housing Guidelines](#163-basic-minimum-housing-guidelines).

<a id="anchor2">[2]</a> Additional details on physical processing requirements can be found in the Rose Library LSC Physical Processing Requirements document and the LSC Policy Decision Document- Physical Processing of Materials.

<a id="anchor3">[3]</a> Detailed instructions for running this script are included in the EAD manual.