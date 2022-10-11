# Configuration after a clean windows install

## Windows Update

- Run all windows updates;
- Restart as many times as needed;

## Chocolatey

- Open Windows PowerShell as :warning:**administrator**:warning:;
- Run this command:
  ```
  Set-ExecutionPolicy Unrestricted -Force
  ```
- Install Choco from [here](https://chocolatey.org/install);
 
 ## Install programs (1)
 
- Open Windows PowerShell as :warning:**administrator**:warning:;
- Run the commands below:
 ```  
  choco install googlechrome -y
  choco install notepadplusplus -y
  choco install git -y
  choco install 7zip -y
  choco install vscode -y
  choco install python --version=3.9.0 -y
  choco install nvm -y
  choco install powertoys -y
  choco install autohotkey -y
  
  ```
- Restart;

## Google Chrome

- Remove Edge shortcuts;
- Open Chrome;
- Make Chrome default browser;
- Turn on Sync;
- Pin Chrome;
- Login google;
- Login github;

## Keyboard

- Start -> type "Language Settings";
- Preferred Languages;
- English (United States);
- Options;
- Remove additional keyboards. There must be only one: "United States-International QUERTY";
- Configure keyboard from [here](https://github.com/mauroao/keyboard-layout);

## Timezone

- Start -> type "Change Time zone";
- (UTC-3:00) Brasilia;

## Windows Terminal

- Open Microsoft Store;
- Install Windows Terminal;

## Github

- Configure SSH connection to Github, pull some repo to test connection;
  ```
  ssh-keygen -t rsa -b 4096 -C "mauro.anselmo.oliveira@gmail.com"
  ```
- Follow instructions [here](https://gist.github.com/raduserbanescu/b5c90780a8a0fc17165e2eb42c51d4fe) and [here](https://www.timschaeps.be/post/adding-git-bash-to-windows-terminal/);
  
## Debloat

- Open Windows PowerShell as :warning:**administrator**:warning:;
- Run the commands below:
  ```
  iwr -useb https://git.io/debloat|iex
  ```
- Follow instructions and debloat all!
  > source: https://github.com/Sycnex/Windows10Debloater

## Video Tools

- Open Windows PowerShell as :warning:**administrator**:warning:;
- Run the commands below:
  ```
  choco install vlc -y
  choco install ffmpeg -y
  choco install handbrake -y
  
  ```
- Start -> type "Default Apps";
- Make VLC dafault video app;

## Don't Sleep!!

- Start -> type "Power & sleep settings";
- Tell to Windows never sleeps;

## Install Fonts

- Install NERD FONTS from [here](https://github.com/mauroao/dotfiles/blob/master/fonts);

## Dotnet Development

- Install Visual Studio Professional 2022 and activate it;
- Install VsVim from [here](https://marketplace.visualstudio.com/items?itemName=JaredParMSFT.VsVim2022Preview). Configure `.vsvimrc` file;
- Install DotNet Core 3.1 SDK and Dotnet 6.0 SDK;

## Install more programs (2)
 
- Open Windows PowerShell as :warning:**administrator**:warning:;
- Run the commands below:
  ```
  choco install docker-desktop -y
  choco install microsoft-teams -y 
  ```
- Restart



