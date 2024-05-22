[![Build Status](https://travis-ci.org/Scott8586/home-assistant-horizonview.svg?branch=master)](https://travis-ci.org/Scott8586/home-assistant-horizonview)

## Home Assistant configuration for Horizon View

Integrations in Use:

1. Enphase Envoy - for solar panels and Electrical Power
2. IQVIA - for allergen forcast
3. Lutron Caseta, used for RA2 Select Relay
4. NUT - connects to two UPS services.
5. Pentair ScreenLogic - servicing pool pumps etc.
6. Pi-hole
7. Synology DSM - tracking critical Synology information
8. Tasmota - remote switch control
9. Unifi Network - tracking presense (via UCKG2+)
10. Unifi Protect - security cameras (via UCKG2+)
11. Venstar - thermostats
12. Vera - old home automation z-wave box

Custom Components in Use:

1. healthchecks.io
2. HACS
3. bobcatminer (not used at the moment)
4. ge_home - connect to oven
5. smartthinq_sensor - connect to washer and dryer
6. pirateweather - local weather
7. bermuda - use the BTLE Proxy's to locate BT device
8. schluter - a better version of the Schluter integration, providing energy, and not timing out.

Off host services:

1. juiceboxproxy - provide charging information from JuiceBox over MQTT (also requires router redirection)
2. ecowitt2mqtt - redirect ecowitt weatherstation information over MQTT
3. GPSD - connected to gpsd on separate server.

