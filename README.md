# AN515-57
Scripts to unlock Advanced section in Acer AN515-57 Bios
### Usage:
  - Download files
  - Format an usb flash drive in FAT32 GPT
  - Copy files to the flash drive
  - Restart and boot from the USB
    * May need to disable "Safe Boot" (Bios 'f2' > Security > Set Supervisor Password ✔ > Boot > Secure Boot: Disabled ✔ > F10 "Save & Exit")


### Tools used:
 [SmokelessRuntimeEFIPatcher](https://github.com/SmokelessCPUv2/SmokelessRuntimeEFIPatcher "SmokelessRuntimeEFIPatcher") </br>
 [SREP_Config.cfg](https://github.com/SmokelessCPUv2/SREP-Community-Patches/blob/main/Configs/Predator_Triton_300_BiosUnlock.cfg "SREP_Config.cfg") - Config file from "Predator_Triton_300_BiosUnlock.cfg" looks like it works on AN515-57.

### Tested on:
AN515-57
  - i5 11400h rtx3060 BIOS V1.18 and v1.19

AN515-56
  - i5-11300H RTX 3050 BIOS v1.08 - Showing just few additional sections (GPU select, Boot sound .. No Aditional Advanced Section)
 
