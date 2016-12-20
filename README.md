# CheatSheets
CheatSheets compilation for Powershell, Exchange, Sharepoint, Lync, RegEx, VSCode and more

# Download only Powershell specific CheatSheets with below oneliner - 

(iwr "https://github.com/PrateekKumarSingh/CheatSheets").Links | ?{$_.title -Like "*Powershell*"} | %{iwr "http://github.com$($_.href)" -OutFile $_.title -Verbose}
