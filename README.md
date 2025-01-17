# MilkNX, W.I.P fork of ReiNX
[![License: GPL v2](https://img.shields.io/badge/License-GPL%20v2-blue.svg)](https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html)
<a href="https://discord.gg/NxpeNwz"><img src="https://discordapp.com/api/guilds/465980502206054400/embed.png" alt="Discord Server" /></a>

*The modular switch custom firmware (forked and revived.)*

*all of this stuff relates to ReiNX as of writing this, I currently
haven't touched much, if not, anything at all, this stuff should still
apply until I get around to changing it after I learn more C among other languages*

**Usage:**


Put `ReiNX` folder on the root of your switch's SD card and run `ReiNX.bin` with your favorite fusee launcher.

**Compiling:**

You'll need devkitpro with devkitARM (along with the `devkitarm-rules` package) and run:
```
git clone --recurse-submodules https://github.com/Reisyukaku/ReiNX.git
cd ReiNX && make
```

To compile with Docker, `chmod +x docker-build.sh` and run the shell script `./docker-build.sh`. After that, just check `out` dir. This will compile without requiring installation of DevKit* dependencies.


**Features:**
* Modularity (doesn't rely on or require any SD files to run; customize SD files to your liking)

* Loads all KIPs from `/ReiNX/sysmodules/` directory

* Optional custom kernel/secmon/warmboot

* FS patches on the fly (NCA verify/cmac and optional nogc)

* Kernel patches on the fly (optional debug mode)

* Exclusive ReiNX sysmodules

* ES patch in RXP patch format (used with custom loader.kip)

**Official thread:**

**Thread is for ReiNX, I plan to make my own thread eventually
but for now, use this one**

[HERE](https://gbatemp.net/threads/official-reinx-thread.512203/)

**Official Installation guide**

**Site isn't up anymore as of writing this
don't use that link for rn, please and thanks**

[HERE](https://reinx.guide/)

**Credits:**

 Reisyukaku for ReiNX
 
 Contributers of ReiNX (and MilkNX, hopefully) for all that they've done

 Naehrwert for hardware init code and generally being helpful!

 CTCaer and st4rk for their contribution to the hardware code aswell!

 SciresM for sysmodules!

 The community for your support!
