### Windows Subsystem for Linux

First of all, you will need a Unix-bases operating system to be able to run PrivadoID issuer node. To do so, we will install and use Ubuntu.

Search for Turn Windows features on or off :

<div align="center">
    <img src="img/windowsFeatures.png" alt="windowsFeatures">
</div>

Activate Windows Subsystem for Linux and reboot your system when promped :

<div align="center">
    <img src="img/linuxSubsystem.png" alt="linuxSubsystem">
</div>

Open your terminal and install this distribution as we've had dockers stability troubles with other versions : 

```
wsl --install -d Ubuntu-24.04
```

Update the subsystem :

```
wsl --update
```


