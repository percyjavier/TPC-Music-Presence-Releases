# Security policy

## Reporting a vulnerability

If you find a security problem in TPC Music Presence, please **do not publish it**.
Report it privately to ThePercyCorner (Discord user: `thepercycornerofficial`) with:

- a description of the problem and how to reproduce it,
- the app version (shown in the installer file name),
- your Windows version.

You will get an answer as soon as possible, and the fix will be released in a new version.

## Supported versions

Only the latest published version receives security fixes.

## How to know a download is genuine

The only official downloads are the releases of the public downloads repository.
Each release includes `SHA256SUMS.txt`. Before installing, compare the checksum:

```powershell
Get-FileHash "TPC-Music-Presence-Setup-X.Y.Z.exe" -Algorithm SHA256
```

The hash must match the one in `SHA256SUMS.txt`. If it does not, do not install it.
