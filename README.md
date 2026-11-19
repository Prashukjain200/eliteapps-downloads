# E-Lite downloads

This repository holds **only the downloadable programs** of E-Lite, the small free Windows programs at <https://eliteapps.store>. It contains no source code.

- **Newest versions:** the release called [`stable`](../../releases/tag/stable) always holds the newest zip of each program under a name that never changes, for example `seekwise-windows-x64.zip`. A link to it always gives the newest version.
- **Older versions:** each version is also kept as its own numbered release.
- **Check what you downloaded:** `SHA256SUMS.txt` in the same release lists the SHA-256 of every file. In PowerShell: `Get-FileHash .\seekwise-windows-x64.zip -Algorithm SHA256`, then compare. The website shows the same numbers.
- **No installer:** unzip anywhere and double-click the program. The programs are not signed yet, so Windows may say "Windows protected your PC" the first time; the website's Downloads page explains why and how to check a file.

Questions or problems: hello@eliteapps.store
