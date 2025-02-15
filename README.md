# Backup_Drives

***Backup de Drives***
Para Pós Instalação ideaol para fomatação.

***PELO CMD OU POWER SHEL COMO ADMINISTRADOR***
COLE:
```PowerShell
dism /online /export-driver /destination:C:\Nome da pasta
```
***RESTAURANDO O BACKUP DOS DRIVES***
```PowerShell
dism /online /Add-Driver /Driver:C:\nome da pasta /Recurse
```
Fim!
