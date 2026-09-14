# Kataterra

Kataterra is a Windows desktop application for selecting an area in Slovenia and preparing official spatial data for CAD and GIS workflows. The public repository contains verified Windows download packages, release notes, checksums and the issue tracker. The application source is maintained in a separate private repository.

## Download

[Download the latest Kataterra release](https://github.com/GapiThePapi/Kataterra-Downloads/releases/latest)

In **Assets**, download `Kataterra_win-x64_<version>.zip` and the matching `.sha256` file. Extract the ZIP before starting `Kataterra.exe`.

Supported platform: Windows 10 or Windows 11, 64-bit. The package is self-contained; users do not need to install .NET.

## Verify the package

PowerShell can verify the downloaded file:

```powershell
Get-FileHash .\Kataterra_win-x64_<version>.zip -Algorithm SHA256
```

The value must match the checksum published in the matching `.sha256` asset.

## Updates

Kataterra can check this public release channel from **About > Check for updates**. Optional once-daily checks can be enabled or disabled in Settings. The application never installs an update without the user's action.

## Feedback and security

- [Report a bug or suggest an improvement](https://github.com/GapiThePapi/Kataterra-Downloads/issues/new/choose)
- For a security issue, use GitHub's private **Report a vulnerability** form in the Security tab. Do not publish sensitive project data or coordinates in an issue.

This is a development build. Until the Windows executable is signed with the publisher's Authenticode certificate, Microsoft Defender SmartScreen may show an unrecognized-app warning.

Copyright © 2026 Acer Novo mesto d.o.o. All rights reserved.
