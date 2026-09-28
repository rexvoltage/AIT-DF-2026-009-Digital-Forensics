# Autopsy Analysis
 
## Deleted Files

Autopsy identified deleted directories within the evidence image.

Deleted folders discovered:
- Corel Content (16 items)
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
 
## Timeline
 
Pending
 
## Examiner Notes
 
Pending
