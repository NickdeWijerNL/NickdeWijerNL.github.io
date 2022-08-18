---
title: "First Blog!"
date: 2022-08-18T12:00:000-04:00
categories:
  - Azure AD
tags:
  - Azure AD
  - Autopilot
  - Security
  - Intune
  - Windows 10
  - Windows 11
---

Tekst...

```powershell
$TargetFile = "C:\Program Files\Remote Desktop\msrdcw.exe"
$ShortcutFile = "$env:public\Desktop\Tredion Cloud.lnk"
$WScriptShell = New-Object -ComObject WScript.Shell
$Shortcut = $WScriptShell.CreateShortcut($ShortcutFile)
$Shortcut.TargetPath = $TargetFile
$shortcut.IconLocation="C:\Program Files\Remote Desktop\msrdc.exe"
$Shortcut.Save()
```