# Apt Sources Lists

A Collection of Linux Repositories Lists for the [APT Package Manager](https://en.wikipedia.org/wiki/APT_(software)) that I Currently use for Installations.<br>
These can be found on /etc/apt/sources.list on [Debian](https://www.debian.org/)-Based Systems.

<br><br>
---
### MIRRORS
As I'm Currently Based on Portugal, these 'sources.list' files use mainly the [Mirrors](https://ftp.rnl.tecnico.ulisboa.pt/) from [the Department of Computer Science and Engineering](https://dei.tecnico.ulisboa.pt/en) of [Tecnico Lisboa](https://tecnico.ulisboa.pt/en/).


<br><br>
---
### DEBIAN

[Debian](https://www.debian.org/) Stable is the Distribution that I "Gravitate" towards when installing Linux on a Machine that i would depend on.<br>
As its name Suggests, The development of Debian's stable releases focuses on Building the most "Solid" System for Production use.<br><br>

The [File](https://github.com/Marcello-Goncalves/Apt_Sources_Lists/blob/main/Debian_Bullseye_sources.list_ULISBOA) Includes the Mirrors from [ULisboa](https://www.ulisboa.pt/) since they showed to be the Fastest to be fetched based on my Location.<br>
However I've Included other Mirrors that showed to have High Downloading Speeds (Again, Varies Based on Geographical Location.) <br>As well as the Mirrors found on the Original Installation Media.<br><br>

The Package [Sources](https://wiki.debian.org/SourcesList) Components Included:<br>
- [Main](https://www.debian.org/doc/debian-policy/ch-archive#s-main) &emsp;&emsp;&emsp;-&ensp;[DFSG](https://www.debian.org/social_contract#guidelines)-compliant software. These are the only packages considered part of the Debian distribution.
- [Contrib](https://www.debian.org/doc/debian-policy/ch-archive#s-contrib) &emsp;&emsp;-&ensp;Contains DFSG-compliant software, but have dependencies not in 'Main'.
- [Non-Free](https://www.debian.org/doc/debian-policy/ch-archive#s-non-free) &emsp;-&ensp;Contains software that does not comply with the DFSG. (e.g. Prorietary Drivers For Specific Hardware Components).<br>

<br><br>
---
### UBUNTU LTS

[Ubuntu](https://ubuntu.com/) is a Debian-Based Linux Distribution Developed and Mantained By [Canonical](https://canonical.com/).<br>
It Became one of the Most popular Linux Systems Both for Client and Server Side uses,<br>Partially due to its LTS Release schedule and Facilitated Installation Process.<br><br>

The Package [Sources](https://manpages.ubuntu.com/manpages/bionic/man5/sources.list.5.html) Components Included:<br>
- Main &emsp;&emsp;&emsp; - Officially supported software.
- Restricted &emsp; - Supported software that is not available under a completely free license.
- Universe&emsp;&emsp;- Community maintained software, i.e. not officially supported software.
- Multiverse &emsp;- Software that is not free.

