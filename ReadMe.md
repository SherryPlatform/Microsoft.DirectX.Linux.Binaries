# Microsoft.DirectX.Linux.Binaries

Official binaries of Microsoft Direct3D 12 for Linux extracted from Windows
Subsystem for Linux 2 (WSL 2).

## Note

Some people ask me why contains 10.0.20277.1 version's binary.

Because this is the last version for Windows Iron branch which have both arm64
and x64 version. Also, I had calculated the SHA-256 between related x64 files 
from 20277.1 and related files from Windows Server 2022 ISOs before 20348.1970,
and the results are the same.

### DirectX 12 Agility SDK Versions Reference

| Series  | Branch                                |
|---------|---------------------------------------|
| 1.616.x | [?] Selenium (rs_prerelease)          |
| 1.615.x | [?] Selenium (rs_prerelease)          |
| 1.614.x | [?] Selenium (rs_prerelease)          |
| 1.613.x | [?] Dilithium (rs_prerelease)         |
| 1.612.x | Germanium (ge_release)                |
| 1.611.x | [?] Gallium (rs_prerelease)           |
| 1.610.x | Zinc (zn_release)                     |
| 1.608.x | [?] Copper (rs_prerelease)            |
| 1.606.x | [?] Copper (rs_prerelease)            |
| 1.602.x | Nickel (ni_release)                   |
| 1.601.x | [?] Nickel (rs_prerelease)            |
| 1.600.x | [?] Nickel (rs_prerelease)            |
| 1.5.x   | Cobalt (co_release)                   |
| 1.4.x   | [?] Cobalt (rs_prerelease/co_release) |
| 1.3.x   | Iron (fe_release)                     |
| 1.2.x   | Vibranium (vb_release)                |

| Series  | Operating System                           |
|---------|--------------------------------------------|
| 1.612.x | Windows 11, version 24H2 (Build 26100)     |
| 1.612.x | Windows Server 2025 (Build 26100)          |
| 1.610.x | Windows Server, version 23H2 (Build 25398) |
| 1.602.x | Windows 11, version 23H2 (Build 22631)     |
| 1.602.x | Windows 11, version 22H2 (Build 22621)     |
| 1.5.x   | Windows 11, version 21H2 (Build 22000)     |
| 1.3.x   | Windows Server 2022 (Build 20348)          |
| 1.2.x   | Windows 10, version 22H2 (Build 19045)     |
| 1.2.x   | Windows 10, version 21H2 (Build 19044)     |
| 1.2.x   | Windows 10, version 21H1 (Build 19043)     |
| 1.2.x   | Windows 10, version 20H2 (Build 19042)     |
| 1.2.x   | Windows 10, version 2004 (Build 19041)     |

## License

Reference: https://github.com/microsoft/WSL/issues/4837#issuecomment-577435179

According to the reference, you need to comply with Microsoft Windows license
terms if you want to use these binaries.
