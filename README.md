# iotlab-pilotcase-stufvenas

## Hardware suggestion

| Product                                                                                                                                                                                                                     | Price    |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------- |
| [Dragino DLOS8N Outdoor LoRaWAN Gateway](https://iot-shop.de/en/shop/dragino-dlos8n-outdoor-lorawan-gateway-5841?category=7&search=LoRaWAN+Gateway#attr=17051,20022,6145,20023,14699)                                       | 249.90 € |
| [IM Buildings People Counter LoRaWAN Infrared](https://iot-shop.de/en/shop/im-buildings-people-counter-lorawan-infrared-4735?search=counter&order=name+asc#attr=23729,1177,20464,21806,18727,18728,18729,21807,21805,14505) | 248.90 € |
| [IM Buildings Outdoor Case for People Counter](https://iot-shop.de/en/shop/imb-ib002-002-00-im-buildings-outdoor-case-for-people-counter-5166?search=counter&order=name+asc#attr=23332)                                     | 192.90 € |

# LoRaWAN Gateway

The gateway we will use in the pilot case is the Dragino DLOS8N Outdoor LoRaWAN Gateway (8 channels). The Gateway is IP65-rated and can be mounted on a pole or wall.
| ![](./assets/lorawan_gateway.png) | [Dragino DLOS8N Outdoor LoRaWAN Gateway](https://iot-shop.de/en/shop/dragino-dlos8n-outdoor-lorawan-gateway-5841?category=7&search=LoRaWAN+Gateway#attr=17051,20022,6145,20023,14699) | 249.90 € |
|-|-|-|

# Getting started
1. Update the firmware on the Dragino DLOS8N Outdoor LoRaWAN Gateway, visit [this guide](https://github.com/iot-lnu/iotlab-pilotcase-hasselo/blob/main/firmware.md)
2. Configure the Dragino DLOS8N Outdoor LoRaWAN Gateway for the Helium network, visit [this guide](https://github.com/iot-lnu/iotlab-pilotcase-hasselo/blob/main/helium.md)

## Sensor configuration
| ![](./assets/IM-Buildings_People_Counter.jpg) | [IM Buildings People Counter LoRaWAN Infrared](https://iot-shop.de/en/shop/im-buildings-people-counter-lorawan-infrared-4735?search=counter&order=name+asc#attr=23729,1177,20464,21806,18727,18728,18729,21807,21805,14505) | 248.90 € |
|-|-|-|
1. Follow the installation in [this video](https://www.youtube.com/watch?v=m08ACak8ySE) to setup the people counter hardware.
2. **If you use Helium Network**, the following steps applies : 
   1. Connect to [the Helium console](https://console.helium-iot.xyz/front/).
![](./assets/heliumConfig/add_device.png)
   2. Add the device to your application by taking it's **DevEUI** (you can get while making the hardware setup) and it's **Join EUI** that you also setup during hardware installation.
![](./assets/heliumConfig/device_config.png)
   3. The **device profile** is up to you but for this case, remember that the sensor is a **Class-A**.

## DataCake configuration
TO DO