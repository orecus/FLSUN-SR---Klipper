# FLSUN SR - Klipper (For Robin Nano v3)

## Installation

Printer Firmware can be found here: https://github.com/makerbase-mks/Klipper-for-MKS-Boards/tree/main/MKS%20Robin%20Nano%20V3.x

1) Follow the instructions for Fluidd (https://docs.fluidd.xyz/installation/fluiddpi) or MainsailOS (https://docs.mainsail.xyz/setup/mainsail-os) on how to install it on a raspberry pi.
2) Flash the above mentioned firmware to the printer by putting it on the root of the SD-Card
3) SSH into your Fluidd or Mainsail instance and execute `ls /dev/serial/by-id/*` when the printer is online after the flash.
4) Copy the configuration file(s) to your Fluidd och MainsailOS instance and update the serial line under `[mcu]` with the output of the previous point.
5) You should now be able to connect and see the printer in Fluidd or Mainsail.
6) The printer configuration supplied here should serve as a starting point, there are more that can and should be configured, please read below and configure what is applicable.

You can follow the guide here: https://3dprintbeginner.com/klipper-on-flsun-super-racer/ for more detailed steps and instructions, change as applicable for the Nano 3 Board.
## Calibration

The below steps should be reviewed and configured as applicable.

* Probe Calibration - https://www.klipper3d.org/Probe_Calibrate.html
* Delta Calibration - https://www.klipper3d.org/Delta_Calibrate.html
* Bed Mesh - https://www.klipper3d.org/Bed_Mesh.html
* Pressure Advance - https://www.klipper3d.org/Pressure_Advance.html
* Slicers - https://www.klipper3d.org/Slicers.html
* Endstop Phase (Optional) - https://www.klipper3d.org/Endstop_Phase.html
* Resonance Compensation (Optional) - https://www.klipper3d.org/Resonance_Compensation.html