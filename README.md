# Charon Manifest Installer

Compiled C# console version of Charon Manifest Downloader.

The public GitHub update repo is intended to contain release artifacts only, not this source folder.

## Build

```powershell
dotnet publish .\CharonManifestInstaller.csproj -c Release -r win-x64 -o .\Release -p:PublishAot=true -p:StripSymbols=true
```

## Release Output

```text
Release/
  CharonManifestInstaller.exe
  README.txt
```
