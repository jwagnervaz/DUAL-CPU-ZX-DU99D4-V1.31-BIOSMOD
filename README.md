
THIS BIOS VERSION IS A PORT I MADE FOR OLD BOARDS WITH 4304 OR OLDER BIOS VERSION
DONT FLASH INTO A 4305 OR NEWER CAUSE IT WILL BRICK YOUR BIOS AND YOU WILL NEED CH341 FOR UNBRICK.
My port only WORKS WITH
v1.11 v1.12 and 1.31v and lower revs.

new revs  like 1.41 and others not compatible . 
if you wanna a port, considere to DONATE.


Fixes:

1 - CPU Microcode Updated for ver 0xB000040 (E5 v4) and 3D (E5 V3)

2 - UEFI boot mode fixed (CSM WORKING TOO)

3 - Memory Timmings Functions enabled

4 - REBAR support integraded IN NATIVE WAY (PORT BY ME) NEED A GPU UEFI GOP/REBAR COMPATIBLE

5 - C6 Retention Enabled

6 - ME UPDATED TO 3.1.3.131 (Latest provided by intel to this chipset C610/C612)

7 - Boot time improved (ABOUT 20 SEC) 

8 - Overclock Settings ( Take Care)

9 - RTC Wakeup Working (PORT BY ME)

10 - IMC Updated

11 - ME Information/Config Menu

12 - BIOS updated to DU994306 thanks to dump provided by https://github.com/thiagoretes (THANKS A LOT)

13 - Ram SET to AUTO, for E5 V3/V4 Compat.

14 - NUMA enable by default

15 - ASPM L1 support (PORT BY ME)

16 - RAID driver UPDATED for EFI Intel VROC for sSATA/SATA - 8.0.0.4006  AND  OROM Intel VROC for sSATA/SATA  - 6.3.0.1005 (PORT BY ME)
                                  1ST PORT IN THE WORLD FROM X399/X299 TO X99 
                                  
17 - Ethernet driver UPDATED for  EFI Realtek UNDI Driver     - 2.046    
                                  OROM Realtek Boot Agent GE  - 2.70**** (PORT BY ME)

