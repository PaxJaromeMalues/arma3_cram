# arma3_cram

<p align="center">
    <a href="https://github.com/PaxJaromeMalues/arma3_cram/releases/latest">
        <img src="https://img.shields.io/badge/Version-1.0.b.x-red.svg" alt="Version">
    </a>
	<a href="https://github.com/CBATeam/CBA_A3/releases">
        <img src="https://img.shields.io/badge/CBA-blue.svg" alt="CBA">
    </a>
    <a href="https://github.com/PaxJaromeMalues/arma3_cram/issues">
        <img src="https://img.shields.io/github/issues-raw/PaxJaromeMalues/arma3_cram.svg?label=Issues" alt="Issues">
    </a>
    <a href="https://arma3.rosenrudel.de/">
        <img src="https://img.shields.io/badge/RR-ARMA-lightgrey.svg?colorA=B19E71&colorB=1A6BB6" alt="RR">
    </a>
</p>

This script sofar requires: **ARMA3, CBA**

Sources: FSG from the BI Forums circa 2017, inspiration by Yax's ITC Land Systems, people from BI Forums and others

A script that is trying to bring anti artillery, (mortar), rocket and missle capabilities to the Vanilla Preatorian

To make this function you need to add to the local description.ext the following code:

```c
class CfgFunctions {
    #include "arma3_cram\CfgFunctions.hpp"
};
```

**Wanted Functionality**

<img src="https://i.imgur.com/B9lKGW8.png">
<img src="https://i.imgur.com/bIpXPfl.png">

**Roadmap:**

```
- Proper sound function to play alarm when incoming munitions are detected.
- Support multiple automated pools of CRAM units in different geographical locations.
- Make this into a mod with a duplicate of each factions CIWS unit.
- Tracer go red and have a HE time fuze connected to the target lead and speed.
```