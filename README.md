# EcoFlow BLE Integration for Home Assistant
<a href="https://www.buymeacoffee.com/npike" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" alt="Buy Me A Coffee" height="41" width="174"></a>


Inspired by [hassio-ecoflow](https://github.com/vwt12eh8/hassio-ecoflow), [hassio-ecoflow-cloud](https://github.com/tolwi/hassio-ecoflow-cloud) and [ecoflow-bt-reverse-engineering](https://github.com/nielsole/ecoflow-bt-reverse-engineering) this integration uses BLE to get battery percentage from devices..

## Installation

- Install as a custom repository via HACS
- Manually download and extract to the custom_components directory

Once installed, use Add Integration -> Ecoflow BLE.

## Disclaimers

⚠️ Originally developed for personal use without a goal to cover all available device attributes and ecoflow devices.

## Current state

While I suspect this will work with other Ecoflow devices that broadcast over Bluetooth Low Energy, I have only tested with a River 2.

<details><summary> RIVER_2 <i>(sensors: 1)</i> </summary>
<p>

*Sensors*
- Battery Level

</p></details>

<details><summary> RIVER_3 <i>(sensors: 1)</i> </summary>
<p>

*Sensors*
- Battery Level

</p></details>

<details><summary> DELTA_2 <i>(sensors: 1)</i> </summary>
<p>

*Sensors*
- Battery Level

</p></details>

<details><summary> STREAM AC PRO <i>(sensors: 1)</i> </summary>
<p>

*Sensors*
- Battery Level

</p></details>
