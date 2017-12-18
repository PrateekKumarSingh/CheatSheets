# CheatSheets
CheatSheets compilation for Powershell, Python, Exchange, Sharepoint, Lync, RegEx, VSCode, GIT and more

# Download only Powershell specific CheatSheets with below oneliner - 

```PowerShell
(iwr "https://github.com/PrateekKumarSingh/CheatSheets/PowerShell").Links | ?{$_.title -Like "*Powershell*"} | %{iwr "http://github.com$($_.href)?raw=true" -OutFile $_.title -Verbose}
```
