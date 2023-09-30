# hackintosh-x1-yoga-gen-2
OpenCore 0.9.5 Sonoma EFI for Lenovo Thinkpad X1 Yoga Gen 
<br />
Specs:<br />
-Intel Core i7-7600U<br />
-HD 620<br />
-16GB LDDR3-2133<br />
-500GB Samsung 970 Evo Plus NVMe SSD<br />
-Intel AC-8265 Wifi+Bluetooth<br />
-Intel I219-LM Ethernet<br />
-14" 1080p IPS with Wacom Pen+Touch<br />
-Sierra EM7455 4G+ Qualcomm X7 WWAN<br />
-2 Thunderbolt 3 Port Intel Alpine Ridge Controller<br />
-Audio Connexant CX8200, Touchpad Synaptic LuxPad, TrackPoint ELAN<br />
-Synaptic Fingerprint<br />
<br />
OS Tested:<br />
-macOS 14.0 Sonoma<br />
<br />
Works:<br />
-QE/CI HD 620<br />
-Sleep/Shutdown/Restart<br />
-LAN+WiFi+Bluetooth<br />
-Touchscreen+Touchpad+Trackpoint<br />
-Audio Out+Mic in<br />
-Power management/Turbo Boost/C-state (idle)<br />
-NVMe<br />
-All shortcuts on keyboard.<br />

Not working:<br />
-WWAN (detected but can't connect).<br />
-Card Reader (makes sleep broke).<br />
-Fingerprint <br />
-All sensors<br />
-Pen (the last voodooi2c that support wacom pen (2.6.5) not compatible on Sonoma anymore)<br />
-USB-C hotplug (common problem on Thinkpad with intel gen 7/8 procie and alpine ridge thunderbolt controller)<br />

Not tested : <br />
-Thunderbolt 3<br />
-DisplayPort via Thunderbolt 3<br />
-HDMI+Audio <br />
(My laptop had corrupted thunderbolt firmware (common problem). So I couldn't test. Kindly give me some feedbacks if those work.<br />

BIOS settings :<br />
-VT-d : off<br />
-DVMT size : 64/128MB<br />
-CSM : off<br />
-boot mode : UEFI only<br />
-fastboot : off<br />
disable all security stuffs<br />
