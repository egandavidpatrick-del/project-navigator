## 📁 Project Navigator Supports David Egan's Extensions to the current BIM ISO 19650 standard the Revised BIM ISO 19650 Directory Structure below

```text
P:\2026 Projects
  ├── 26L001 The First Project
  |	  ├─── 00_README.txt
  |   ├─── 01_WIP
  |   ├─── 02_SHARED
  |   ├─── 03_PUBLISHED
  |   ├─── 04_ARCHIVE
  |   ├─── 05_RESOURCES
  |   └──  06_INCOMING
  ├── 26L002 The Second Project
  |   ├─── 00_README.txt
  |   ├─── 01_WIP
  |   ├─── 02_SHARED
  |   ├─── 03_PUBLISHED
  |   ├─── 04_ARCHIVE
  |   ├─── 05_RESOURCES
  |   └──  06_INCOMING
  ├── 26L003 The Third Project
  ├── 26L010 The Tenth Project
  └── 26L100 The Hundredth Project
```
```text
P:\2022 Projects
  ├── 22L001 The First Project
  |   ├─── 00_README.txt
  |   ├─── 01_WIP
  |   ├─── 02_SHARED
  |   ├─── 03_PUBLISHED
  |   ├─── 04_ARCHIVE
  |   ├─── 05_RESOURCES
  |   └──  06_INCOMING
  ├── 22L002 The Second Project
  |	  ├─── 00_README.txt
  |   ├─── 01_WIP
  |   ├─── 02_SHARED
  |   ├─── 03_PUBLISHED
  |   ├─── 04_ARCHIVE
  |   ├─── 05_RESOURCES
  |   └──  06_INCOMING
  ├── 22L003 The Third Project
  ├── 22L010 The Tenth Project
  └── 22L100 The Hundredth Project
```
```text
P:\2020 Projects
  ├── 20L001 The First Project
  |   ├─── 00_README.txt
  |   ├─── 01_WIP
  |   ├─── 02_SHARED
  |   ├─── 03_PUBLISHED
  |   ├─── 04_ARCHIVE
  |   ├─── 05_RESOURCES
  |   └──  06_INCOMING
  ├── 20L002 The Second Project
  |   ├─── 00_README.txt
  |   ├─── 01_WIP
  |   ├─── 02_SHARED
  |   ├─── 03_PUBLISHED
  |   ├─── 04_ARCHIVE
  |   ├─── 05_RESOURCES
  |   └──  06_INCOMING
  ├── 20L003 The Third Project
  ├── 20L010 The Tenth Project
  └── 20L100 The Hundredth Project
```
## 📁 David Egan's ISO 19650 CDE Directory Structure Base Standard: ISO 19650-1:2018 | Extensions: 05_RESOURCES, 06_INCOMING

```text
P:\2026 Projects
└── [26L001 PROJECT NAME]
    ├── 00_README.txt
    ├── 01_WIP
    │   ├── 01_ByOriginator
    │   │   ├── 00_ProjectAdmin
    │   │   ├── ARCH
    │   │   ├── CIVIL
    │   │   ├── LAND
    │   │   ├── MEP
    │   │   ├── STRU
    │   │   └── TECO
    │   └── 02_ByOthers
    │       ├── ARCH
    │       ├── MEP
    │       └── STRUC
    ├── 02_SHARED
    │   ├── 01_ByOriginator
    │   │   ├── ARCH
    │   │   ├── MEP
    │   │   └── STRUC
    │   └── 02_ByOthers
    │       ├── ARCH
    │       ├── MEP
    │       └── STRUC
    ├── 03_PUBLISHED
    │   ├── 01_ByOriginator
    │   └── 02_ByOthers
    ├── 04_ARCHIVE
    ├── 05_RESOURCES
    │   ├── 01_Standards
    │   │   └── Document_Issue_Register.xlsx
    │   ├── 02_Templates
    │   │   ├── Drawing_Template.dwg
    │   │   └── Sheet_Template.rvt
    │   ├── 03_CAD_Blocks
    │   ├── 04_Families
    │   └── 05_Scripts
    └── 06_INCOMING
        ├── 01_Client_Briefs
        ├── 02_Surveys
        ├── 03_Geotech
        └── 04_ThirdPartyInfo
```

## 📁 00_README.txt
```text
                    ISO 19650 PROJECT DIRECTORY STRUCTURE


DIRECTORY BREAKDOWN


01_WIP                    = WORK IN PROGRESS
                          Internal use only. Incomplete, unchecked information.
                          Path: 01_WIP/01_ByOriginator/ 01_WIP/02_ByOthers/

02_SHARED                 = SHARED FOR COORDINATION 
                          Ready for other disciplines to use. Clash checked.
                          Path: 02_SHARED/01_ByOriginator/  02_SHARED/02_ByOthers/

03_PUBLISHED              = PUBLISHED FOR CLIENT/ISSUE
                          Formal issue. Read only. Transmitted externally.
                          Path: 03_PUBLISHED/01_ByOriginator/ 03_PUBLISHED/02_ByOthers/

04_ARCHIVE                = ARCHIVE
                          Superseded and withdrawn information. Do not use.

05_RESOURCES              = PROJECT RESOURCES
                          Company standards, templates, registers, BEP.
                          Path: 05_RESOURCES/01_Standards/KEY FILE: Document_Issue_Register.xlsx lives here  
						  05_RESOURCES/02_Templates/  05_RESOURCES/03_CAD_Blocks/  05_RESOURCES/04_Familes/  
						  05_RESOURCES/05_Scripts/
                          

06_INCOMING               = INCOMING INFORMATION
                          Information received from Client and Third Parties.
                          Path: 06_INCOMING/01_Client_Briefs/ 06_INCOMING/02_Surveys/  
						  06_INCOMING/03_Geotech/  06_INCOMING/04_ThirdPartyInfo/

NOTE: This implementation includes 2 additional support folders:
David Egan introduced sections 05/06 to compliment the current ISO 19650
standard 05_RESOURCES and 06_INCOMING. These are NOT defined CDE states in ISO 19650-1:2018.
They are added to support metadata management and controlled information flow.

KEY RULES

1.  WIP → SHARED → PUBLISHED → ARCHIVE. Information only moves forward.
2.  01_ByOriginator = Navigator.  02_ByOthers = Consultants/Contractors.
3.  Never edit files in PUBLISHED or ARCHIVE.
4.  All deliverables must follow the File Naming Convention.
5.  The Document Issue Register is the single source of truth for issue status.

CONTACTS

Project Manager:
BIM Manager: 
Date Started:
```


As AEC organisations grow, these directory structures often expand into thousands of project directories distributed across shared network environments, making historical and active project retrieval increasingly difficult, time-consuming, and operationally inefficient.

The Navigator platform centralises both historical and current project directories into a structured, searchable catalogue. This catalogue can be adapted to point directly to cloud storage locations such as OneDrive or enterprise file servers, enabling AEC teams to locate project directories and associated information in seconds rather than manually navigating complex directory trees.

The system provides:

- Rapid project retrieval
- Centralised project visibility
- Improved operational continuity
- Increased accessibility to organisational knowledge
- Reduced time spent searching legacy directories and file systems

While the platform was originally developed for the AEC (Architecture, Engineering & Construction) sector, its underlying architecture is designed to support any industry in which organisations manage projects through structured directory hierarchies. This includes environments that rely on project-number-based directory systems, shared operational directories, cloud-based file repositories, or extensive historical data archives similar to the example project directory structures illustrated above.
