# QFM-SDK
## Introduction
- QFM SDK (Q-Face Module Software Development Kit) is a set of tools and libraries for developing applications for Q-Face modules manufactured by Suprema AI Inc.

## Revision History
- 2022.11.21 : v0.1.2 released
  - linux library files have been updated. (arm, arm64 and x86_64 based linux OS supported)
  - demo application is updated.


```
.
├── README.md
└── linux
    ├── demo
    │   ├── arm
    │   │   └── release
    │   │       ├── Q-Face_demo
    │   │       └── libQFM_SDK.so
    │   ├── arm64
    │   │   └── release
    │   │       ├── Q-Face_demo
    │   │       └── libQFM_SDK.so
    │   └── x86_64
    │       └── release
    │           ├── Q-Face_demo
    │           └── libQFM_SDK.so
    ├── include
    │   ├── QF_API.h
    │   ├── QF_Command.h
    │   ├── QF_Def.h
    │   ├── QF_Delete.h
    │   ├── QF_Enroll.h
    │   ├── QF_Error.h
    │   ├── QF_Identify.h
    │   ├── QF_Image.h
    │   ├── QF_Module.h
    │   ├── QF_Packet.h
    │   ├── QF_Serial.h
    │   ├── QF_Socket.h
    │   ├── QF_SysParameter.h
    │   ├── QF_Template.h
    │   ├── QF_Upgrade.h
    │   ├── QF_Verify.h
    │   ├── Version.h
    │   └── Version.h.in
    └── lib
        ├── arm
        │   └── release
        │       ├── libQFM_SDK.a
        │       └── libQFM_SDK.so
        ├── arm64
        │   └── release
        │       ├── libQFM_SDK.a
        │       └── libQFM_SDK.so
        └── x86_64
            └── release
                ├── libQFM_SDK.a
                └── libQFM_SDK.so

```
## Description of Files
- `libQFM_SDK.a` : static library file
- `libQFM_SDK.so` : dynamic library file

## Description of architecture
- `arm` : armv7
- `arm64` : armv8
- `x86_64` : x86_64 (amd64 or intel64)
