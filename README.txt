Charon Manifest Installer

Run:
  CharonManifestInstaller.exe

What it does:
  - Checks for updates on startup
  - Finds Steam
  - Reads Steam\config\stplug-in\{AppId}.lua
  - Downloads matching .manifest files into Steam\depotcache
  - Lets you press O to open depotcache after completion
  - Lets you press Z to preview and create Documents\AppId.zip

Source order:
  1. ManifestVault
  2. Backup repo qwe213312/k25FCdfEOoEJ42S6
  3. ManifestHub fallback when option 2 is selected

Notes:
  If Steam is installed under Program Files and Windows blocks file writes,
  run the EXE as Administrator.
