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
| SHA256 | 2d93b7c33b645eb1744d5e4cb8f75f7942e18e713056a7ecbea136efa10d2362 (rdrive.rdr image) |
| MD5 | 374b6812f5a320f79e0fc47b42041901 (rdrive.rdr image) |
| SHA256 | 6216149fddf6eb7074349afaef226f02c3b246ee6c3c3ae91c5ab7adeb8c29e0 (Evidence.E01) |
| MD5 | 9e2b4bb9adf2b77b0810f8f6bb115a3f (Evidence.E01) |
---
 
## Findings

The evidence image was successfully acquired and analysed as an R-Drive Image (.rdr) file.
The image contains a single mounted partition labelled R&AW_CHIEF (D:).
The partition capacity is approximately 29.2 GB.
The partition uses the FAT32 file system.
The image was successfully mounted and accessed as a local disk, indicating that the image is readable and not corrupted.
Hash values (MD5 and SHA256) were generated and recorded for integrity verification.
Verification completed successfully, confirming that the forensic image corresponds to the source evidence and has not been altered during acquisition or examination.
 
---
 
## Observations
 
The image file itself is relatively small (1.36 MB) compared to the logical partition size (29.2 GB), suggesting that the image may be compressed, sparse, metadata-based, or part of a segmented backup structure.
Only approximately 9.93 GB of the partition appears to be occupied, leaving a substantial amount of unallocated space.
The use of FAT32 indicates that the storage device may have been a removable device such as a USB flash drive, memory card, or portable storage medium.
The partition mounted without errors, indicating that the file system structure is intact and accessible.
Matching verification results and recorded hashes provide assurance that no accidental modification occurred during acquisition or examination.
 
---
 
## Interpretation
 
The forensic examination confirms that the acquired R-Drive image is a valid and forensically sound representation of the original storage media. Integrity checks were successful, demonstrating that the evidence remained unchanged throughout the imaging and verification process.
The presence of a FAT32 file system and a volume label of R&AW_CHIEF may indicate that the storage device was intended for portable data storage or transfer. The significant amount of available space suggests the possibility of recoverable deleted data or artefacts existing within unallocated areas, which may warrant further examination.
Because the image was successfully mounted and accessed, subsequent forensic analysis can be conducted on the file system contents, deleted files, metadata, timestamps, and other digital artefacts while maintaining the integrity of the original evidence.
---
 
## Screenshots
 
