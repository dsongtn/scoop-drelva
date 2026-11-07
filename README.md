# Drelva Access — Scoop bucket

Public gateway only. No private applications, signing secrets or credentials in this repository.

## Install using Scoop

```powershell
scoop bucket add drelva https://github.com/dsongtn/scoop-drelva.git
scoop install drelva
drelva version
drelva doctor
```

The manifest pins version-specific public archives with SHA-256 hashes. No administrator privileges required for a normal per-user Scoop install.

The private server still needs OAuth public client registration and package entitlement before `drelva join` can succeed. This is not a Microsoft Store or official WinGet listing.

Remove with `scoop uninstall drelva` and `scoop bucket rm drelva`.

[Official website](https://dsongtn.github.io/drelva-distribution/) · [Preview release](https://github.com/dsongtn/drelva-distribution/releases/tag/v0.1.1).
