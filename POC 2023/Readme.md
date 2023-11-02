# OLE object are still dangerous today — Exploiting Microsoft Office - POC 2023



Our slides for POC 2023. 


OLE is a mechanism that allows users to create and edit documents containing items or "objects" created by multiple applications，and Microsoft Office provides an interface to support the OLE mechanism, which allows users to easily use some OLE objects in documents, such as Sound clips, spreadsheets, and bitmaps. While this design is user-friendly, the interface can load any CLSID, even if these objects are not intended for Office. This significantly expands the attack surface because any Windows machine will have thousands of COM objects designed to work in various scenarios. The presence of this attack surface has been discovered as early as 2010, and there have been many zero-day vulnerabilities in the following years. With the iteration of the windows system, many new com objects appeared in win10 and win11, but are they safe? With such questions in mind, we analyzed these COM objects and discovered 10+ new vulnerabilities, including two critical ones, which attackers could easily exploit for remote code execution in Office.


