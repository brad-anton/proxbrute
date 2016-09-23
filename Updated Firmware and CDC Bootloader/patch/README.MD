<pre>
This is the proxbrute mod by Brad Antoniewicz of Foundstone(https://github.com/brad-anton/proxbrute) ported to the latest Firmware with the CDC bootloader(port by www.legacysecuritygroup.com)

Firmware Dated 9-23-2016

Instructions for patching the files so you can the compile firmware yourself:

Get the proxmark3 source from Commit: 99911e5c7b8f4a2ca870046031e3f362324c0d88
copy brute.patch to proxmark3 directory
cd into proxmark3 directory
patch -p2 < ./brute.patch

Then follow general compiling instructions listed in ../../COMPILING-INSTRUCTIONS-KALI-2016.MD

Instructions for using LF standalone proxbrute mode on the elechouse RDV2 and standard version of the proxmark3 can be found at:
https://legacysecuritygroup.com/index.php/categories/9-rfid/7-proxmark-3-emulating-hid-tags-in-standalone-mode
</pre>
