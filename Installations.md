### Installations

Please Try [this](https://github.com/ItaiPendler/PC-Setup-Script), you need to download everything there and run the chocolaty.bat with admin privleges

1. ### [Office 365](https://www.office.com)
* Click **Install Office** and choose the first option from the drop-down
* Then follow the installation instructions (Give it time)


2. ### [Oracle Driver](https://tikshuv.sharepoint.com/:u:/r/sites/CPR/Shared%20Documents/Development/%D7%94%D7%AA%D7%A7%D7%A0%D7%AA%20OracleDriver.zip?csf=1&web=1&e=35HMwm)
If you are using a client (like: [Oracle SQL Developer](https://tikshuv.sharepoint.com/:f:/r/sites/CPR/Shared%20Documents/Development/sqldeveloper-19.4.0.354.1759-x64?csf=1&web=1&e=zumnX8) use the following:

 -  Hostname: `oracledbvmpublic.westeurope.cloudapp.azure.com`
 -  Port: `1521`
 -  Service name: `CPR`

(Connection Type: Basic)      

3. ### [Visual Studio Code](https://code.visualstudio.com/docs/?dv=win)
After installing VSCode, download the [File from here](https://tikshuv.sharepoint.com/:u:/r/sites/CPR/Shared%20Documents/Development/CPR-Development-ExtensionPack-0.0.1.vsix?csf=1&web=1&e=PzrfrC). open vs code and go to the extenstions tab, click the option icon (three dots), and click 'Install from VSIX', then choose the downloaded file.

OR

run the following command in your CMD to install the workspace extensions:
`code --install-extension christian-kohler.npm-intellisense & code --install-extension CoenraadS.bracket-pair-colorizer & code --install-extension dbaeumer.vscode-eslint & code --install-extension dsznajder.es7-react-js-snippets & code --install-extension eg2.vscode-npm-script & code --install-extension esbenp.prettier-vscode & code --install-extension formulahendry.auto-close-tag & code --install-extension formulahendry.auto-rename-tag & code --install-extension msjsdiag.debugger-for-chrome & code --install-extension PKief.material-icon-theme & code --install-extension SirTori.indenticator & code --install-extension xabikos.JavaScriptSnippets & code --install-extension graphql.vscode-graphql & code --install-extension mikestead.dotenv & code --install-extension eamodio.gitlens`

* If VSCode was open when you ran the command, restart it to load the extensions (Ctrl+Shift+P -> **'Reload Window'** -> Enter)

4. ### [Git](https://git-scm.com/download/win)
* After installing Git, run the following commands in your CMD:
  1. `git config --global user.name "Firstname Lastname"`
  2. `git config --global user.email "TeudatZehut@idf.il"`
  3. `git config --global core.hooksPath hooks`


5. ### [Node](https://nodejs.org/en/download/)

#### **אם יש בעיה בסאנוד של המחשב יש להוריד את**
[זה](https://www.microsoft.com/en-us/p/waves-maxxaudio-pro-for-dell-2019/9pjppgg8tgvg?activetab=pivot:overviewtab)