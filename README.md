# PowerShell-Script-Windows-Shortcut
This is a quick description about how to create a Windows Shortcut to your most used Powershell scripts.

## Usual PowerShell exe file location
Here's the universal location where you can find the Windows PowerShell executable, that we will put in 
our link:
%SystemRoot%\system32\WindowsPowerShell\v1.0\powershell.exe

## PowerShell.exe Switches used in this example
Here are some quick descriptions of the switches used in this example.
```
-noexit
```
Used to leave the PowerShell window opened after the script finishes

```
-ExecutionPolicy Bypass
```
Used to bypass the execution policy (careful with that)

```
-NoProfile
```
Execute a script without loading profile script, because it  can be long if you have long profile scripts

## Complete command to paste in the location of the item
Get your script path and file name, and add it after the ```-File``` parameter of your Powershell.exe call:

%SystemRoot%\system32\WindowsPowerShell\v1.0\powershell.exe -noexit -NoProfile -ExecutionPolicy Bypass -File c:\folder\script.ps1

## Coming soon...
Screenshots about the process