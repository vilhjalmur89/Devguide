# Pixfalcon Hardware

Pixfalcon is binary-compatible derivative of the [Pixhawk](hardware-pixhawk.md) design optimized for space-constrained applications such as FPV racers. It has less IO to allow for the reduction in size. For drones requiring high processing performance or a camera interface the [Snapdragon Flight](hardware-snapdragon.md) might be a more optimal fit.

![](images/hardware/hardware-pixfalcon.png)

## Quick Summary

  * System-on-Chip: [STM32F437](http://www.st.com/web/en/catalog/mmc/FM141/SC1169/SS1577/LN1789)
    * CPU: 180 MHz ARM Cortex M4 with single-precision FPU
    * RAM: 256 KB SRAM (L1)
  * Wifi: ESP8266 external
  * GPS: U-Blox M8
  * Video: -
  * Flow: [PX4 Flow unit](http://www.hobbyking.com/hobbyking/store/__66308__HK_Pilot32_Optical_Flow_Kit_With_Sonar.html)
  * Availability: [Hobbyking Store](http://www.hobbyking.com/hobbyking/store/__86437__PixFalcon_Micro_PX4_Autopilot_plus_Micro_M8N_GPS_and_Mega_PBD_Power_Module.html)

## Connectivity

  * 1x I2C
  * 2x UART (no flow control)
  * 8x PWM with manual override
  * S.BUS / PPM input
