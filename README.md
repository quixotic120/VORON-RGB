# VORON-RGB

a fork to collect my changes to the Voron design. WIP at this point and untested but the changes are somewhat minor

##changes

increased volume - 300x300x300 (ish, lose some z axis as described below)

_bed supports_

modular steps updated to support anti-backlash delrin leadscrew nuts

_electronics_

currently using RADDS 1.5 w/ silentstepsticks but hopefully will be using my version of RAMPS-FD soon (once the kinks are worked out, on my git). Have modded the RADDS a bit with better headers and a converter for the RRD-graphic LCD

_color mixing hotend support_

added mount for the diamond hotend, different extruder design and 3 extruders for color mixing purposes (hopefully 5 soon for full color!). Kept it in line with the modular format used so it should be fairly easy to swap in a different hotend (I have an extra e3dv6-lite for this). 2 reasons: 1 being the diamond brings a lot of complexity so if it's not needed I prefer to avoid it and 2 being that the diamond is HUGE and you lose a bit of z axis as a result

_software_

using repetier instead of marlin for color mixing and due board support

##TODO:
Printer enclosure
RADDS enclosure - would like an enclosure that could hold RADDS, due, a pi zero for octoprint, and a header for powering accessories. Ideally in the style of the voron RAMPS enclosure
Camera mount

# VORON  
![](https://raw.githubusercontent.com/mzbotreprap/VORON/master/Resources/img/voron_assembly.png)

Reddit: [/r/voroncorexy](https://www.reddit.com/r/voroncorexy/)

Firmware, plans, and parts for VORON RepRap printer

## Updates:  

_Apr 30, 2016:_  
REV C Parts are pushed (STL and STEP). Parts included in this release:  
- Improved Bed Carriage  
- V1-to-REV C leadscrew adapter (for those who already printed v1)  
- Improved RAMPs Case  
- Improved Power Box (and mirror of v1 as default)  

_Apr 22, 2016:_  
Massive update to the manual. All motion system are done. Next is filamnt systems, and wiring. 
Also, added a BSP adapter for E3D Titan.

In other news, we have a sub-reddit now! Link at the top of the page.

_Apr 19, 2016:_  
Updated the BOM to reflect the REV B components. Link updated.

_Apr 17, 2016:_  
REV B Carriage is up. Belt tensioning every each way. I've cleaned up the folder to get rid of some older stuff nobody should be using now anyway.  
Description of changes here: http://imgur.com/a/EneHq

_Apr 15, 2016:_  
Quick update: The manual stalled out due to work on REV B of the X Carriage. At I started writing down the process, I became convinced belt tensioning is a thing that needs to happen. So I'm bringing back a version of what I had on the prototype printer. New carriage will also have a better way to mount a single E3D hot end, so you don't have to take apart X Carriage to remove it.

There are a few other special projects in the works, one of them involving E3D Titan ;)  

REV B will be going up tomorrow after I have a chance to put some more QA time on it.  

_Apr  4, 2016:_  
Updated BOM to reflect some changes discussed on GitHub. Big thanks to codexmas for QA work. Checked in a PDF version of the BOM. Manual is getting closer to being finished.

_Mar 22, 2016:_  
REV A STLs are published. Updated to the X Carriage to house a blower fan. Also updated the BOM to reflect the new configuration.

_Mar 8, 2016:_  
ver1.0 of the STLs has been released. Happy printing.
