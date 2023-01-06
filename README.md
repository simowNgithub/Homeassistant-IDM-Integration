# Homeassistant-IDM-Integration
I did a complete integration by modbus. I transfer the photovoltaik data from my SMA Tripower (photovoltaik) and Shelly 3EM (house consumption electricity) to the IDM Terra SW8 Complete HGL Sole-Wärmepumpe with Navigator 2.0.

<a href="https://www.buymeacoffee.com/cryr6xw8kjU" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 60px !important;width: 217px !important;" ></a>

# Steps for implementation
1. Add SMA Tripower (inverter / Wechselrichter) with modbus for calculate the PV values
2. Add Shelly 3EM (house consumption electricity / Strommessgerät) with the Shelly Integration for calculate the overload of PV values
3. Add IDM Heatpump (heatpump / Wärmepumpe) with modbus
4. Use my script for getting the available power for the heatpump and sync the values to the heatpump

![424dd4adbc97b4dd986d3d1154b85286f51745b5](https://user-images.githubusercontent.com/117570480/200165911-544808cb-e029-49ff-b217-e350f3b16f56.jpeg)
