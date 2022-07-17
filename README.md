Run in elevated PowerShell to ensure all rect-native-windows dependencies are installed (https://microsoft.github.io/react-native-windows/docs/rnw-dependencies):

Set-ExecutionPolicy Unrestricted -Scope Process -Force; iex (New-Object System.Net.WebClient).DownloadString('https://aka.ms/rnw-deps.ps1');

To run:

yarn

yarn start

yarn windows
