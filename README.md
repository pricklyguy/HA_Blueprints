# Home Assistant Blueprints
Collection of Home Assistant blueprints for automation and control.

---

## Zigbee2MQTT - 4 Button Remote for Ceiling Fan + Light
Control a fan and light using a 4-button Zigbee remote via Zigbee2MQTT.

[![Import Blueprint](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https://raw.githubusercontent.com/pricklyguy/HA_Blueprints/refs/heads/main/blueprints/automation/zigbee_four_button_remote.yaml)

### Features
- **Button 1:** Single press toggles light, double press cycles brightness (25/50/75/100%)
- **Buttons 2/3/4:** Single press sets fan low/med/high, double press turns fan off
- Customizable fan speed percentages
- Designed for Tuya or similar 4-button remotes via Zigbee2MQTT

---

## Zigbee2MQTT - 4 Button Remote for Light, Fan, and Blinds
Full-featured 4-button remote controlling a light, fan, and a single blind/cover via Zigbee2MQTT.

[![Import Blueprint](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https://raw.githubusercontent.com/pricklyguy/HA_Blueprints/refs/heads/main/blueprints/automation/Zigbee_4button_fan_blinds.yaml)

### Features
- **Button 1:** Single press toggles light, double press cycles three configurable brightness presets
- **Button 2:** Single press toggles fan on/off, double press cycles three configurable speed presets (low/med/high)
- **Button 3:** Single press opens blind; second press within a configurable stop window sends STOP while mid-travel
- **Button 4:** Single press closes blind; second press within a configurable stop window sends STOP while mid-travel
- Blind entity is optional — leave blank if not controlling a cover
- All speed and brightness presets are configurable via sliders

---

## Zigbee2MQTT - H2 Quad Rocker Scene Controller (Fan Cycle)
Control for the Aqara H2 Quad Rocker with light toggling, fan speed cycling through all speeds including off, and blind start/stop logic.

[![Import Blueprint](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https://raw.githubusercontent.com/pricklyguy/HA_Blueprints/refs/heads/main/blueprints/automation/aqara_quad_rocker_scene_control.yaml)

### Features
- **Button 1 (Top Rocker):** Single press toggles light
- **Button 2 (Middle Rocker):** Cycles fan speeds (Off → Low → Med → High → Off)
- **Button 3 (Bottom Rocker):** Single press opens blinds; second press while moving stops them
- **Button 4 (Wireless Rocker):** Single press closes blinds; second press while moving stops them

---

## Zigbee2MQTT - H2 Quad Rocker Scene Controller (Fan Toggle)
Same device as above but with simple fan on/off toggle instead of speed cycling — ideal since the H2 only supports single press actions, making cycling impractical.

[![Import Blueprint](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https://raw.githubusercontent.com/pricklyguy/HA_Blueprints/refs/heads/main/blueprints/automation/aqara_quad_rocker_scene_fan_toggle.yaml)

### Features
- **Button 1 (Top Rocker):** Single press toggles light
- **Button 2 (Middle Rocker):** Single press toggles fan on/off
- **Button 3 (Bottom Rocker):** Single press opens blinds; second press while moving stops them
- **Button 4 (Wireless Rocker):** Single press closes blinds; second press while moving stops them

---

## Zigbee2MQTT - 3 Button Dual Blind Controller
Control two independent blinds and both as a group using a 3-button Tuya Zigbee remote via Zigbee2MQTT.

[![Import Blueprint](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https://raw.githubusercontent.com/pricklyguy/HA_Blueprints/refs/heads/main/blueprints/automation/3button_blind_controll.yaml)

### Features
- **Button 1 (Left):** Controls left blind — single press opens or closes based on current position; press again while moving to stop
- **Button 2 (Center):** Controls both blinds together — open/close based on average position; press again while either is moving to stop both
- **Button 3 (Right):** Controls right blind — single press opens or closes based on current position; press again while moving to stop
- Configurable stop window (seconds) to tune how quickly a second press triggers STOP vs. a new open/close command
- Double press supported by the device and available for future use
