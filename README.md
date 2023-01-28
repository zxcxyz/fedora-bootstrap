# Intro
This is a repo to keep track of all the customizations I do to my Fedora Workstation, just to avoid searching for them again after I reinstall it or something.

# Install .bashrc from the repo
```bash
./update.sh
# reload the console or use source ~/.bashrc after that
```

# Install GPU Drivers
NVIDIA: https://rpmfusion.org/Howto/NVIDIA

# Install Codecs 
go Software -> Search -> Codec
Install every single codec you can find
this should fix videos not playing on some websites 

# Fix time in dual boot
```bash
timedatectl set-local-rtc 1
```

# Fix white menu bars with dark theme
https://ask.fedoraproject.org/t/dark-mode-but-white-menu/25070

# Install various tools
Install VSCODE, sign in with github to pull the settings
Kubectl
Docker
Kubectx - https://github.com/ahmetb/kubectx
Vagrant and VirtualBox