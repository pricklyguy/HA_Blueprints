# Home Assistant Blueprints

Collection of Home Assistant blueprints for automation and control.

## Zigbee2MQTT - 4 Button Remote for Ceiling Fan + Light

Control a fan and light using a 4-button Zigbee remote via Zigbee2MQTT.

[![Import Blueprint](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https://raw.githubusercontent.com/pricklyguy/HA_Blueprints/refs/heads/main/blueprints/automation/zigbee_four_button_remote)

### Features
- Button 1: Single press toggles light, double press cycles brightness (25/50/75/100%)
- Buttons 2/3/4: Single press sets fan low/med/high, double press turns fan off
- Customizable fan speed percentages
- Designed for Tuya  or similar 4-button remotes via Zigbee2MQTT

## Zigbee2MQTT - H2 Quad Rocker Scene Controller

Multi-functional control for the H2 Quad Rocker including light toggling, fan speed cycling, and blind control with start/stop logic.

[![Import Blueprint](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https://raw.githubusercontent.com/pricklyguy/HA_Blueprints/refs/heads/main/blueprints/automation/h2_quad_rocker_scene_control.yaml)

### Features
- **Button 1(Top Rocker):** Single press toggles light.
- **Button 2(Middle Rocker):** Cycles fan speeds (Off -> 33% -> 66% -> 100%).
- **Button 3(Bottom Rocker):** Single press opens blinds; second press while moving stops them.
- **Button 4(Wireless Rocker):** Single press closes blinds; second press while moving stops them.

