::::: Net-War Reaver Wrapper aka NWRW :::::

A Noob Wlan WPS Hacking Tool  

Sven Wurth - dos\@net-war.de

License: GPL (v2 only)



This Tool is a wrapper for the reaver WPS Attacking Toolkit

Why this tool?

reaver is great, but there is no automatic way to prescan,decide and start the attack.

This is the reason why I wrote NWRW - Net-War Reaver Wrapper.

This code is not the nicest one, i know, but hey it't working and helps!

Have fun.


GOALS:

1. scan the available networks via "wash" (This tool is part of the reaver toolkit)

2. try to attack them! do a short reaver session aggainst all the networks
   The goal is this step is to find vulnerable wps networks.
   Why? Not all WPS wlans are vulnerable. This step is a preselection. 
   The attacking itself is slow (6-20hours), so we try to find networks for which the 
   time is a good investment.
   Example: "fritzbox" -> don't try it! the developers done a good job to implement WPS

3. After we have an overview we attack all the networks!

4. wait many hours or even days

5. Enjoy the full list with results! 


REQUIREMENTS:

-BT5r3

-Currently this tools only supports the rtl8187 device "alfa awuss036h"
(this is a cheap and great USB Wlan device, if you successfully tried other devices, please let me know)

INSTALL DOKU:
aptitude install reaver
