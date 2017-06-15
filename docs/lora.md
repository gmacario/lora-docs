# LoRa - Architecture, Specification and Modules

## LoRa Alliance - General Information

* [LoRa(R) Alliance](https://www.lora-alliance.org/)

* [LoRa Alliance Board Officers](https://www.lora-alliance.org/Join/Become-a-Member)
  - Geoff Mulligan - President - Proto6 Consulting
  - Stan Moyer - Vice President - Inventures (same as Steve Crumb from GENIVI)
  - ...
 
* How to [Become a Member of the LoRa Alliance](https://www.lora-alliance.org/Join/Become-a-Member)
  - Public member (free) have access to Released Deliverables
  - Adopter ($3k): in addition, can access Final Deliverables + much more
  - Institutions (Free, subject to BoD approval): in addition, can ...
  - Contributor ($20k): in addition, have the right to initiate, participate in, vote and chair Work Groups
  - Sponsor ($50k): in addition, can request a BoD seat + ...

## LoRa Specification

This document describes the LoRaWAN™ network protocol. Send [an email to request LoRaWAN 1.0 Specification](https://www.lora-alliance.org/Contact/RequestSpecificationForm.aspx).

file: `LoRaWAN Specification 1R0.pdf` (PDF, 82 pages)

The Specification is Copyright (C) 2015, LoRA Alliance, Inc..

## LoRa Case Studies

* [TheThingsNetwork](https://thethingsnetwork.org/)

## Resources

* [LoRaWAN: What is it?](https://t.co/OUUBEpV6Ta) - LoRa Alliance, 2015 (PDF, 20 pages)

* Architecture: See [lora-architecture.md](lora-architecture.md)

* Devices
	- [LoRa MAC library in C](http://www.research.ibm.com/labs/zurich/ics/lrsc/lmic.html)
	- [Semtech's endpoint](https://github.com/Lora-net/LoRaMac-node)

* Gateways
	- [A DIY low-cost LoRa gateway](http://cpham.perso.univ-pau.fr/LORA/RPIgateway.html)
	- [Semtech's gateway](https://github.com/Lora-net/lora_gateway)

* Network servers
	- Open source LoRaWAN servers are a bit scarce.

## LoRa Certified Products

* [LoRa Certified Products](https://www.lora-alliance.org/Products/Certified-Products)

### Adeunis RF

* [LoRaWAN Demonstrator by Adeunis RF](http://www.adeunis-rf.com/en/products/lorawan-products/lorawan-demonstrator-by-adeunis-rf)
  - [Datasheet](http://www.adeunis-rf.com/media/downloads/172/trad_file/eng/arf_lorawan_demonstrator_868_data_sheet_v1-2_gb.pdf) (PDF, 1 page)
  - [User guide](http://www.adeunis-rf.com/media/downloads/185/trad_file/eng/ug_lorawan_demonstrator_user_v1.1.pdf) (PDF, 16 pages)
  - List Price: 178,80 EUR ([ThingPark Store, 2016-05-04](http://actility.thingpark.com/thingpark-store/development-kit/171-lorawan-demonstrator.html))

* [LoRaWAN transmitter with ANA/DIG Sensor interfaces](http://www.adeunis-rf.com/en/products/lorawan-products/lorawan-sensors)
  - [Datasheet](http://www.adeunis-rf.com/media/downloads/173/trad_file/eng/arf_lorawan_sensors_data_sheet_v1-3-gb.pdf)
  - [User guide](http://www.adeunis-rf.com/media/downloads/184/trad_file/eng/arf8045_adeunis_lorawan_sensors_user_guide_v1.3_fr_gb.pdf)

* [LoRaWAN transmitter with pulse interfaces](http://www.adeunis-rf.com/en/products/lorawan-products/lorawan-pulse)  
  - [Datasheet](http://www.adeunis-rf.com/media/downloads/176/trad_file/eng/arf_lorawan_pulse_data_sheet_v1-3-gb.pdf)
  - [User guide](http://www.adeunis-rf.com/media/downloads/183/trad_file/eng/arf8046xx_adeunis_lorawan_pulse_user_guide_v1.4_fr_gb.pdf)

* [Adeunis RF distributors in Italy](http://www.adeunis-rf.com/fr/points-de-vente)
  - [Advantec SRL](http://www.advantec.it/radiomodem-adeunis/)
  - [Farnell italy](http://it.farnell.com/adeunis)
  - [Distrelec Italy](http://www.distrelec.it/manufacturer/adeunis/man_adeunis)

### IMST - iM880B-L

The first LoRa Alliance certified radio module with a maximum output power of 19 dBm is the iM880B-L by IMST GmbH (source: [Wikipedia](https://en.wikipedia.org/wiki/LPWAN)).

* http://www.wireless-solutions.de/products/radiomodules/im880b-l

The chip may be evaluated with the [SK-iM880B - Long Range Radio Starter Kit](http://www.wireless-solutions.de/products/starterkits/sk-im880b.html)
* [SK-iM880B Price: 249.00 EUR](http://webshop.imst.de/sk-im880b-starter-kit-for-im880b-l.html) excl 19% Tax

Other interesting products:

* [iU880A - Long Range USB Adapter](http://webshop.imst.de/iu880a-long-range-usb-adapter.html)

### Libelium - Waspmote + LoRaWAN modules

* [Waspmote - Open Source Sensor Node for the Internet of Things](http://www.libelium.com/products/waspmote/)
  - [Waspmode Datasheet](http://www.libelium.com/downloads/documentation/waspmote_datasheet.pdf) (PDF, 29 pages)
  - [Waspmote Quick Start Guide](http://www.libelium.com/downloads/documentation/quickstart_guide.pdf) (PDF, 19 pages pages)
  - [Waspmote Technical Guide](http://www.libelium.com/downloads/documentation/waspmote_technical_guide.pdf) (PDF, 173 pages)
  - [Wireless Sensor Networks with Waspmote and Meshlium](http://www.libelium.com/downloads/documentation/wsn-waspmote_and_meshlium_eng.pdf) (PDF, 22 pages)
* [Libelium Adds LoRaWAN for Full Compatibility with Smart Cities Networks](http://www.libelium.com/lorawan-waspmote-868-europe-900-915-us-433-mhz-asia-lora) - Libelium PR, 2015-11-24
* [Libelium - Industrial control applications](https://www.libelium.com/top_50_iot_sensor_applications_ranking/#industrial_control)
* [Libelium - Online order form](https://www.libelium.com/orderform/)

### Marvin

* [Marvin](http://www.rdmmakerspace.nl/Marvin/) is a development board based on the Arduino Leonardo and is grove sensor compatible.
* [Marvin workshop material](https://drive.google.com/drive/folders/0B3qKsQNZF5ygbldQMzRFTnA5RzA)
* [Order Marvin LoRa Development Board](https://www.conrad.nl/nl/marvin-lora-development-board-for-iot-prototypingboard-48158.html) (84.70 EUR from Conrad NL)
* [Marvin Kickstarter project](https://www.kickstarter.com/projects/688158475/marvin-the-lora-development-board/) was funded in December 2016

### Pycom: LoPy - the LoRa, WiFi and Bluetooth IoT development platform

* Company based in Amsterdam, Netherlands
* Pycom webshop: <https://www.pycom.io/>
* [LoPy](https://www.pycom.io/wp-content/uploads/2017/01/lopySpecsheetGraffiti2017newR.pdf) is a MicroPython triple-network dev platform which doubles up as a **LoRa Nano gateway**. Arduino IDE compatible
  - LoPy images and pinouts: <https://github.com/pycom/LoPy>
  - LoPy Quickstart guide: <https://docs.pycom.io/pycom_esp32/pycom_esp32/getstarted.html>
  - [LoPy Kickstarter project](https://www.kickstarter.com/projects/1795343078/lopy-the-lora-wifi-and-bluetooth-iot-development-p) was funded in March 2016
* The [L01 OEM](https://www.pycom.io/product/l01-oem-module/) module is priced @14.95 EUR for 100 units


## LoRa RF Transceivers

### Microchip - RN2483

NOTE: LoRaWAN device!

* http://www.microchip.com/wwwproducts/en/RN2483
* [RN2483 Data Sheet](http://ww1.microchip.com/downloads/en/DeviceDoc/50002346B.pdf) (PDF, 20 pages)
* [Buy on-line: RN2483-I/RM101](http://www.microchipdirect.com/ProductDetails.aspx?Category=RN2483) (est. 9.61 EUR/ea per 1000+ pcs)

### Semtech - SX127x

* http://www.semtech.com/wireless-rf/rf-transceivers/

* [Wireless RF Solutions Guide](http://www.semtech.com/images/mediacenter/collateral/ism_sg.pdf) (PDF, 8 pages)

* RF Transceiver Related Articles
  - [Making the Right Trade-offs for Sensor Networks](http://www.semtech.com/rf-transceivers/right-tradeoffs-sensor-networks.pdf) - Hardy Schmidbauer, Semtech Corporation (PDF, 7 pages)
  - [A Practical Implementation of 6LoWPAN for Metropolitan Sized Networks](http://www.semtech.com/rf-transceivers/Practical_MAN-Semtech.pdf) - Joseph A. Knapp and Nicolas Sornin, Semtech Corporation (PDF, 9 pages)
  - [Semtech's Low-Cost, High-Range RF Transceivers](http://issuu.com/alexeeweb/docs/volume_84_-_simon_blyth)

* More RF Transceiver Information
  - [ISM Selector Guide](http://www.semtech.com/images/mediacenter/collateral/ism_sg.pdf)
  - [ISM Band RF Transceiver Application Notes](http://www.semtech.com/wireless-rf/ISM-Application-Notes/)
  - [RF Design Partners](http://www.semtech.com/wireless-rf/wireless-solutions/)
  - [LoRa™ RF Product Family](http://www.semtech.com/wireless-rf/lora.html)

* http://www.semtech.com/wireless-rf/rf-transceivers/sx1276/

* Application Notes
  - [SX127x Reference Design Overview](http://www.semtech.com/apps/filedown/down.php?file=AN1200.19_SX127x_RefDesign_STD.pdf)
  - [AN1200.28 - LoRaWAN MCU Specification and Requirements](http://www.semtech.com/apps/filedown/down.php?file=an1200_28_lorawan_mcu_specification_v2.pdf) (PDF, 3 pages)

### Semtech - SX1301

The SX1301 digital baseband chip is a massive digital signal processing engine specifically designed to offer breakthrough gateway
capabilities in the ISM bands worldwide. It integrates the **LoRa concentrator IP**.

The LoRa concentrator is a multi-channel high performance transmitter/receiver designed to simultaneously receive several LoRa packets
using random spreading factors on random channels. Its goal is to enable robust connection between a central wireless data
concentrator and a massive amount of wireless end-points spread over a very wide range of distances.

* SX1301 Datasheet: <http://www.semtech.com/images/datasheet/sx1301.pdf> (PDF, 40 pages)

## Distributors of LoRa modules and chips

### AliExpress

* **[2pcs/lot LoRa1278 - 4Km 100mW 433MHz High sensitivity sx1278 chip Lora module ultra long range RF Wireless Transceiver Module](http://www.aliexpress.com/item/Upgrade-version-LoRa1278-4Km-100mW-High-sensitivity-sx1276-chip-FSK-Lora-long-range-RF-Wireless-Transceiver/32276300110.html)** (Used by @muwattali for lora-shield prototypes)
* [2pcs/lot 868MHz | 915MHz 100mW sx1276 chip long range 4Km RF Wireless LoRa Module LoRa1276](http://www.aliexpress.com/store/product/New-2pcs-868MHz-4Km-100mW-sx1276-chip-Lora-long-range-RF-Wireless-transmitter-receiver-Module-LoRa1276/1087605_32338274153.html)
* [Long distance LoRa SX1276 SX1278 RF wireless module DRF1278F](http://www.aliexpress.com/store/product/Long-distance-LoRa-SX1276-SX1278-RF-wireless-module-DRF1278F/1396782_2021201457.html)

### Cooking Hacks

https://www.cooking-hacks.com/

* [SX1272 LoRa module for Arduino, Raspberry Pi and Intel Galileo - 900 / 915 MHz [XBee Socket]](https://www.cooking-hacks.com/sx1272-lora-module-for-arduino-raspberry-pi-intel-galileo-900-mhz) - Price: 45.00 EUR
* [LoRaWAN module for Arduino, Waspmote and Raspberry Pi - 868 MHz [XBee Socket]](https://www.cooking-hacks.com/lorawan-module-for-arduino-raspberry-pi-868-mhz-xbee-socket) - Price: 58.00 EUR
* [LoRaWAN Radio Shield for Arduino - 433 MHz](https://www.cooking-hacks.com/lorawan-radio-shield-for-arduino-433-mhz) - Price: 90.00 EUR
* [LoRaWAN Radio Shield for Arduino - 868 MHz](https://www.cooking-hacks.com/lorawan-radio-shield-for-arduino-868-mhz) - Price: 90.00 EUR
* [LoRaWAN Radio Shield for Arduino - 900/915 MHz](https://www.cooking-hacks.com/lorawan-radio-shield-for-arduino-900-915-mhz) - Price: 90.00 EUR

Tutorials:

* [Extreme Range Links: LoRa 868 / 900MHz SX1272 LoRa module for Arduino Waspmote and Raspberry Pi](https://www.cooking-hacks.com/documentation/tutorials/extreme-range-lora-sx1272-module-shield-arduino-raspberry-pi-intel-galileo/)
* [LoRaWAN Technology for Arduino, Waspmote and Raspberry Pi](https://www.cooking-hacks.com/documentation/tutorials/lorawan-for-arduino-raspberry-pi-waspmote-868-900-915-433-mhz/) - incl. links to libraries and examples for Arduino, Waspmote and Raspberry Pi

### Taobao.com

* [SX1301IMLTRC screen SX1301 package QFN64 brand good quality stock SEMTECH](https://world.taobao.com/item/524964459840.htm)

### Techship

* <https://techship.com/products/category/kits-and-solutions/>
<!-- EOF -->
