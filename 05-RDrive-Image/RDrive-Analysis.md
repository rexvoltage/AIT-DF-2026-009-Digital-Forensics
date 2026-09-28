# R-Drive Image Analysis
 
## Evidence Examination
 
### Image Information
 
| Attribute | Result |
|------------|------------|
| Image Type | R-Drive Image (.rdr) |
| Image Size | 1.36 MB (1,427,456 bytes) |
| Partitions | R&AW_CHIEF (D:) Properties |
| Capacity   | 29.2 GB (31,438,405,632 bytes) |
| Used Space | 9.93 MB (10,420,985,408 bytes) |
| File System | FAT32 |
| Partition Status | Accessible and mounted as a local disk |
 
---
 
## Verification
 
| Item | Result |
|---------|---------|
| Verification Status | Successfull |
| SHA256 | Pending |
| MD5 | Pending |
 
---
 
## Findings
The examined disk uses the GPT (GUID Partition Table) partitioning scheme and has a total capacity of approximately 953.8 GB.

Four partitions were identified:

1. UEFI System Partition (200 MB, FAT32)
2. Microsoft Reserved Partition (16 MB)
3. C: Primary Partition (952.7 GB, NTFS, BitLocker Protected)
4. Windows Recovery Partition (887 MB, NTFS)

The primary partition occupies the majority of the disk space and is protected using BitLocker encryption. 
 
---
 
## Observations
 
The drive appears to be a modern Windows installation configured with UEFI boot and GPT partitioning.

The presence of a BitLocker-protected NTFS partition indicates that user and operating system data are encrypted. Standard Windows system partitions, including EFI, MSR, and Recovery partitions, are present and appear intact.

No unusual or hidden partitions were observed during the initial examination.
 
---
 
## Interpretation
 
The partition structure is consistent with a standard Windows 10/11 installation on a GPT disk.

BitLocker encryption may restrict access to user data without the appropriate recovery key or credentials. The integrity and structure of the partition layout suggest that the disk was properly configured and contains the necessary boot and recovery environments.

Further examination should include image verification and hash validation to ensure forensic integrity.
 
---
 
## Screenshots
 
