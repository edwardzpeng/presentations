# COMRACE: Detecting Data Race Vulnerabilities in COM Objects - Usenix Security 2022



Our paper and slides for Usenix Security 2022


The Microsoft Component Object Model (COM) is the foundation for many key Microsoft technologies and we develop COMRace, the first data race vulnerability detection tool for commercial off-the-shelf COM objects. COMRace targets a severe but previously overlooked flaw in the COM threading model, which makes COM objects prone to data race attacks. In COMRace, we apply static binary analyses to identify thread-unsafe interface methods in off-the-shelf COM binaries, then further verify binary analyses results with automatically synthesized proof-of-concept exploits (PoC). We have applied COMRace to 10,420 registered COM objects on the windows platform and the tool reports 186 vulnerable interface methods. COMRace automatically synthesizes 234 PoCs for 256 selected method pairs (82 unsafe methods) with conflict accesses, and there are 194 PoCs triggering race conditions. Furthermore, 145 PoCs lead to critical memory corruptions, exposing 26 vulnerabilities confirmed by the Common Vulnerabilities and Exposures (CVE) database.

