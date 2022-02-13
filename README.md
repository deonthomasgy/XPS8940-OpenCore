# XPS8940-OpenCore

Dell XPS 8940 - OpenCore
OpenCore 0.7.8 - macOS Big Sur 11.6.3 - BIOS version 2.4.0

Shutdown/Reboot/Sleep works without any issue.

GENERATE YOUR OWN SMBIOS deets (SN/MLB/UUID/ROM) -- they are EMPTY right now!

(use genSMBIOS with iMac19,1 https://github.com/corpnewt/GenSMBIOS)

System: Dell XPS 8940

CPU: Intel i5-10400

RAM: 1x8GB DDR4-2666, 1x16GB DDR4-2666

SSD: KINGSTON SA400S37240G Media

GPU: Nvidia Quadro K2000 2GB

iGPU: UHD 630 (enabled)
VDA Decoder: Fully Supported

AirPort/WiFi: not working/untested

Audio: ALC3861 (actually ALC899)


--

USB Mapped for all front USB ports + all USB3.0 ports on the back (no USB2.0 ports due to port limit (15))

--

BIOS v2.4.0

change to AHCI instead of RAID
disable all SGX, security features
do not touch Sleep States, Performance states, SpeedShift etc. Leave them at defaults
