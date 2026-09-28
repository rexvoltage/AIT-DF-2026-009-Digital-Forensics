# Autopsy Analysis
 
## Deleted Files

Autopsy identified deleted directories within the evidence image.

Deleted folders discovered:
- Corel (3 items)
- corel draw work (47 items)
- SSH (12 items)

Additional deleted artefacts were identified within $RECYCLE.BIN.

These artefacts were marked for further recovery and examination.
 
##SSH Folder Forensic Examination Summary

#Objective

Determine the status, recoverability, and potential deletion of the folder named SSH within the provided forensic image.
Examination Method
The forensic image was loaded into Autopsy 4.23.1 and manually examined through the file system tree and file metadata views.
Findings
Folder Status
The folder SSH was located within the file system structure of the forensic image.
The folder contained several PDF documents, including:
•	Cron-Automation.pdf
•	Firewall-Configuration.pdf
•	IOC-Investigation.pdf
•	Network Configuration.pdf
•	SSH Attack Simulation.pdf
•	SSH Detection Script.pdf
•	SSH Log Investigation.pdf
•	SSH Service.pdf
•	UFW Rules.pdf
•	Validation-and-Testing.pdf
Allocation Analysis
Examination of folder and file metadata revealed:
•	File Name Allocation: Unallocated
•	Metadata Allocation: Unallocated
•	Sleuth Kit Status: Not Allocated File
The red “X” indicators displayed by Autopsy further support that the files are not currently allocated within the active file system.
Deletion Assessment
The unallocated status of both the folder entries and the contained files indicates that the SSH folder has been deleted from the active file system.
Recoverability Assessment
Several SSH files remain visible through file system metadata records.
However:
•	PDF files could not be opened successfully within Autopsy.
•	Text extraction did not return readable content.
•	External viewer functionality did not successfully display the selected PDF.
Based on the current examination, successful recovery of file contents has not yet been demonstrated.
Current Recoverability Conclusion
The most defensible conclusion at this stage is:
SSH Folder Status: Deleted
SSH Contents Status: Present within unallocated file system records
Recoverability: Undetermined
Additional extraction and recovery testing would be required before classifying the files as:
•	Recoverable,
•	Partially Recoverable, or
•	Unrecoverable.
Deletion Timeframe
A definitive deletion timestamp has not yet been identified.
Examination of the Recycle Bin did not reveal corresponding deletion records for the SSH folder. Therefore, no defensible deletion date or time can currently be established.

##Preliminary Conclusion

The SSH folder was identified within the forensic image and contains multiple PDF documents. Examination of file system metadata indicates that both the folder and its contents are unallocated, demonstrating that the folder has been deleted from the active file system. Although metadata records remain available, successful recovery of file content has not yet been demonstrated. Consequently, the recoverability of the SSH folder cannot currently be determined. No conclusive evidence has yet been identified to establish the precise timeframe of the deletion event.
 
## Recovery
 
Current Classification:
•	SSH Folder: Deleted
•	Recoverability: Undetermined
•	Deletion Timeframe: Not Yet Established




##Corel Folder Forensic Examination Summary

#Objective

Determine the status, recoverability and potential deletion of the folder named Corel within the supplied forensic image.
Examination Method
The forensic image was examined using Autopsy 4.23.1. The Corel folder structure, file system records and metadata allocation status were reviewed.
Findings
Folder Identification
The folder Corel was identified within the file system structure of the forensic image.
The folder contains a subfolder named Corel Content, which includes numerous Corel application resources and configuration components.
#Examples of identified subfolders include:
•	Adjustment Presets
•	CorelDRAW
•	Export Presets
•	Fills
•	Fonts
•	Images
•	Palettes
•	Templates

##Allocation Analysis

#Examination of the Corel folder contents revealed:
•	File Name Allocation: Unallocated
•	Metadata Allocation: Unallocated
•	Red “X” indicators displayed throughout the folder #contents
These artefacts indicate that the folder entries are no longer allocated within the active file system.

