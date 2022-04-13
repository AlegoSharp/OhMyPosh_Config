# OhMyPosh_Config
>winget install JanDeDobbeleer.OhMyPosh

>Install-Module PSReadLine -Force -SkipPublisherCheck

# Microsoft.PowerShell_profile.ps1
>Import-Module -Name Terminal-Icons \
>Set-PSReadLineOption -PredictionSource History \
>Set-PSReadLineOption -PredictionViewStyle ListView \
>Set-PSReadLineOption -EditMode Windows \
>oh-my-posh init powershell --config ~/AppData/Local/Programs/oh-my-posh/themes/ohmyposhv3-v2.json| Invoke-Expression
