# PowerShell-Script-Windows-Shortcut
PowerShell Script Windows Shortcut

## Usual PowerShell exe file location

%SystemRoot%\system32\WindowsPowerShell\v1.0\powershell.exe

## PowerShell.exe Switches used in this example

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
Execute a script without loading profile script, which can be long if you have long profile scripts

## Complete command to paste in the location of the item

%SystemRoot%\system32\WindowsPowerShell\v1.0\powershell.exe -noexit -NoProfile -ExecutionPolicy Bypass -File c:\folder\script.ps1

## Example

%SystemRoot%\system32\WindowsPowerShell\v1.0\powershell.exe -noexit -NoProfile -ExecutionPolicy Bypass -File "D:\scripts\Launch-MyPowerShellScript.ps1"

## Useful links

[15 ways to bypass the PowerShell execution policy](https://blog.netspi.com/15-ways-to-bypass-the-powershell-execution-policy/)