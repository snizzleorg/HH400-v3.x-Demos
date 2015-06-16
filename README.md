# Demo Code for HHLib Programming Library for HydraHarp 400 
Version 3.0  
PicoQuant GmbH - October 2014  



## Introduction

The HydraHarp 400 is a TCSPC system with USB interface. 
The system requires a 686 class PC with USB 2.0/3.0 host controller,
1024 MB of memory and at least 1 GHz CPU clock. The HydraHarp 
software is suitable for Windows XP, Vista, 7, and 8.
The programming library is a DLL with demos for various programming 
languages. Please refer to the manual (PDF) for instructions.


## Disclaimer

PicoQuant GmbH disclaims all warranties with regard to this software 
and associated documentation including all implied warranties of 
merchantability and fitness. In no case shall PicoQuant GmbH be 
liable for any direct, indirect or consequential damages or any material 
or immaterial damages whatsoever resulting from loss of data, time 
or profits arising from use or performance of this software.


## License and Copyright Notice

With the HydraHarp hardware product you have purchased a license to use 
the HydraHarp software. You have not purchased other rights to the software. 
The software is protected by copyright and intellectual property laws. 
You may not distribute the software to third parties or reverse engineer, 
decompile or disassemble the software or part thereof. You may use and 
modify demo code to create your own software. Original or modified demo 
code may be re-distributed, provided that the original disclaimer and 
copyright notes are not removed from it. Copyright of the manual and 
on-line documentation belongs to PicoQuant GmbH. No parts of it may be 
reproduced, translated or transferred to third parties without written 
permission of PicoQuant GmbH. 


## Trademark Disclaimer

HydraHarp, PicoHarp, TimeHarp and NanoHarp are registered trademarks 
of PicoQuant GmbH. Other products and corporate names appearing in the 
product manuals or in the online documentation may or may not be registered 
trademarks or copyrights of their respective owners. They are used only 
for identification or explanation and to the ownerís benefit, without 
intent to infringe.


## What's new in this Version

Version 3.0 is an improvement release that supersedes versions 2.x. 
Please upgrade if you installed version 2.x. If you are still using 
version 1.x, please read the following notes carefully.


## What's new in version 2.0 versus 1.2

- Supports HydraHarp devices with USB 3.0 interface 
- Supports time bin widths of up to 33.5 µs and histogram time spans 
  up to 2.2 seconds. 
- Supports compressed TTTR overflow records for file size reduction at 
  low count rates. 
- Fixes some minor bugs. 
- **NOTE 1:** Version 2.0 requires a firmware update of the HydraHarp device. 
  The HydraHarp software can perform this update when it is first started.
- **NOTE 2:** This version has a new TTTR data format. 

**IMPORTANT! The firmware update requirement has consequences that you 
must observe:**

1. Once the update is performed you will no longer be able to use any 
   HydraHarp software prior to version 2.0.
2. Custom software you may have written for file import will require 
   minor adaptions for version 2.0.
3. You will no longer be able to use custom software based on HHLib.dll 
   prior to version 2.0.
4. Custom DLL-based software you may have written will require minor 
   adaptions for version 2.0.
5. In case of a power failure or computer crash during the update the 
   device may become in-operational.
6. Reverting to old firmware or repairing a disrupted update requires 
   a return to factory and may incur costs.


## Installation 

Before installation, make sure to backup any work you kept in previous
installation directories and uninstall any older versions of HHLib.
The HHLib package can be distributed on CD, via download or via email.
The setup distribution file is setup.exe.
If you received the package via download or email, it may be packed in a 
zip-file. Unzip that file and place the distribution setup file in a 
temporary disk folder. Start the installation by running setup.exe before
connecting the HydraHarp device.

The setup program will install the programming library including manual, 
and programming demos. Note that the demos create output files and must 
have write access in the folder where you run them. This may not be the 
case in the default installation folder. If need be, please adjust the 
acces permissions or copy the demos to a suitable folder.

Before uninstalling the HHLib package, please backup your measurement data 
and custom programs.
From the start menu select:  PicoQuant - HydraHarp-HHLib v2.x  >  uninstall.
Alternatively you can use the Control Panel Wizard 'Add/Remove Programs'
(in some Windows versions this Wizard is called 'Software')


## Contact and Support

https://support.picoquant.com

PicoQuant GmbH  
Rudower Chaussee 29  
12489 Berlin, Germany  
Phone +49 30 6392 6929  
Fax   +49 30 6392 6561  
