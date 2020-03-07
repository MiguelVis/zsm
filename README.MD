ZSM
===

ZSM, also known as Z80ASMUK, is a Z80 assembler for CP/M, that outputs HEX files.

I like so much this assembler, so I have recopiled every ZSM version I could find over the Internet and my own disks.

I have even contributed a bit to ZSM with code of my own, mainly patches.

![ZSM image](http://www.floppysoftware.es/images/cpm-zsm.jpg "ZSM image")

Additional tools
----------------

I have developed some companion tools, in order to have a good native development tool chain for the Z80 assembler programming language under the CP/M operating system:
- `zsmpp`: source code preprocessor for the ZSM assembler.
- `bintoasm`: converts a binary file into an assembler file for ZSM.
- `hextobin`: converts a HEX file into a binary file.
- `hextocom`: converts an HEX file into a COM file for CP/M.
- `prl`: makes PRL relocatable files from COM files.
- `prntosym`: extracts symbols from a PRN file (from ZSM v2.8+) and generates an assembler file for ZSM.
- `rsx`: manages RSX files.
- `dump`: prints file contents in hexadecimal and ascii format.

License
-------

Reading the source code of ZSM, it seems there are various custom licenses involved.

Regarding my companion tools, they are under the GPL license.