##Deletion Assessment
The unallocated status of the Corel folder structure and its contents provides evidence that the Corel folder has been deleted from the active file system.
Numerous folder records remain present within file system metadata, allowing the original structure to be examined despite deletion.

##Recoverability Assessment

The Corel directory structure remains visible through metadata records.
Multiple files and subfolders were identified during examination; however, The Corel folder is deleted, but data associated with the folder remains identifiable within file system metadata.

##Deletion Timeframe
No Recycle Bin records associated with the Corel folder were identified during the current examination.

##Consequently

A precise deletion timestamp cannot currently be determined.

##Preliminary Conclusion

The Corel folder was located within the forensic image and contains a substantial Corel application directory structure. Examination of the associated file system entries revealed that both file name allocation and metadata allocation are marked as Unallocated. This indicates that the Corel folder has been deleted from the active file system. Although the folder structure remains visible through metadata records, recoverability testing has not yet been completed. Therefore, while the folder can be classified as Deleted, its recoverability remains Undetermined pending further recovery analysis.
 

##Corel Draw Work Forensic Examination Summary


#Objective
To determine the status, recoverability, and potential deletion of the folder named Corel Draw Work within the provided forensic image.

#Examination Method
The forensic image was examined using Autopsy 4.23.1. File system artefacts, folder structures, and metadata allocation records associated with the Corel Draw Work directory were reviewed.

##Findings

#Folder Identification
The folder Corel Draw Work was successfully identified within the forensic image.
The folder contained multiple entries and associated files that remained visible through file system metadata.

##Allocation Analysis
Examination of the folder structure revealed the following characteristics:
•	Folder entries displayed red “X” indicators within Autopsy.
•	File system records were marked as Unallocated.
•	Associated metadata records were also marked as Unallocated.
These findings indicate that the folder is no longer allocated within the active file system.

#Deletion Assessment
The presence of unallocated file and metadata records provides evidence that the Corel Draw Work folder was deleted from the active file system.
Although deleted, the folder structure remains partially preserved within file system metadata and can be examined through forensic analysis.

#Recoverability Assessment
Multiple folder entries and associated artefacts remain visible after deletion.
This indicates that remnants of the folder persist within the forensic image.
However:
•	No successful file recovery or content validation has yet been performed.
•	No evidence currently confirms that deleted files can be opened or reconstructed successfully.
Consequently, the recoverability status cannot yet be conclusively determined.

##Deletion Timeframe

#During examination:
•	No corresponding Recycle Bin artefacts were identified.
•	No deletion records containing definitive timestamps were recovered.
•	No supporting MFT timeline analysis has yet been completed.
Therefore, a defensible deletion timestamp cannot currently be established.

#Conclusion
The folder Corel Draw Work was identified within the forensic image and appears to have been deleted from the active file system. This conclusion is supported by the presence of unallocated file name records, unallocated metadata records, and deleted-folder indicators displayed within Autopsy. Although the folder structure remains visible through forensic examination, recovery testing has not yet been completed. Accordingly, recoverability remains undetermined. No evidence currently available establishes the precise date or time at which the deletion occurred. 

 
##Current Classification
| Item | Classification |
|---|---|
| Corel Draw Work | Deleted |
| Folder Structure Present | Yes |
| Contents Visible in Metadata | Yes |
| Recoverability | Undermined |
| Deletion Timeframe | Not Established |

##Investigation Status 
| Target | Status |
|---|---|
| SSH | Deleted |
| Corel | Deleted |
| Corel Draw Work | Deleted |
| My Pic | Not Yet Located |
| Our Pic | Not Yet Located |
| ADDS Project | Not Yet Located |
| Deletion Timeframe | Not Yet Establish |
Therefor My Pic, Our Pic, and ADDS Project appears absent from the image.
