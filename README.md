# Windows configuration after clean install

## Windows Update

- Run all windows updates;
- Restart as many times as needed;

## Chocolatey

- Open Windows PowerShell as :warning: **administrator** :warning:;
- Run this command:
  ```
  Set-ExecutionPolicy Unrestricted -Force
  ```
- Install Choco from [here](https://chocolatey.org/install);
 
 ## Install programs
 
 ```  
  choco install googlechrome -y
  choco install notepadplusplus -y
  choco install git -y
  choco install 7zip -y
  choco install autohotkey -y
  choco install vscode -y
  choco install nvm -y
  choco install docker-desktop -y
  choco install microsoft-teams -y 
  choco install microsoft-windows-terminal -y
  choco install powertoys -y
  choco install python --version=3.9.0 -y
  ```
3. Configure SSH connection to Github, pull some repo to test connection;
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
  choco install ffmpeg -y
  ```
