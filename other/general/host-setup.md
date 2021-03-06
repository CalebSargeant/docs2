# Host Setup

### Developer tools in Chrome:

* **Network** tab shows all api calls for webpage
* **Console** shows error messages

### Mac

#### List of Stuff

List of stuff to install on a \(new\) Mac:

```text
## New Mac Setup
# Install Homebrew (https://brew.sh/)
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"

# install git
brew install git

# install ansible
brew install ansible

# coreutils
brew install coreutils

# install python requests for API calls
pip3 install requirements

# install powershell (pwsh)
brew cask install powershell

# install powershell language for atom
apm install language-powershell

# Install Powershell beautifier
pwsh
Install-Module -Name PowerShell-Beautifier
# modifying file - Edit-DTWBeautifyScript C:\temp\MyFile.ps1

# install atom beautify
apm install beautify

# install atom compare-files
apm install compare-files

# Install nmap
brew install nmap

# Install pandoc (https://pandoc.org/) - usage ex. pandoc -t markdown -o output.md ~/input.docx
brew install pandoc

# Install virtualenv
pip3 install virtualenv

# Install webp to convert webp to png (for i in `ls | grep webp | cut -f 1 -d '.'`; do dwebp "$i.webp" -o "$i.png"; done)
brew install webp
```

#### Updating Bash

```text
# https://apple.stackexchange.com/questions/193411/update-bash-to-version-4-0-on-osx
brew install bash
sudo bash -c 'echo /usr/local/bin/bash >> /etc/shells'
chsh -s /usr/local/bin/bash

# open new terminal window
```

### Windows

#### PowerShell v6

```text
#$version = "6.2.3"
#$url = "https://github.com/PowerShell/PowerShell/releases/download/v$version/PowerShell-$version-win-x64.msi"
#$dest = "$ENV:UserProfile\Downloads\PowerShell-6.2.3-win-x64.msi"

#Invoke-WebRequest -Uri $url -OutFile $dest
#msiexec.exe /package PowerShell-$version-win-x64.msi /quiet ADD_EXPLORER_CONTEXT_MENU_OPENPOWERSHELL=1 ENABLE_PSREMOTING=1 REGISTER_MANIFEST=1
```

#### WSL

Windows Subsystem for Linux

```text
# Run Powershell as Administrator, run command, reboot
Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Windows-Subsystem-Linux
```

```text
# Go to Windows Store, search for Linux, install Ubuntu 18.04 LTS & run it

# Update & Upgrade
sudo apt update -y && sudo apt upgrade -y

# Install pip3
sudo apt install python3-pip -y

# Install Ansible
#pip3 install ansible

# I had to install ansible through apt
sudo apt install ansible -y

# Running a playbook
cd /mnt/d/repos/personal/ansible
ansible-playbook -i ./hosts.yml playbookname.yml
```

### Git

#### Configuration

```text
nano ~/repos/reponame/.git/config

[core]
  sshCommand = ssh -i /Users/caleb.sargeant/.ssh/github

[user]
  name = Caleb Sargeant
  email = 4991715+CalebSargeant@users.noreply.github.com
```

#### Cloning

[https://stackoverflow.com/questions/41714882/git-how-to-clone-with-ssh-key-username](https://stackoverflow.com/questions/41714882/git-how-to-clone-with-ssh-key-username)

```text
git clone git@provider.com:userName/projectName.git --config core.sshCommand="ssh -i ~/.ssh/github"
```

