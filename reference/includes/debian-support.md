---
author: sdwheeler
ms.author: sewhee
ms.date: 06/30/2022
ms.prod: powershell
ms.topic: include
---
<!-- markdownlint-disable first-line-h1 -->
The following table is a list of currently supported PowerShell releases and the versions of Debian
they're supported on. These versions remain supported until either the version of
[PowerShell reaches end-of-support][lifecycle] or the version of
[Debian reaches end-of-life][eol-debian].

- A &#x2705; indicates that the version of the OS or PowerShell is still supported
- A &#x274c; indicates that the version of the OS or PowerShell isn't supported
- A &#x1f7e1; indicates the version of PowerShell is no longer supported on that version of the OS
- When both the version of the OS and the version of PowerShell have &#x2705;, that combination is
  supported

|   Debian    | 7.0 (LTS) |    7.1    | 7.2 (LTS-current) | 7.3 (preview) |
| ----------- | :-------: | :-------: | :---------------: | :-----------: |
| &#x2705; 11 | &#x2705;  | &#x1f7e1; |     &#x2705;      |   &#x2705;    |
| &#x2705; 10 | &#x2705;  | &#x1f7e1; |     &#x2705;      |   &#x2705;    |
| &#x2705; 9  | &#x1f7e1; | &#x1f7e1; |     &#x1f7e1;     |   &#x1f7e1;   |
| &#x274c; 8  | &#x1f7e1; | &#x274c;  |     &#x274c;      |   &#x274c;    |

PowerShell is supported on Debian for the following processor architectures.

|   Debian   |     7.0 (LTS)     | 7.2 (LTS-current) |   7.3 (preview)   |
| ---------- | :---------------: | :---------------: | :---------------: |
| Version 9+ | x64, Arm32, Arm64 | x64, Arm32, Arm64 | x64, Arm32, Arm64 |

[lifecycle]: /powershell/scripting/install/powershell-support-lifecycle
[eol-debian]: https://wiki.debian.org/DebianReleases
