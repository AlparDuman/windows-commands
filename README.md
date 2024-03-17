## Contents
* [autoEndTask](#autoendtask)
* [oldMenu](#oldmenu)
* [Powershell commands](#powershell-commands)

## autoEndTask
<p align="justify">Windows shutdown can sometimes be stopped by a prompt to end programs that are still running. To end them automatically, add this rule to your Windows computer by using `add autoEndTask.reg` once. Be warned, however, that unsaved progress of programs that are still running will be lost. If you always save your progress, this is not a problem. To revert, use `del autoEndTask.reg` once.</p>

## oldMenu
<p align="justify">If you do not like the new & short context menu from Windows 11, use `add oldMenu.reg` once. After sometime you get the old & full context menu without detours. To revert, use `del oldMenu.reg` once.</p>

## Powershell commands
* <p align="justify">Show Windows activation key `(Get-WmiObject -query ’select * from SoftwareLicensingService‘).OA3xOriginalProductKey`</p>
