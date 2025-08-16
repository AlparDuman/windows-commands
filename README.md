## Registry files

| Description  | Download |
| - | - |
| Always display the full context menu instead of the new simplified context menu in Windows 11. | [![add](https://img.shields.io/badge/File%20to-apply-blue)](https://raw.githubusercontent.com/AlparDuman/windows-tweaks-collection/main/add%20oldMenu.reg) [![undo](https://img.shields.io/badge/File%20to-undo-red)](https://raw.githubusercontent.com/AlparDuman/windows-tweaks-collection/main/del%20oldMenu.reg) |

## Powershell commands

| Command | Describtion  |
| - | - |
| `(Get-WmiObject -query ’select * from SoftwareLicensingService‘).OA3xOriginalProductKey` | Retrieves the original OEM Windows product key stored in the system's BIOS or UEFI firmware, if available. |

## Cmd commands

| Command | Describtion |
| - | - |
| `chkdsk d: /f /r /x` | The D: drive is checked for errors, logical file system problems are fixed, data from bad sectors is located and recovered, and the drive is forcibly unmounted before the check to ensure safe repair. |
| `format d: /fs:NTFS /p:2` | Formats drive D: with the NTFS file system and overwrites each sector twice to completely erase all data. |
| `DISM.exe /Online /Cleanup-image /Restorehealth` | 	Checks the current Windows operating system for damage to the system image and automatically repairs any problems detected by restoring damaged files. If necessary, replacement files are usually downloaded from Windows Update. |
| `sfc /scannow` | (It is recommended to run the command `DISM.exe ...` beforehand.) Checks the integrity of all protected system files and automatically repairs damaged or missing files by replacing them with error-free copies stored in the system cache. |
| `netstat -an` | Display a list of all network connections as addresses with ports. |
