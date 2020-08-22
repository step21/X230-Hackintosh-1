To use the BCM94352 wifi and bluetooth, use KextBeast to install the kext here into Library/Extensions (10.15)

BrcmPatchRAM3 from 
https://github.com/acidanthera/BrcmPatchRAM

Know issues: occationally, after reboot, the other bluetooth module (original bluetooth board on on X230) will take over (the wifi light will be off, but wifi is actually on and the original bluetooth module is actived). Under this situation, previously connected bluetooth devices will be missing. And if you try to setup the device in this situation, it will be hard for the original devices to get connected. Sometimes toggle the wifi switches may help bring the bluetooth back. Trying to remove the original bluetooth module will render the bluetooth on BCM94352 useless. 
