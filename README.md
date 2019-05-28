# Pentair Pool Controller

For last couple of years, I have been looking for good automation system that I can use to automate my backyard pool and spa. All current systems available are outdated and overpriced. It is mind blowing to see how much Pentair, Zodiak or Hayward are charging for their systems. So, I decided to build my own.

It is powered by RaspberyPi running NodeJS, Node-Red, Node Red Dashboard coupled with 16 relays module and IntelliComm® II Interface Adapter. I really could have implemented software solution instead of overpriced adapter but I decided to focus on building hardware first. 

Here is the view of AQUALINK® POWER CENTERS and Pool Controller Altelix enclosure:


### Here is the list of the components I used:

1. [Raspberry Pi 3 Model B Board](https://www.amazon.com/Raspberry-Pi-MS-004-00000024-Model-Board/dp/B01LPLPBS8)
1. [SainSmart 16-Channel Relay Module](https://www.amazon.com/gp/product/B0057OC66U)
1. [IntelliComm® II Interface Adapter](https://www.pentair.com/en/products/pool-spa-equipment/pool-automation/intellicomm_ii_interfaceadapter.html)
1. [Altelix NEMA Enclosure 17x14x6](https://www.amazon.com/Raspberry-Pi-MS-004-00000024-Model-Board/dp/B01LPLPBS8)
1. [Omron G7L-2A-BUBJ-CB DC24 Relays](https://www.amazon.com/gp/product/B0057OC66U)
1. [8 Positions Dual Row 600V 25A Screw Terminals](https://www.amazon.com/gp/product/B0057OC66U)
1. [DS18b20 Waterproof Temperature Sensors](https://www.amazon.com/gp/product/B0057OC66U)
1. [Intermatic PE24VA Valve Actuators](https://www.amazon.com/Intermatic-PE24VA-Valve-Actuator-Black/dp/B002ZPJVV2)
1. [AQUALINK® POWER CENTERS Model 6614-LD](https://www.jandy.com/en/products/controls/system-components/power-centers/aqualink-power-center)
1. [IntelliFlo® VSF Variable Speed Pump](https://www.pentair.com/en/products/pool-spa-equipment/pool-pumps/intelliflo_vsf.html)
1. [MASTERTEMP HEATER](https://www.pentair.com/en/products/pool-spa-equipment/pool-heaters/mastertemp_heater/sku/460737.html)

### In future I am planning

1. Integrate my system with analog sensors like flow, pressure, pH, and current sensors.
1. Build wall unit controller using some old android tablet.
1. Integrate with Google Assistance and Alexa.
1. Install Time Series database with Graphana so I can start collecting and visualizing historical sensor data


### Useful References
1. [RS485 Adapter Software Implementation](https://github.com/tagyoureit/nodejs-poolController#rs485-adapter)
1. [SunTouch / QuickTouch RS-485 Protocol](https://docs.google.com/document/d/1M0KMfXfvbszKeqzu6MUF_7yM6KDHk8cZ5nrH1_OUcAc/edit?usp=drivesdk)
