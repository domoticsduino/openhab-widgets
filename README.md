# OPENHAB WIDGETS
Collections of my personal widgets for OpenHAB

See my youtube channel for additional info and showcase: [DomoticsDuino - SMART HOME con OPENHAB](https://www.youtube.com/@DomoticsDuino?sub_confirmation=true)

## Energy Widget
Widget for energy monitoring, both consumption and production

Filename: dd-energy.yml

Params:
 - Title: string
 - Grid Consumption: item
 - MAX Grid Consumption (W): number
 - Grid Surplus: item
 - PV Production: item
 - MAX PV Production (W): number
 - PV Own Consumption: item
 - Home Consumption: item
 - Home FF Consumption: item
 - Limit FF Consumption: number
 - Home GF Consumption: item
 - Limit GF Consumption: number
 - Home BA Consumption: item
 - Limit BA Consumption: number
 - Real Time Consumption: item
 - Limit Real Time Consumption: number
 - Value Font Size: string
 - Subvalue Font Size: string
 - Value Border Radius: string
 - Grid Color: string
 - Grid Surplus Color: string
 - Solar Color: string
 - Home Color: string
 - Min opacity: number

### *version 0.2*
 - Added opacity support
 - Added warning
 - Added dynamic icons

### *version 0.1*
 - initial version
 
Credits to: https://community.openhab.org/t/energy-widget-like-in-home-assistant-demo/131189
