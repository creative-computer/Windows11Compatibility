# Windows11Compatibility

Steps to test PC for Windows 11 compatibility
- Create "c:\c3" folder if it does not already exist
- Download Windows11Compatibility.ps1 to c:\c3 and name "Windows11Compatibility.ps1"
- Press "Windows Key" and type PowerShell and select "Run as Administrator"
- In PowerShell console, change directory to c:\c3 by typing "cd c:\c3"
- Type ".\Windows11Compatibility.ps1" and press enter

Results will be:
TPM Compatible       : True or False
Processor Compatible : True or False
64 Bit OS            : True or False

For a system to be compatible with Windows 11, it must receive True for all three checks.

Source: https://www.cyberdrain.com/monitoring-with-powershell-checking-if-your-device-is-compatible-with-windows-11/
