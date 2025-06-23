# About

You need to make some choices before programming the ESPHome Indoor Multi-Sensor. First is the Sensor package. You can either choose Package A, the Sensirion SEN6X sensor package which is an all-in-one sensor package. Or you can choose Package B which is a lower cost discrete sensor set that is missing particulate matter sensors. Next up is what type of radar sensor you plan on including. There are 4 choices here. Each of these these builds include all supported sensors: pressure, light, sound level, power/energy monitor and speaker. If there are sensors you wish to not include, take control of the sensor in and use the non-factory config yaml as a starting point.

# Installation

You can use the buttons below to install the pre-built firmware directly to your device via USB from the browser.

| Sensor Pkg | Radar LD2410 | Radar C4001 | Radar LD2450-MTMZ | Radar LD2450-STSZ |
|---|---|---|---|---|
| Pkg A | <esp-web-install-button manifest="firmware/sensor-pkg-a-ld2410.manifest.json"></esp-web-install-button> | <esp-web-install-button manifest="firmware/sensor-pkg-a-c4001.manifest.json"></esp-web-install-button> | <esp-web-install-button manifest="firmware/sensor-pkg-a-ld2450-mtmz.manifest.json"></esp-web-install-button> | <esp-web-install-button manifest="firmware/sensor-pkg-a-ld2450-stsz.manifest.json"></esp-web-install-button> |
| Pkg B | <esp-web-install-button manifest="firmware/sensor-pkg-b-ld2410.manifest.json"></esp-web-install-button> | <esp-web-install-button manifest="firmware/sensor-pkg-b-c4001.manifest.json"></esp-web-install-button> | <esp-web-install-button manifest="firmware/sensor-pkg-b-ld2450-mtmz.manifest.json"></esp-web-install-button> | <esp-web-install-button manifest="firmware/sensor-pkg-b-ld2450-stsz.manifest.json"></esp-web-install-button> |

<script type="module" src="https://unpkg.com/esp-web-tools@10/dist/web/install-button.js?module"></script> 
