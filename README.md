# PowerShellCustomization

Source: https://www.youtube.com/watch?v=VT2L1SXFq9U

1)   Installare tutti i nuovi font (o solo quello che si vuole utilizzare)
2)   Installare winget (GitHub)
3)   winget install JanDeDobbeleer.OhMyPosh
4)   Riavviare Windows
5)   Impostare il font "CaskaydiaCove Nerd Font" da "Windows Terminal" per "PowerShell"
6)   Copiare in C:\Users\Simone\Documents\PowerShell il file Microsoft.PowerShell_profile.ps1
7)   Copiare in C:\Users\Simone\AppData\Local\Programs\oh-my-posh\themes il file config.json
8)   NOTA: sostituire "Simone" con il nume utente corrette nei due percorsi precedenti e all'interno del file citato al punto 6
9)   OPZIONALE: in Visual Studio Code aprire i settings premendo F1, aprire "Preferences: Open Settings (UI)" e in Editor: Font Famili aggiungere "'CaskaydiaCove NF', " (apici doppi esclusi, apici singoli e spazio inclusi)
10)  Install-Module -Name Terminal-Icons -Repository PSGallery
11)  Install-Module PSReadLine -RequiredVersion 2.2.0-beta1 -AllowPrerelease
12)  Install-Module z -AllowClobber
13)  Per visualizzare correttamente il font nel PowerShell "autonomo" copiare sul desktop il collegamento da "C:\ProgramData\Microsoft\Windows\Start Menu\Programs\PowerShell" modificare il "Tipo di Carattere" dalle proprietà e copiare "indietro" il file

