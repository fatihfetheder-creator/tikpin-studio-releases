# TikPin Studio Releases

Official Windows release channel for TikPin Studio.

## Download

Windows installers are published only from the GitHub **Releases** section of this repository.

Official product website: https://tikpin.com

## Integrity verification

Each published Windows installer is accompanied by its version and SHA-256 checksum in the corresponding release notes. You can verify a downloaded installer in PowerShell with:

```powershell
Get-FileHash .\TikPin-Studio-Kurulum.exe -Algorithm SHA256
```

Compare the result with the SHA-256 value published for that release.

## Security

Do not download TikPin Studio installers re-uploaded by third parties. Use this repository's Releases section or the official TikPin application download flow.

## Repository scope

This repository is used only for official TikPin Studio release distribution. Application source code is maintained separately.
