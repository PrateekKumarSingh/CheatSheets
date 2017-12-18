# CheatSheets
CheatSheets compilation for Powershell, Python, Exchange, Sharepoint, Lync, RegEx, VSCode, GIT and more

# Download only Powershell specific CheatSheets with below oneliner - 

```PowerShell
(iwr 'https://goo.gl/J76Um4').links | ?{$_.title -Like "*Powershell*"} | %{iwr "http://github.com$($_.href)?raw=true" -OutFile $_.title -Verbose}
```
