dotfiles-windows
================

# ssh

```powershell
# Make sure you're running as an Administrator
Set-Service ssh-agent -StartupType Automatic
Start-Service ssh-agent
Get-Service ssh-agent
```

# windows terminal

```
Install-Module posh-git -Scope CurrentUser
Install-Module oh-my-posh -Scope CurrentUser
Install-Module -Name PSReadLine -AllowPrerelease -Scope CurrentUser -Force -SkipPublisherCheck

notepad $PROFILE
Import-Module posh-git
Import-Module oh-my-posh
Set-Theme Paradox
```


# chocolatey

```bash
#################
# Windows Features

choco install TelnetClient -source windowsFeatures -y

############## 
# Fonts

choco install firacode -y
choco install sourcecodepro -y

############## 
# Development

choco install dotpeek -y
choco install windbg -y
choco install ack -y

#choco install keybase -y
#choco install Gpg4win -y
#choco install yubikey-manager -y

choco install linqpad5 -y
choco install fiddler -y
choco install curl -y

choco install javaruntime -y
choco install java.jdk -y

choco install git -y
choco install git-credential-manager-for-windows -y
choco install hub -y 
choco install poshgit -y
choco install githubforwindows -y
choco install gitkracken -y 

choco install python3 -y
choco install nodejs.install -y
#choco install ruby -y
#choco install ruby.devkit -y

############
# Multimedia

choco install snagit -y
choco install camtasia -y
choco install vlc -y
choco install youtube-dl -y
choco install flashplayerplugin -y

##############
# Web Browsers

#choco install brave -v
choco install firefox -y
choco install googlechrome -y
choco install googlechrome.canary -y

choco install lastpass -y

############
# Essentials

choco install vim -y
choco install sudo -y
choco install microsoft-windows-terminal - y

choco install checksum -y

choco install 7zip -y
choco install 7zip.commandline -y

choco install foxitreader -y

choco install vscode -y
choco install visualstudiocode-insiders -y

choco install totalcommander -y
choco install rdcman -y

choco install imgburn -y
choco install deluge -y
choco install freedownloadmanager -y
choco install expandrive -y

choco install filezilla -y
choco install paint.net -y

##########
# Sysadmin

choco install sysinternals -y
choco install lockhunter -y

choco install teamviewer -y

choco install windirstat -y
choco install dumeter -y

choco install winscp -y
choco install putty -y
```
