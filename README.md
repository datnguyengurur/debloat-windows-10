# How to ?

### Open Powershell as administrator and run the command below:

```powershell
IEX (New-Object Net.WebClient).DownloadString('https://raw.githubusercontent.com/thecyberbear/debloat-windows-10/main/DeCrapify.ps1')
```



### Install OpenSSH Server on Windows with Pub key authentication
#### Frist Create a folder name .ssh in the user directory where you want to login as.
#### Second Run the command bellow (Remember change the path to correct Pub key's path)

```powershell
IEX (New-Object Net.WebClient).DownloadString('https://raw.githubusercontent.com/thecyberbear/debloat-windows-10/main/OpenSSH-Win-Config.ps1') -Install -Download -PublicKeyOnly -KeyPath "C:\Users\Administrator\.ssh\id_rsa.pub"
```
