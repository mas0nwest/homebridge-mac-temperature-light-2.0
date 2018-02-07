# homebridge-mac-temperature-light

[Homebridge](https://github.com/nfarina/homebridge) accessories to estimate room temperature, and room ambient light from your Mac's sensors.

## Installation

1. Install Homebridge using `npm install -g homebridge`
2. Install this plugin using `npm install -g homebridge-mac-temperature-light`
3. Update your configuration file. See **Configuration** below.

## Configuration & Usage
Your Homebridge config file (`~/.homebridge/config.json`) should include `MacTemperature` or `MacAmbientLight` accessories, with names of your choosing, dpeending on what functions from this plugin you wish to enable.

Example:
```
"accessories": [
    {
        "accessory": "MacTemperature",
        "name": "Temperature"
    },
    {
        "accessory": "MacAmbientLight",
        "name": "Ambient Light"
    }
]
```
