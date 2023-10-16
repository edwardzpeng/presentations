# Exploiting vulnerbilities in ESXi - Typhooncon 2022



This is our slides for Typhooncon 2022


VMware ESXi, also called VMware ESXi Server, is a bare-metal hypervisor developed by VMware for vSphere. ESXi is one of the primary components in the VMware infrastructure software suite. It’s the industry leader for efficient architecture, setting the standard for reliability, performance, and support. SLPD is a system service of ESXi, available before authentication, run with root privilege after ESXi 5.5, enabled by default before ESXi 7.0 U2c. It was reported that attackers are targeting multiple vulnerabilities in ESXi SLPD, for example, the massive ESXiArgs ransomware attack. Succeed to exploit Vulnerability in SLP, an attacker can get the root shell in ESXi and rule all the VM on it. However, there is no discussion about how to exploit these vulnerabilities. In this representation, we will talk about multiple vulnerabilities of SLP including preauth RCE and sandbox escape, including analyzing the root cause, and how to exploit these vulnerabilities stably. In the end, we also cover some novel techniques on how to do post-exploitation on ESXI.
