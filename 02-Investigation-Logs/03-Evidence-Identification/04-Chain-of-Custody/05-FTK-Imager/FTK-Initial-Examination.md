# FTK Imager Examination

## Findings

### Image Loaded
Evidence.E01 forensic image loaded successfully for examination.

### Partitions
Single accessible partition identified containing user and application data.

### Users
No user account information identified during initial FTK examination.

### Deleted Files
Multiple deleted folders and files detected, indicated by red X markers.
Deleted content included:
| Folder | Status | Recoverable |
|.......|.........|.........|

| Corel Content | Present | Yes |
| corel draw work | Present | Yes |
| SSH | Present | Yes | 
| My pic | Absent | No |
| Our pic | Absent | No |
| ADDS Project | Absent | No |


### Notes
Available folders identified:
- Corel Content (16 files)
- corel draw work (47 files)
- SSH (12 files)
- MSI9481b.tmp (2 files)
- System Volume Information (3 files)

Folders of investigative interest:
1. SSH folder, which may contain secure shell connection information, keys, or configuration data.
2. corel draw work folder, which may contain user-created design files and project documents.
3. Corel Content folder containing Corel-related application resources and content files.

Further analysis required using Autopsy and R-Drive recovery tools to determine file contents and recover deleted artefacts.
