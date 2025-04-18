# One Bug to Rule Them All: Stably Exploiting a Preauth RCE Vulnerability on Windows Server 2025 - Blackhat Asia 2025

As the security protection mechanisms of the Windows operating system are constantly being proposed and applied, it is becoming increasingly difficult to find exploitable vulnerabilities on current Windows, especially vulnerabilities that can cause preauth 0-click RCE. But, is there really no such vulnerabilities?

A few months ago, we conducted an in-depth analysis of the Windows Remote Desktop Services and we found several Preauth RCE vulnerabilities in the Remote Desktop Licensing Service, some of them will lead to unauthenticated non-sandboxed 0-click RCE.

In this talk, we will explore the attack surface of the Remote Desktop Licensing Service, focusing on the newly identified vulnerability, CVE-2024-38077, which impacts all versions of Windows Server from 2003 to 2025. Despite Microsoft's various fortifications to Windows for decades and we didn't see preauth 0-click RCE in Windows for years, we still can exploit a single memory corruption vulnerability to complete the 0-click preauth RCE on Windows. We will then share our approach to bypassing all the mitigations on the latest Windows Server 2025 and build a 0-click preauth RCE exploit by using only CVE-2024-38077.
