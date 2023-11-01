## Contents
* [Description](#description)
* [autoEndTask](#autoendtask)
* [Powershell commands](#powershell-commands)

## Description
Collection of scripts for tweaking windows

## autoEndTask
When Windows shuts down, a prompt to close programs manually can prevent this. To close them automatically, add a rule to your Windows machine with `add autoEndTask.reg`. Be warned, however, that unsaved progress from any program will be lost. If you always save your progress, this is not a problem. To remove the rule, use `del autoEndTask.reg`.

## Powershell commands
The execution of Powershell scripts is disabled by default for security reasons. Here you can copy the required code and paste it into your own Powershell terminal:
* Read Windows activation key `(Get-WmiObject -query ’select * from SoftwareLicensingService‘).OA3xOriginalProductKey`
