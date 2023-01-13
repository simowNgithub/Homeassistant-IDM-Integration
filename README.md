# Homeassistant-IDM-Integration
I did a complete integration by modbus. I transfer the photovoltaik data from my SMA Tripower (photovoltaik) and Shelly 3EM (house consumption electricity) to the IDM Terra SW8 Complete HGL Sole-Wärmepumpe with Navigator 2.0.

<a href="https://www.buymeacoffee.com/cryr6xw8kjU" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 60px !important;width: 217px !important;" ></a>

# Steps for implementation
1. Add SMA Tripower (inverter / Wechselrichter) with modbus for calculate the PV values
2. Add Shelly 3EM (house consumption electricity / Strommessgerät) with the Shelly Integration for calculate the overload of PV values
3. Add IDM Heatpump (heatpump / Wärmepumpe) with modbus
- Type in the „Fachmann Codeeingabe“…
![IMG_1219](https://user-images.githubusercontent.com/117570480/212335397-6b3aa0aa-8777-4897-943c-a8e99750dd9d.png)
![IMG_1220](https://user-images.githubusercontent.com/117570480/212335481-19ce904a-47ab-4e27-b866-40d7d54cca7b.png)
- Go to „Einstellungen“ > „Photovoltaik“
![IMG_1221](https://user-images.githubusercontent.com/117570480/212335505-d53f13bb-c18c-4c88-a403-d5287448a042.png)
- Set the „PV Signal“ to „Gäubedeleittechnik / Smartfox“
![IMG_1222](https://user-images.githubusercontent.com/117570480/212335532-46e8bfae-81dc-41bc-aa8a-39a9c754ab99.png)
- Check if the Dashboard show you the „kW Ertrag“ (Overload)
![IMG_1223](https://user-images.githubusercontent.com/117570480/212335555-df8fb810-fe42-4c09-8f96-18ea3c35f919.png)

4. Use my script for getting the available power for the heatpump and sync the values to the heatpump

![424dd4adbc97b4dd986d3d1154b85286f51745b5](https://user-images.githubusercontent.com/117570480/200165911-544808cb-e029-49ff-b217-e350f3b16f56.jpeg)
