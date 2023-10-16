# Exploiting Errors in Windows Error Reporting in 2022 - POC 2022



This is my slides for POC 2022


Windows Error Reporting (WER) provides the functionality for users to collect application faults, kernel faults and other application specific errors. Developers can use this infrastructure to receive information that can be used to improve their applications on Windows. Several years ago, a in-the-wild exploit (CVE-2019-0863) of WER made the security community start to do research on the internal of WER, and then many Logical bugs of WER have been discovered by security researchers in the recents years. Almost all of these bugs are related with the Path Redirection Attack. Attackers can abuse the junction to read/write/delete privileged filesystems then get EOP in the victim's system. To mitigate the Path Redirection Attack, Microsoft provides a Junctions Mitigation Policy to block these kinds of attacks. Nowadays, many windows services have enabled this mitigation policy which means Such kinds of bugs have become less and less. However, this does not mean that there are no other types of bugs in WER. After digging into the internal implementation of WER, we found a more subtle logical bug that has existed for many years.
In this talk, We will introduce the basic infrastructure of WER, The history of its bugs, the new bug we found and our exploitation.
