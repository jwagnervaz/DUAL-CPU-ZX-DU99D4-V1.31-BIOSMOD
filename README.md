seLASTEST FIRMWARE WILL BE ONLY HERE.
https://github.com/jwagnervaz/DUAL-CPU-ZX-DU99D4-V1.31-BIOSMOD/tree/main/LASTEST
(05/06/2023)ZX-DU99D4 V1.3
this version have Server Intel ME version 3.1.3.131

ALTERNATIVE BIOS WITH DESKTOP INTEL ME
https://github.com/jwagnervaz/DUAL-CPU-ZX-DU99D4-V1.31-BIOSMOD/tree/main/LASTEST-NEWME9
(05/06/2023)ZX-DU99D4 V1.3
This have ME 9.1.45.3000 Version and new AMIBIOS BIOS base (First port in the World)


All the other versions is for history changes.

I recomend use AFUWIN to flash.
Make your own full Bios Dump before modding.

Important: After flash the rom with AFUWIN you may get error 67.
If this happen, press power button intill the PC turn off.
Turn it on and Bios update will clear CMOS. 
this will prevent brick.

all my BIOS is compatible with 
ZX-DU99D4-V1.31,ZX-DU99D4-V1.12 (tested by @xWaRLoRDx), in theory it could work with all rev of this board till V1.31



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

1- IM NOT REPONSSABLE FOR DAMAGES IN YOUR MOTHERBOARD, SO HAVE YOUR OWN DUMP AND A PROGRAMMER CH431 IF FOR SOME REASON YOU GET A BRICK
2- DO IT IN YOUR OWN RISK.
