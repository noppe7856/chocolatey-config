# Chocolatey Config
My development laptop chocolatey config

Youll need chocolatey installed first 
<code>iex ((new-object net.webclient).DownloadString('https://chocolatey.org/install.ps1'))</code>

To begin installing the packages. Run the following in powershell console
<code>((new-object net.webclient).DownloadFile('https://raw.githubusercontent.com/flimble/chocolatey-config/master/packages.config',"$env:temp\packages.config")); cinst "$env:temp\packages.config"</code>

