# Microsoft.DirectX.Linux.Binaries

Official binaries of Microsoft Direct3D 12 for Linux extracted from Windows
Subsystem for Linux 2 (WSL 2).

## Note

Some people ask me why contains 10.0.20277.1 version's binary.

Because this is the last version for Windows Iron branch which have both arm64
and x64 version. Also, I had calculated the SHA-256 between related x64 files 
from 20277.1 and related files from Windows Server 2022 ISOs before 20348.1970,
and the results are the same.

## License

Reference: https://github.com/microsoft/WSL/issues/4837#issuecomment-577435179

According to the reference, you need to comply with Microsoft Windows license
terms if you want to use these binaries.
