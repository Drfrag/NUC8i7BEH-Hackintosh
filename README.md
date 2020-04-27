# NUC8i7BEH-Hackintosh
This project is for people who have a NUC817BEH and want to use it as if it were a Mac, specifically a Mac Mini.
My goal here is not to teach you how to install Mac OS X on your machine, but to provide an EFI that was tested on the Catalina 10.15.5 version and is quite stable.
We have all the USB ports working, including the power supply in one of the ports even when the computer is at rest or completely off, USB C and Thunderbolt port (needs to be plugged in before starting the boot).
The audio works using HDMI port, Bluetooth or the p2 output.
The built in microphone is activated and we still have the option of using an external microphone through the p2 combo jack.
This version also has Bluetooth enabled and fully functional and also the SD card reader.
Intel wifi card is not yet supported in Mac OS X in a stable way, so it must be disabled in the BIOS.
I suggest that you modify the SerialNumber, BoardSerialNumber, MLB and ROM using the Clover Configurator in order to enable the Messaging and FaceTime services.
