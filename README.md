for a working DMG recovery, via DMCA i cannot distribute the base system files, but looking into macrecovery.py is a legal way to do it. it is quite easy and once its done you are all set.
they have a great way of doing things, allowing you to actually download the recovery files legally,
Although there are other sources, albeit legally i do not support it.

just put the EFI on the root of the disk, preferably a FAT32 USB stick. 


name a folder com.apple.recovery.boot, on the root of the drive (not inside EFI folder)



then put the basesystem.chunklist and basesystem.dmg into that com.apple.recovery.boot folder


boot from usb.

please ignore the .gitattributes

This has been tested on Samsung PM971 and Sk Hynix BC501 drives and it works. 128gb and 256gb work.

the type covers all work, including the touch ID one but it is not functional in MacOS


Battery Reporting works perfectly. 


please note you will need to add HoRNDIS.kext for phone tethering or UnPlugged, but i personally 
like to use the TP-LINK UE300 as it has a RealTek chip that doesnt need a 3rd party kext.

Even with WiFi, i highly disclaim signing into your apple ID or iServices as this will put your account at risk.


it is as close to Plug-and-Play as you can get on a hackintosh as the internal Marvell Avastar chip will never work with MacOS. a good strategy if you find a working USB to Ethernet adapter is that 
 once you click on the reinstall macOS button, yank out the USB and swap to the adapter.

the touchscreen does not work as the drivers are unstable


⚠️ I DO NOT REPRESENT MICROSOFT IN ANY WAY, SHAPE, OR FORM. THIS EFI MAY CAUSE DATA LOSS, THIS IS NOT MY RESPONSIBILITY, AND I DO NOT SAY THIS WILL WORK ON ALL SURFACE MODELS, OR SURFACE PRO 1796 MODELS! IT IS NOT MY RESPONSIBILITY FOR UEFI DAMAGE OR "BRICKING" AND I KNOWINGLY  ACCEPT NO LIABILITY IN ANY WAY, AND THIS EFI IS PROVIDED "AS-IS" The AND BY DOWNLOADING THIS PRODUCT, YOU ACCEPT THESE TERMS ⚠️
