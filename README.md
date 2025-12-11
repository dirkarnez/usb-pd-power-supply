usb-pd-power-supply
===================
### Libraries
- [manuelbl/usb-pd-arduino: USB Power Delivery for Arduino](https://github.com/manuelbl/usb-pd-arduino)
  - https://github.com/manuelbl/usb-pd-arduino/blob/main/examples/TriggerBoardAdvanced/TriggerBoardAdvanced.ino
- [ReclaimerLabs/USB_PD: USB Power Delivery library](https://github.com/ReclaimerLabs/USB_PD)

### Notes
- USB PD3.0 (PPS Programmable Supply) is needed
- Actually, Controller IC controls the A Pins /B Pins to tell the PPS-adapter to output different voltages to VCC Pins

### USB Type-C Official Specification
- [USB Type-C® Cable and Connector Specification Release 2.4 | USB-IF](https://usb.org/document-library/usb-type-cr-cable-and-connector-specification-release-24)
  - https://www.usb.org/sites/default/files/USB%20Type-C%202.4%20Release%20202410.zip
  
### MCUs
- **TPS25750**
- **Cypress EZ-PD**
- STM32G0
- ~FUSB302B~
- IP2721??

### PPS
- XY-WPDT
  - [**・「XY-WPDT」ＰＤ充電器用トリガーデバイスを入手してみた : Skyzoo ヨッシーの備忘録**](https://gijin77.blog.jp/archives/33475591.html)


### Tools
- [Chromium Embedded Controller (EC) Development](https://www.chromium.org/chromium-os/ec-development/)
- [Compliance Tools | USB-IF](https://www.usb.org/compliancetools)
- [ReclaimerLabs/USB-C-Explorer: Dev board for USB-C and Power Delivery](https://github.com/ReclaimerLabs/USB-C-Explorer)

### Reference
- [USB PD Protocol Analyzer for 5 USD · manuelbl/usb-pd-arduino Wiki](https://github.com/manuelbl/usb-pd-arduino/wiki/USB-PD-Protocol-Analyzer-for-5-USD)
    - [usb-pd-arduino/examples/TriggerBoardAdvanced/TriggerBoardAdvanced.ino at main · manuelbl/usb-pd-arduino](https://github.com/manuelbl/usb-pd-arduino/blob/main/examples/TriggerBoardAdvanced/TriggerBoardAdvanced.ino)
    - [usb-pd-arduino/examples/ListCapabilities/ListCapabilities.ino at main · manuelbl/usb-pd-arduino](https://github.com/manuelbl/usb-pd-arduino/blob/main/examples/ListCapabilities/ListCapabilities.ino)
    - [usb-pd-arduino/test/VoltageChange/src/main.cpp at main · manuelbl/usb-pd-arduino](https://github.com/manuelbl/usb-pd-arduino/blob/main/test/VoltageChange/src/main.cpp)
    - [USB Power Delivery for Arduino | Hackaday.io](https://hackaday.io/project/190815-usb-power-delivery-for-arduino)
    - [Charging SEVs — A Modest Proposal called AOPD - Jan Wildeboer’s Blog](https://jan.wildeboer.net/2024/06/Charging-SEVs-A-Modest-Proposal-AODP/)
    - [Proto Board for Sink Mode · manuelbl/usb-pd-arduino Wiki](https://github.com/manuelbl/usb-pd-arduino/wiki/Proto-Board-for-Sink-Mode)
- [Search results for "USBCPD_Application_Customization_Tool" · Gallery](https://dev.ti.com/gallery/info/USBPD/USBCPD_Application_Customization_Tool/)
- [eeucalyptus/ch32v003-usbpd: Use the ch32v003 as a usb pd controller](https://github.com/eeucalyptus/ch32v003-usbpd)
    - [eeucalyptus - USB PD coding](https://eeucalyptus.net/2023-12-06-usb-pd-1.html)
    - [eeucalyptus - USB PD on the CH32V003](https://eeucalyptus.net/2024-05-13-usb-pd-2.html)
    - [cnlohr/ch32fun: Open source minimal stack for the ch32 line of WCH processors, including the ch32v003, a 10¢ 48 MHz RISC-V Microcontroller - as well as many other chips within the ch32v/x line.](https://github.com/cnlohr/ch32fun/)
- [All About USB-C: Talking Low-Level PD | Hackaday](https://hackaday.com/2023/02/14/all-about-usb-c-talking-low-level-pd/)
- [drivers/usb/fusb302/core/PD_Types.h - kernel/msm - Git at Google](https://android.googlesource.com/kernel/msm/+/android-7.1.0_r0.2/drivers/usb/fusb302/core/PD_Types.h)
- [tamarin-c/FUSB302.c at main · stacksmashing/tamarin-c](https://github.com/stacksmashing/tamarin-c/blob/main/FUSB302.c)
- [graycatlabs/usb-c-arduino: USB-C Power Delivery on Arduino](https://github.com/graycatlabs/usb-c-arduino/tree/master)
- [Using USB Power Delivery for good, not evil! #arduino #raspberrypi - YouTube](https://www.youtube.com/watch?v=PL94V6BK9jM)
- [Powering your projects using USB-C Power Delivery - YouTube](https://www.youtube.com/watch?v=iumAnPiQSj8)
- [USB Power Delivery: USB PD Safety Implementation | Renesas](https://www.renesas.com/us/en/support/engineer-school/usb-power-delivery-03-emarker-c-auth)
- [pd-buddy-python · PyPI](https://pypi.org/project/pd-buddy-python/)
- [PD Buddy Wye | Hackaday.io](https://hackaday.io/project/26263-pd-buddy-wye)
- [Gallery | PD Buddy Sink | Hackaday.io](https://hackaday.io/project/20424/gallery#cec9a5e98bb9c3080b37f26f4b965223)
- [Gallery | PD Buddy Sink | Hackaday.io](https://hackaday.io/project/20424/gallery#f98730d7c893ea698a2068b65809ce6b)
- [Tiny USB Type C Adjustable Power Supply | eclecticc](https://eclecti.cc/hardware/tiny-usb-type-c-adjustable-power-supply)
- search usb pd adjustable voltage supply
