# marlin-config

I am an occasional user of 3D printing, having originally purchased an Ender 3 quite
a few years ago, a Prusa MK3 with various upgrades, and an Ender 5 Pro during the
middle of the pandameic shutdowns mostly because that was all that was available at
the time and my other printers were not accessable.  After selling the Prusa to get
a Bambu P1P, I elected to do a minimal amount of upgrades to the Ender's (rather than
just get rid of them) to make them more useful.  Upgrading these things piecemeal means 
you pretty much have to make a custom build of the Marlin Firmware for them, and this repo 
is the end result of that process.

This repo contains configuration files for Marlin Firmware 2.1.x bugfix branch (the Marlin
branch I have found to be the most stable and useful for my specific printers), reflecting
the firmware I am using on the two Creality Ender printers I have running currently.  Marlin
supports many, many different configurations and getting everything set up right for the
exact bits you have on your printer can be time consuming.  The Marlin code itself is both clean
and clearly written, so if you are so inclined and invest the time you can make it do whatever 
you want.  Two printer configurations and compiled firmware builds are provided in this repo:

* Ender 3 Pro, with Creality 4.2.7 32-bit board, Sprite Pro extruder, CR-Touch probe with the
  Z-limit switch disconnected, dual Z lead screw upgrades, printing on a Creality glass bed
  with small metal clips.  Bed springs are the heavier yellow ones.

* Ender 5 Pro, with Creality 4.2.7 32-bit board, stock hotend, CR-Touch probe with Z-limit switch
  disabled, a dual-gear metal extruder gear assembly, heavy yellow bed springs, usually using 
  a PEI build surface sheet from the Bambu Lab X1C / P1P (they fit fine).

I use this repo to keep my personal Ender printers up to date.  The compiled firmware files may be 
useful only if you have the exact combination of motherboard, hotend, extruder, and CR-Touch probe 
on your machine.  Otherwise these may be used as a datapoint to see what combination of settings 
and firmware are tested and working for someone, and go from there to get your own setup running.

The cost of upgrading these two stock Ender printers to this configuration was about $450 CAD in 
April of 2023, plus a significant amount of time.  As an alternative in my market, you could 
also buy a Bambu P1P for $900 CAD, a Creality K1 for $800 CAD, a Sovol SV06 for $350 CAD, or a
Sovol SV06 Plus for around $480 CAD.  All of these would probably have been a far better option 
than upgrading the old Enders, but the Enders are worth next to nothing on the second hand market
and I didn't want to just discard them.  After the upgrades both are producing excellent prints,
as high or higher quality than the Bambu Lab P1P printer (albeit at a far slower speed), and are
reasonably reliable and easy to maintain.  In particular they are good at printing PETG, something
I have yet to do reliably on the Bambu P1P - it's a material that fundamently does not like to go
down fast.
