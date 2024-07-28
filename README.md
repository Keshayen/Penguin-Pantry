# Penguin-Pantry
This Repository was created to help me set up the basic apps that I utilise on Linux!!!

## Plans For This Repository.
* Make A Fully Automated Script That Dynamically Changes When Using Different Package Managers.
* Add Debian Distro support (Possibly In The Future).
* Make This Repo A Lot Better!!!

# Fedora Linux

## Browser
* I Currently Use The default Browser That Ships With Fedora Linux XFCE Spin Which Is FireFox.
* Install Method is via the DNF command.

      Sudo dnf install firefox

## Communication Applications
* I currently have Discord installed but I barely use Discord.

      sudo flatpak install flathub com.discordapp.Discord

## Code Editor

curl -f https://zed.dev/install.sh | sh

* I have Visual Studio install, but I might switch to another code editor.

      sudo rpm --import https://packages.microsoft.com/keys/microsoft.asc
      echo -e "[code]\nname=Visual Studio Code\nbaseurl=https://packages.microsoft.com/yumrepos/vscode\nenabled=1\ngpgcheck=1\ngpgkey=https://packages.microsoft.com/keys/microsoft.asc" | sudo tee /etc/yum.repos.d/vscode.repo > /dev/null


Add notion-repackaged to your package manager by creating the file /etc/yum.repos.d/notion-repackaged.repo with the following contents:

[notion-repackaged]
name=notion-repackaged
baseurl=https://yum.fury.io/notion-repackaged/
enabled=1
gpgcheck=0

The app can then be installed via:

sudo dnf install notion-app-enhanced
// or
sudo dnf install notion-app
sudo npm i -g asar

patch using script in repo


install pomotez

tl legacy 


flatpak --user override ch.tlaun.TL --env=TL_BOOTSTRAP_OPTIONS="-Dtl.useForce"


fastfetch
