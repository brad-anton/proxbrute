This is the proxbrute mod by Brad Antoniewicz of Foundstone(https://github.com/brad-anton/proxbrute)<br>
ported to the latest Firmware with the CDC bootloader by Corey Harding of www.legacysecuritygroup.com<br>
<br>
Firmware Dated 9-23-2016<br>
proxmark3 source from Commit: 99911e5c7b8f4a2ca870046031e3f362324c0d88<br>
<br>
Instructions for patching the files so you can the compile firmware yourself:<br>
<br>
Get the proxmark3 source from Commit: 99911e5c7b8f4a2ca870046031e3f362324c0d88<br>
copy brute.patch to proxmark3 directory<br>
cd into proxmark3 directory<br>
patch -p2 < ./brute.patch<br>
<br>
Then follow general compiling instructions from https://github.com/Proxmark/proxmark3/wiki/compiling<br>
<br>
Instructions for using this port of the proxbrute mode on the elechouse RDV2 and standard version of the proxmark3 can be found at:<br>
https://legacysecuritygroup.com/index.php/categories/9-rfid/7-proxmark-3-emulating-hid-tags-in-standalone-mode