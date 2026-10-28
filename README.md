# Negi — downloads

Windows 10/11 (x64) installers. This repository holds only the installers, no source code.

**Latest version:** https://github.com/Mustihaft/negi/releases/latest

Download only from this repository's releases or https://mustihaft.github.io/negi/.

Check the file before you run it. Each release lists the installer's SHA-256; in PowerShell,
`(Get-FileHash .\<installer>.exe).Hash -eq "<SHA-256 from the release>"` must print `True`.
If it prints `False`, delete the file and download it again. A matching checksum shows the file
is the one published here; it doesn't prove the software is harmless.

The installer is not code-signed yet, so Windows SmartScreen may warn. Only if the check
printed `True` and you trust this project: choose *More info*, confirm the file name, then
*Run anyway*. Never turn off Microsoft Defender or SmartScreen for Negi.
