# DD Analysis
 
## Purpose
 
Use DD for forensic image handling, copying, and verification.
 
---
 
## Activity Log
 
### Activity 001
 
#### Command Used
 sudo dd if=/dev/sdb of=/home/rexpeter/1ST_EAGLE.img bs=4M status=progress conv=noerror,sync
```bash
```
#### Source
 /dev/sdb

#### Destination
 /home/rexpeter/1ST_EAGLE.img
 
#### Date/Time
 2026-09-27T23:30:10-04:00
 
#### Hash Generated

sha256sum for 1ST_EAGLE.img
e641bd6d16d837cead2bfeb8989aa6baf2cc9398e3bac8f20f37a38645f91f69 

md5sum for 1ST_EAGLE.img
41039972fcf133168ee90dac8581fc52 

sha256sum for Evidence.E01
6216149fddf6eb7074349afaef226f02c3b246ee6c3c3ae91c5ab7adeb8c29e0 

md5sum for Evidence.E01
9e2b4bb9adf2b77b0810f8f6bb115a3f 

 
#### Result

A forensic image of the source device was successfully acquired using the DD utility. Integrity verification was performed using MD5 and SHA256 hashing. The generated hash values can be used to validate the authenticity and integrity of the acquired image during future forensic examinations. 
Pending
 
## Observations
The source device labelled 1ST EAGLE was detected as a 4.0 GB removable storage device. A complete bit-for-bit image was acquired and stored in IMG format. No read errors were observed during the acquisition process.
 
## Interpretation
The DD utility was successfully used to create a forensic image while preserving the original evidence. The generated image can be verified using cryptographic hash values and analysed with forensic tools without modifying the original media.
 
## Screenshots

