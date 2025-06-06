# Be Careful of What You Embed Demystifying OLE Vulnerabilities - NDSS 2025



Our slides for NDSS 2025. 


Microsoft Office is a comprehensive suite of productivity tools and Object Linking & Embedding (OLE) is a specification that standardizes the linking and embedding of a diverse set of objects across different applications.OLE facilitates data interchange and streamlines user experience when dealing with composite documents (e.g., an embedded Excel sheet in a Word document). However, inherent security weaknesses within the design of OLE present risks, as the design of OLE inherently blurs the trust boundary between first-party and third-party code, which may lead to unintended library loading and parsing vulnerabilities which could be exploited by malicious actors. Addressing this issue, this paper introduces OLExplore, a novel tool designed for security assessment of Office OLE objects.With an in-depth examination of historical OLE vulnerabilities, we have identified three key categories of vulnerabilities and subjected them to dynamic analysis and verification. Our evaluation of various Windows operating system versions has led to the discovery of 26 confirmed vulnerabilities, with 17 assigned CVE numbers that all have remote code execution potential.


