# ruuvi_hass
RuuviTag sensor for hass.io

Copy ruuvi-hass.py, manifest.json and ____init.py_____ to <config folder>/custom_components/ruuvi-hass/ (e.g. /home/homeassistant/.homeassistant/custom_components/ruuvi-hass.py)


The configuration.yaml has to be edited like this
```
sensor:
  - platform: ruuvi-hass
    mac: 'MA:CA:DD:RE:SS:00'
    name: 'livingroom'
    
  - platform: ruuvi-hass
    mac: 'MA:CA:DD:RE:SS:01'
    name: 'bathroom'
```
Todo:
- Add more sensors (acceleration)
