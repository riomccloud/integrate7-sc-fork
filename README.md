# integrate7-sc-fork
Fork of [wkeller's](https://forums.mydigitallife.net/members/wkeller.190847) [Integrate7](https://forums.mydigitallife.net/threads/integrate7-script-%E2%80%93-automatically-slipstream-updates-and-drivers-up-to-08-2023.78722) with changes that meet my needs.

## How to use
1. Obtain an original and legitimate copy of a Windows 7 edition.
2. Download the latest version of [Integrate7](https://forums.mydigitallife.net/threads/integrate7-script-%E2%80%93-automatically-slipstream-updates-and-drivers-up-to-08-2023.78722) supported by this repository. Since the author usually deletes its previous versions, I will try to keep this fork updated as soon as possible.
3. Replace the file "Integrate7.cmd" (root directory) with the file available in this repository.
4. Move the installation media file to the Integrate7 folder.
5. Run "Integrate7.cmd" as administrator and enjoy.

## Changes
- .NET Framework 4.8 will not be integrated
- DirectX End-User Runtime will not be integrated
- The network time synchronization server has been changed to NTP.br
- Ciphering protocols older than TLS 1.2 have been deactivated
- Certificate server and issuer revocation will not be disabled
- "Map Network Drive" entry will not be hidden from the context menu of My Computer
- Low disk space warning has been retained
- The word 'Shortcut' added to shortcuts when they are created has been retained
- The default settings for displaying icons on the taskbar has been retained
- User Account Control has been kept enabled
- WBEM logs has been kept enabled
- CBS logs has been kept enabled
- Preventive CHKDSK scan service will not be disabled
- Scheduled defragmentation/optimization service of Disk Defragmenter will not be disabled
- Disk Diagnostic service will not be disabled
- Memory Diagnostic service will not be disabled
- Event Logs have been kept enabled
- Other logs have been kept enabled
- A shortcut to My Computer will not be created on the Desktop
- Small memory dumps will be created by default in crashes and blue screens of death
- Windows will wait for CHKDSK scans to fully complete before booting the system
- The default settings for screen off timer after a certain period of inactivity have been retained
- The default search engine for Internet Explorer is DuckDuckGo Lite instead of Google
- Automatic update of root certificates during installation has been kept enabled
- Unsupported OS warnings in Chromium-based browsers will not be removed
- The End-User License Agreement (EULA) for Microsoft SysInternals tools has not been accepted by default
