---
title: "Domotizzazione"
linkTitle: "domotizzazione"
weight: 3
description: >
  Domotittazione del ciclorifugio.
---

## Dispositivi IoT per domotizzazione
Allo scopo di miglioare l'esperienza dell'utente il gruppo ha selezionato una lista di interazioni ed automatismi da implementare attraverso dispositivi IoT.

### Potenziali prodotti per la domotizzazione del ciclorifugio

* [Home assistant](https://www.home-assistant.io/) 
* [Savant](https://www.savant.com/)
* [Control4](http://www.control4.it/wordpress/)
* [openHAB](https://www.openhab.org/)  

[Spegazione del funzionamento del software Home Automation](https://24-7-home-security.com/open-source-home-automation-software/)

<em>E' stato selezionato Home assistant</em>

### Dispositivi IoT necessari nel ciclorifugio (MQTT)

| Dispositivo | prodotto (link) | home assistant/tasmota link | protocollo di comunicazione | prezzo |
|---|---|---|---|---|
| sensori di contatto alla finestre | [Mini Door/Window Sensor](https://goabode.com/security-devices/door-alarms/mini-door-window-sensor) | [home assistant](https://www.home-assistant.io/integrations/abode/) | abodeRF/433Mhz | $27.99 |
| // | [Door and Window Sensor](https://www.banggood.com/D06-Tuya-Smart-Life-WiFi-Wireless-Remote-Door-and-Window-Sensor-Alarm-Molile-Phone-Control-Sensor-Alarm-Detector-p-1843620.html?p=CM27171011078201412U&cur_warehouse=CN&ID=6287845) | [tasmota](https://templates.blakadder.com/D06.html) | wifi | $18.69 | 
| rgb led | [LIFX Nightvision BR30 ](https://www.lifx.com/collections/lamps-and-pendants/products/lifx-nightvision-br30) | [home assistant](https://www.home-assistant.io/integrations/lifx/) | wifi | $59.99 |
| led | [LIFX White to Warm ](https://www.lifx.com/collections/lamps-and-pendants/products/lifx-white-to-warm) | [home assistant](https://www.home-assistant.io/integrations/lifx/) | wifi | $29.99 |
| switch | [WiFi Smart Light Switch Glass Panel Touch](https://www.aliexpress.com/item/4000160375733.html?aff_fcid=571592c74ed5431f9efc793fb4f3310b-1625557233428-01761-5SqueSek&aff_fsk=5SqueSek&aff_platform=link-c-tool&sk=5SqueSek&aff_trace_key=571592c74ed5431f9efc793fb4f3310b-1625557233428-01761-5SqueSek&terminal_id=5c124ed8f7df482e98799c38ab2c8150&tmLog=new_Detail) | [tasmota](https://templates.blakadder.com/wifi_smart_switch_3gang.html) | wifi | $11.29 - 15.99 |
| smart lock | [August Wi-Fi Smart Lock](https://august.com/products/august-wifi-smart-lock) | [home assistant](https://www.home-assistant.io/integrations/august/) | wifi | $229.99 |
| sensori di fumo | [Tuya WiFi Smoke Alarm](https://www.aliexpress.com/item/4000818367545.html?aff_platform=portals-tool&sk=_dYc72Dj&aff_trace_key=ad46a8783ef8414cb3077511738cc481-1595436156311-00915-_dYc72Dj&terminal_id=3ac645b4aa5741e4bebe6d5c100f96fc&tmLog=new_Detail&aff_request_id=ad46a8783ef8414cb3077511738cc481-1595436156311-00915-_dYc72Dj) | [tasmota](https://templates.blakadder.com/YG400A.html) | wifi | $13.70 |
| termostato | [AVATTO Tuya WiFi Smart Thermostat](https://www.aliexpress.com/item/4000398480147.html?aff_platform=portals-tool&sk=_dYc72Dj&aff_trace_key=ad46a8783ef8414cb3077511738cc481-1595436156311-00915-_dYc72Dj&terminal_id=3ac645b4aa5741e4bebe6d5c100f96fc&tmLog=new_Detail&aff_request_id=ad46a8783ef8414cb3077511738cc481-1595436156311-00915-_dYc72Dj) | [tasmota](https://templates.blakadder.com/ME81H.html) | wifi | $17.47 - 24.22 |
| smart plug | [BSEED Europe Standard Tuya Smart Wifi Socket](https://www.amazon.de/dp/B07S643X2J?tag=tasmotatempla-21) | [tasmota](https://templates.blakadder.com/bseed_smart_socket.html) | wifi | 18,59€ |
| // | [DeLock 11826 WiFi Steckdose](https://www.amazon.de/dp/B07SNGJ8GD?tag=tasmotatempla-21) | -- | mqtt | 17,48 € |
| text | [text](link.com) | [text](link.com) | text | text |