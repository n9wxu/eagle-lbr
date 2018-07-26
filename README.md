# eagle-lbr
A collection of myself created eagle libraries.

:warning: **Use at your own risk, always check your layout before manufacturing!**

## Changes

- 20180726:
  - added Heltec Wifi LoRa 32 module<br>
    [https://github.com/Heltec-Aaron-Lee/WiFi\_Kit\_series](https://github.com/Heltec-Aaron-Lee/WiFi_Kit_series)

- 20180724:
  - fixed SK6812 SMD3535 footprint<br>
    [https://github.com/1randy/eagle-lbr/issues/1](https://github.com/1randy/eagle-lbr/issues/1)

  - added SMD5050_W(ide) footprint, longer pads for easier soldering

  - renamed package "SK6812-NARROW" to "LED5050_N"


## Libraries

* SK6812.lbr:
  LED with smart control circuit
  - SK6812 SMD3535: 3.5mm x 3.5mm
  - SK6812 SMD5050: 5.0mm x 5.0 mm
  - SK6812 SMD5050_N: 5.0mm x 5.0mm with shorter/narrower pads
  - SK6812 SMD5050_W: 5.0mm x 5.0mm with longer/wider pads

* TAS6424.lbr:
  - TAS6424-Q1: 2.1-MHz Digital Input 4-Channel Automotive Class-D Audio Amplifier

* LoRa_modules.lbr:
  - AI-Thinker_RA-01: 433MHz LoRa Module
  - RFM95: 866MHz LoRa Module
  - LORA\_SILK\_M, LORA\_SILK\_S: LoRA Logo for silkscreen (medium & small size)
  
* ESP32.lbr
  - Heltec WIFI LoRa 32<br>
    ESP32 Module with LoRa, 2.54mm DIP

## Misc

* Datasheets for the components in the directory [datasheets/]()