18 - Shell Bult-in fixed (NEVER WORKED IN THIS BOARD)
                                  Tianocore EDK2 2.2 24H1 (PORTED BY ME) [(BUILD FROM)](https://github.com/tianocore/edk2/releases/tag/edk2-stable202405)

DOWNLOAD  [(HERE)](https://github.com/jwagnervaz/DUAL-CPU-ZX-DU99D4-V1.31-BIOSMOD/tree/main/PORT-VERSION-4304-OR-OLDER)

BIOS CPUID VALIDATION:
https://valid.x86.fr/n1jc19
                                  
DONATE VIA PAYPAL EMAIL: JWAGNERVAZ@MSN.COM
---

**ATTENTION!**

**Different Types of Boards:**

There are two types of ZX-DU99D4 motherboards with significant hardware differences based on their BIOS versions:

1. **For motherboards with BIOS versions equal to or older than (05/06/2023) ZX-DU99D4 DU994304:**
   - You must first backup your BIOS using FPT. Download it [here](https://github.com/jwagnervaz/DUAL-CPU-ZX-DU99D4-V1.31-BIOSMOD/blob/main/FPT/FPT.zip) (Note: AFUWIN does not create a full backup BIOS).

2. **For motherboards with BIOS versions equal to or newer than (10/30/2023) ZX-DU99D4 DU994305:**
   - You must first backup your BIOS using FPT. Download it [here](https://github.com/jwagnervaz/DUAL-CPU-ZX-DU99D4-V1.31-BIOSMOD/blob/main/FPT/FPT.zip) (Note: AFUWIN does not create a full backup BIOS).
   - These have different hardware and BIOS compatibility.

**Important Notes:**
- Flashing the wrong BIOS version can result in errors (b7) or (61). and you will need a ch341 and flip to flash your bios chip with yout backup.
- If you get error  (AF), unplug the pc from power cord and press power for 5 seconds, this will erase your CMOS.
- To identify your BIOS version, check it in your BIOS settings. hit (DEL) when turn your PC on and discover your version.

**Compatibility Update:**
- I've created a port for motherboards with BIOS versions older than (05/06/2023) ZX-DU99D4 DU994304.  [(HERE)](https://github.com/jwagnervaz/DUAL-CPU-ZX-DU99D4-V1.31-BIOSMOD/tree/main/PORT-VERSION-4304-OR-OLDER)
- This allows older motherboard owners to use newer BIOS versions like (03/06/2024)ZX-DU99D4 V1.3 DU994306  [(HERE)](https://github.com/jwagnervaz/DUAL-CPU-ZX-DU99D4-V1.31-BIOSMOD/tree/main/PORT-VERSION-4304-OR-OLDER)
-  ZX-DU99D4 DU994305 AND NEWER DONT FLASH BIOS FROM HERE. I WILL DO MODS FOR THIS VERSION SOON AS POSSIBLE.

LASTEST BIOS FOR DU994304 AND OLDERS VERSIONS  [(HERE)](https://github.com/jwagnervaz/DUAL-CPU-ZX-DU99D4-V1.31-BIOSMOD/tree/main/PORT-VERSION-4304-OR-OLDER)
---
OLDER VERSIONS BELLOW!
______________________________________________________________________
LASTEST FIRMWARE WILL BE ONLY HERE.
https://github.com/jwagnervaz/DUAL-CPU-ZX-DU99D4-V1.31-BIOSMOD/tree/main/LASTEST
(05/06/2023)ZX-DU99D4 V1.3
this version have Server Intel ME version 3.1.3.131

ALTERNATIVE BIOS WITH DESKTOP INTEL ME
https://github.com/jwagnervaz/DUAL-CPU-ZX-DU99D4-V1.31-BIOSMOD/tree/main/LASTEST-NEWME9
(05/06/2023)ZX-DU99D4 V1.3
This have ME 9.1.45.3000 Version and new AMIBIOS BIOS base (First port in the World)


All the other versions is for history changes.

I recomend use AFUWIN to flash. 
HERE (https://github.com/jwagnervaz/DUAL-CPU-ZX-DU99D4-V1.31-BIOSMOD/tree/main/TOOL%20FLASH)
Make your own full Bios Dump before modding.

Important: After flash the rom with AFUWIN you may get error 67 (b7) .
If this happen, press power button intill the PC turn off.
Turn it on and Bios update will clear CMOS. 
this will prevent brick.


YOU NEED A GPU WITH UEFI BOOT SUPPORT.
If you dont have, your Pc Will not BOOT.
check compatibility WITH GPU-Z.

all my BIOS is compatible with 
ZX-DU99D4-V1.31,ZX-DU99D4-V1.12 (tested by @xWaRLoRDx) ZX-DU99D4-V1.11 (tested by @MrPurple666), in theory it could work with all rev of this board till V1.31



Changelogs:

-------------------------------------------
Fixes:

1 - CPU Microcode Updated for ver 0xB000038 (E5 v4) and 3D (E5 V3)
 
2 - UEFI boot mode fixed

3 - Memory Timmings Functions enabled

4 - REBAR support integraded (credits to https://github.com/xCuri0/ReBarUEFI) so for use this function you need a GPU compatible and use xCuri0 application to set rebar size) 

5 - C6 Retention Enabled

6 - ME UPDATED TO 3.1.3.131 (Latest provided by intel to this chipset C610/C612) or  ME 9.1.45.3000 (Alternative BIOS)

7 - Boot time improved

8 - Overclock Settings ( Take Care)

9 - RTC Wakeup Working

10 - IMC Updated

11 - ME Information/Config Menu

12 - BIOS updated to DU994304 thanks to dump provided by https://github.com/leiskris

13 - Ram SET to AUTO, for E5 V3/V4 Compat.


-------------------------------------------

Bugs:



(These are bugs that alerdy exist on this board)

1 - Sleep mode

2 - Bad Ram Compatibility

3 - Long time to boot

4 - CMOS dont save if you loose power

5 - Desktop Ram its not compatible with V4 CPU's

6 - You tell me!




# DUAL-CPU-ZX-DU99D4-V1.31-BIOSMOD
BIOSMOD for DUAL CPU ZX-DU99D4 V1.31 



RAM SET FROM AUTO TO 2400 / 2133 or AUTO it depends from version you downloaded
Note: Microcodes updated from stock bios for Rev. 0xB000040 The build booted as you can see in ► Intel SA-00233 Patched ◄ https://valid.x86.fr/srbv9d

1- IM NOT REPONSSABLE FOR DAMAGES IN YOUR MOTHERBOARD, SO HAVE YOUR OWN DUMP AND A PROGRAMMER CH341 IF FOR SOME REASON YOU GET A BRICK
2- DO IT IN YOUR OWN RISK.
