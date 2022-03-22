# Exploiting Windows COM/WinRT Services - Blackhat USA 2021



The Component Object Model (COM) and Windows Runtime (WinRT) are widely used in windows systems, they are often used for cross-process communication and UWP Application. Both of them provide large attack surfaces for hackers to hunt for LPE, RCE and Sandbox Escape vulnerabilities. In the past year, we have found more than 100 bugs in COM/WinRT service. We classify these vulnerabilities according to their different types (UAF, OOB READ/WRITE, Type Confusion, Arbitrary READ/WRITE). We'll share how we found these bugs and our exploit tricks for some of these bugs.

