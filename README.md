# Windows configuration after clean install

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

## Timezone

- Start -> type "Change Time zone";
- (UTC-3:00) Brasilia;
  
## Install more programs (2)
 
- Open Windows PowerShell as :warning:**administrator**:warning:;
- Run the commands below:
  ```
  choco install docker-desktop -y
  choco install microsoft-windows-terminal -y
  choco install powertoys -y
  choco install autohotkey -y
  choco install microsoft-teams -y 
  ```
- Restart
  
## Do configurations 
  
- Configure SSH connection to Github, pull some repo to test connection;
  ```
  ssh-keygen -t rsa -b 4096 -C "mauro.anselmo.oliveira@gmail.com"
  ```
 
4. Configure keyboard from [here](https://github.com/mauroao/keyboard-layout);
5. Add keyboard "United States-International";
6. Install Visual Studio Professional 2022 and activate it;
7. Install VsVim from [here](https://marketplace.visualstudio.com/items?itemName=JaredParMSFT.VsVim2022Preview). Configure `.vsvimrc` file;
8. Install DotNet Core 3.1 SDK and Dotnet 6.0 SDK;

# Aditional items
  ```
  choco install cmder -y
  choco install vlc -y
  choco install ffmpeg -y
  ```
