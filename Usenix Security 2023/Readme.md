# Detecting Union Type Confusion in Component Object Model - Usenix Security 2023



Our paper and slides for Usenix Security 2023


Component Object Model (COM) is a binary-interface standard for software components introduced by Microsoft in 1993. Thirty years after its first release, COM is still the basis to support many other core technologies of Microsoft. COM developers used many unions rather than structs in the coding to conserve memory in legacy computers. However, the excessive use of union architecture will most likely introduce type confusion vulnerabilities that can be taken advantage of by 100%-reliable exploits. According to our studies, the problem of union type confusion has long been overlooked and no solutions have been developed for off-the-shelf systems that employ COM.

In this paper, we propose COMFUSION, the first tool that detects union type confusion in COM. The crux is to infer union variables and their discriminants in COM binaries. This is challenging since existing type recovery techniques do not support union type in binaries. To resolve this problem, COMFUSION identifies union variables through taint propagation with the help of Microsoft Interface Definition Language (MIDL) files and then searches for union type confusion via symbolic execution. We evaluate COMFUSION on three popular releases of Windows operating system, including Windows 10 1809, Windows 10 21H2, and Windows 11 21H2. COMFUSION successfully found 36 union type confusions. Out of these, 19 type confusions have been confirmed to be capable of corrupting memory, exposing 4 confirmed CVEs.
