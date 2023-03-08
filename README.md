# Microchip Embedded Wi-Fi®

<a href="http://www.microchip.com/design-centers/wireless-connectivity/embedded-wi-fi"><img src="http://www.microchip.com/_images/logo.png" align="left" hspace="10" vspace="6"></a>
</br></br></br>

Microcip Embedded Wi-Fi® is a family of self-contained, low power and certified modules bringing wireless internet connectivity.

**[ATWILC1000](http://www.microchip.com/wwwproducts/en/ATWILC1000)** is IEEE 802.11 b/g/n/ IOT link controller utilizing highly optimized 802.11 and provides mulitple peripheral interfaces like SPI, and SDIO.  

**[ATWILC3000](http://www.microchip.com/wwwproducts/en/ATWILC3000)** is IEEE 802.11 b/g/n/BLuetooth Low Energy 5.0 IOT link controller utilizing highly optimized 802.11-Bluetooth coexistence protocol and provides mulitple peripheral interfaces like UART, SPI, and SDIO.

This repository provides ATWILC1000 WLAN firmware, and ATWILC3000 WLAN and BLE firmware. The baud rate of ble_firmware.bin is 115200 and flow control is disabled by default. 

Refer to the [Wi-Fi Link Controller Linux User Guide](http://ww1.microchip.com/downloads/en/DeviceDoc/ATWILC1000-ATWILC3000-Wi-Fi-Link-Controller-Linux-User-Guide-DS70005328C.pdf) for information on how to use the wireless devices on linux and the [Wi-Fi Link Controller Linux Documentation](https://www.microchip.com/en-us/product/ATWILC1000#document-table) for the latest release notes and revision history.

The firmware files should be placed on the target's filesystem under /lib/firmware/mchp, or built as part of the linux kernel by placing it under kernel_src/firmware/mchp

For more information on Microchip Embedded Wi-Fi®, visit [Microchip Embedded Wi-Fi®](http://www.microchip.com/design-centers/wireless-connectivity/embedded-wi-fi).
