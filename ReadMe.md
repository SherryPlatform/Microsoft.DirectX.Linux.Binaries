# Microsoft.DirectX.Linux.Binaries

Official binaries of Microsoft Direct3D 12 for Linux extracted from Windows
Subsystem for Linux 2 (WSL 2).

## Notes

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
| 1.1.x   | Titanium (19h1_release)               |

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
| 1.1.x   | Windows 10, version 1909 (Build 18363)     |

### Packaged Direct3D 12 versions from Windows Subsystem for Linux 2 (WSL 2)

- 2.6.0: No changes.
- 2.5.9, 2.5.8, 2.5.7, 2.5.6, 2.5.4, 2.5.1: No changes.
- 2.4.13, 2.4.12, 2.4.11, 2.4.10, 2.4.9, 2.4.8, 2.4.5, 2.4.4: No changes.
- 2.3.26, 2.3.25, 2.3.24, 2.3.22, 2.3.21, 2.3.17, 2.3.14, 2.3.13, 2.3.12: No
  changes.
- 2.3.11: Introduce DXCore 10.0.26100.1-240331-1435.ge-release.
- 2.2.4: No changes.
- 2.2.3: Introduce 10.0.26091.1-240325-1447.ge-release.
- 2.2.2, 2.2.1: No changes.
- 2.1.5, 2.1.4, 2.1.3, 2.1.1, 2.1.0: No changes.
- 2.0.15, 2.0.14, 2.0.12, 2.0.11: No changes.
- 2.0.9: Revert DXCore to 10.0.25131.1002-220531-1700.rs-onecore-base2-hyp.
- 2.0.8, 2.0.7: No changes.
- 2.0.6: Introduce Direct3D 12 1.611.1-81528511.
- 2.0.5, 2.0.4, 2.0.3, 2.0.2, 2.0.1, 2.0.0: No changes.
- 1.3.17, 1.3.15, 1.3.14, 1.3.11: No changes.
- 1.3.10: Introduce DXCore 10.0.25880.1000-230602-1350.main.
- 1.2.5, 1.2.4, 1.2.3, 1.2.2, 1.2.1, 1.2.0: No changes.
- 1.1.7, 1.1.6, 1.1.5, 1.1.3, 1.1.2: No changes.
- 1.1.0: Introduce Direct3D 12 1.608.2-61064218.
- 1.0.3, 1.0.1, 1.0.0: No changes.
- 0.70.8, 0.70.5, 0.70.4, 0.70.0: No changes.
- 0.68.4, 0.68.2: No changes.
- 0.67.6: No changes.
- 0.66.2: Introduce Direct3D 12 1.606.4.
- 0.65.3, 0.65.1: No changes.
- 0.64.0: No changes. 
- 0.61.8, 0.61.4: No changes. 
- 0.60.0: No changes.
- 0.58.3, 0.58.1, 0.58.0: No changes.
- 0.56.2: Introduce DXCore 10.0.25131.1002-220531-1700.rs-onecore-base2-hyp.
- 0.56.1: Introduce Direct3D 12 1.601.0.
- 0.51.3, 0.51.2: Not existed.
- 0.50.2: Not existed.
- 0.48.2: Not existed. 
- 0.47.1: Not existed.

### Inbox Direct3D 12 versions from Windows Subsystem for Linux 2 (WSL 2)

We know that the inbox version of Windows Subsystem for Linux has been removed
starting with Windows 11 Build 25267, which noted in
https://github.com/microsoft/WSL/issues/9355#issuecomment-1358023777.

Here are the list for inbox Direct3D 12 versions from Windows Subsystem for
Linux 2 (WSL 2):

- 10.0.22621.5699: Use the same binaries from 10.0.22621.3958 & 10.0.22621.1.
- 10.0.22621.3958: Only for DXCore binaries.
- 10.0.22621.xxxx: Work In Progress
- 10.0.22621.1635: Use the same binaries from 10.0.22621.1.
- 10.0.22621.1
- 10.0.22000.2713: Only for libd3d12.so in Direct3D 12 binaries are updated.
- 10.0.22000.2600: Only for libd3d12.so in Direct3D 12 binaries are updated.
- 10.0.22000.2360: Only for Direct3D 12 binaries.
- 10.0.22000.2359: Work In Progress
- 10.0.22000.2245: Work In Progress
- 10.0.22000.2243: Work In Progress
- 10.0.22000.1761: Work In Progress
- 10.0.22000.1757: Work In Progress
- 10.0.22000.120: Only for libD3D12Core.so in Direct3D 12 binaries are updated.
- 10.0.22000.1
- 10.0.20348.3807: Use the same binaries from 10.0.20348.2461 & 10.0.20277.1.
- 10.0.20348.2461: Only for libd3d12.so in Direct3D 12 x64 binaries are updated.
- 10.0.20348.2227: Only for libd3d12.so in Direct3D 12 x64 binaries are updated.
- 10.0.20348.1970: Only for Direct3D 12 x64 binaries.
- 10.0.20277.1: The last version for Windows Iron branch which have both full
  arm64 and x64 binaries. Also, the SHA-256 between related x64 files from
  20277.1 and related files from Windows Server 2022 ISOs before 20348.1970
  are the same.
- 10.0.19041.6159: Use the same binaries from 10.0.19041.4474 & 10.0.19041.3992
  & 10.0.19041.3636.
- 10.0.19041.4474: Only for DXCore binaries.
- 10.0.19041.3992: Only for DXCore binaries and Direct3D 12 x64 libd3d12.so.
- 10.0.19041.3636: Only for Direct3D 12 binaries. Only libD3D12Core.so exists in
  Direct3D 12 arm64 binaries. 
- 10.0.19041.3570: Work In Progress
- 10.0.19041.3393: Work In Progress
- 10.0.19041.3391: Work In Progress
- 10.0.19041.3324: Use the same binaries from 10.0.19041.1200.
- 10.0.19041.1200: Only libD3D12Core.so exists in Direct3D 12 arm64 binaries.

## License

Reference: https://github.com/microsoft/WSL/issues/4837#issuecomment-577435179

According to the reference, you need to comply with Microsoft Windows license
terms if you want to use these binaries.
