# How to ?

### Open powershell as administrator and run the command below:

```powershell
IEX (New-Object Net.WebClient).DownloadString('https://raw.githubusercontent.com/thecyberbear/debloat-windows-10/main/DeCrapify.ps1')
```

```powershell
IEX (New-Object Net.WebClient).DownloadString('https://raw.githubusercontent.com/thecyberbear/debloat-windows-10/main/OpenSSH-Win-Config.ps1') -Install -Download -PublicKeyOnly -KeyPath C:\Users\Administrator\.ssh\id_rsa.pub
```
