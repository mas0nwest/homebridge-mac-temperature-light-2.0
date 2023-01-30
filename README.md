# `CURRENTLY NOT WORKING!`

## Tested Devices
- Mac Mini 2012 - Catalina
- MacBook Pro 2017 - Monterey
- MacBook Pro M1 - Ventura - *not supported*

## Installation

1. Install Homebridge using `npm install -g homebridge`
2. Install this plugin using `npm install -g homebridge-mac-temperature-light` or via the Homebridge Ui
3. Update your configuration file. See **Configuration & Usage** below.

## Configuration & Usage
Your Homebridge config file (`~/.homebridge/config.json`) should include `MacTemperature` accessories, with names of your choosing, dpeending on what functions from this plugin you wish to enable.

Example:
```
"accessories": [
    {
        "accessory": "MacTemperature",
        "name": "Temperature"
    }
]
```
