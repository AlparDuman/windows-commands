## Registry files
| Description  | Download |
| - | - |
| Do not block shutdown with still running programs. $${\color{red}Any}$$ $${\color{red}progress}$$ $${\color{red}not}$$ $${\color{red}saved}$$ $${\color{red}will}$$ $${\color{red}be}$$ $${\color{red}lost!}$$ | [![add](https://img.shields.io/badge/File%20to-install-blue)](https://raw.githubusercontent.com/AlparDuman/windows-tweaks-collection/main/add%20autoEndTask.reg) [![undo](https://img.shields.io/badge/File%20to-undo-red)](https://raw.githubusercontent.com/AlparDuman/windows-tweaks-collection/main/del%20autoEndTask.reg) |
| Always show full context menu, instead of new windows 11 simplified | [![add](https://img.shields.io/badge/File%20to-install-blue)](https://raw.githubusercontent.com/AlparDuman/windows-tweaks-collection/main/add%20oldMenu.reg) [![undo](https://img.shields.io/badge/File%20to-undo-red)](https://raw.githubusercontent.com/AlparDuman/windows-tweaks-collection/main/del%20oldMenu.reg) |
## Powershell commands
| Describtion  | Command |
| - | - |
| Read windows activation key | `(Get-WmiObject -query ’select * from SoftwareLicensingService‘).OA3xOriginalProductKey` |
## Cmd commands
| Describtion  | Command |
| - | - |
| Repair system errors on storage device. Replace `c:` with drive letter | `chkdsk c: /f /r` |
| Display a list of all network connections, as address with port | `netstat -an` |
