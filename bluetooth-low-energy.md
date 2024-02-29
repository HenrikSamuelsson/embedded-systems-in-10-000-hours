# Bluetooth Low Energy

Bluetooth Low Energy (BLE) radio enables devices to exchange data wirelessly over short ranges [(Bluetooth SIG - Tech Overview, n.d.)](references.md#bluetooth-sig---tech-overview-no-date). The purpose of the BLE radio is to have a communication link between devices without requiring a cable to be connected between the devices. It should also be mentioned that BLE can be used for location tracking of assets and people.

A concrete example of an BLE use case is an BLE enabled thermostat. By adding BLE radio to the thermostat it becomes possible to setup the configuration from a smartphone app. This simplifies the setup process such as setting a schedule for different temperatures for different times of the day. The smartphone will provide the user interface and the thermostat itself will be simplified without any need for buttons or display.

BLE have become an generally accepted standard and is widely supported by many hardware developers. Billions of BLE devices have been manufactured and shipped . This means that BLE comes built in a wide variety of devices, smartphones, computers, cars, wearables, medical devices, speakers, and even coffee mugs.

## BLE Protocol Stack

### Physical Layer

The physical layer (PHY) is the lowest bottom layer in the BLE Protocol stack. This layer is about actual physical methods to transmit the information by the use of radio.

The BLE standard defines three different types of PHY radios:

1. LE 1M PHY
2. LE 2M PHY
3. LE Coded PHY

## BLE Device Addresses

A BLE device will have an unique address, represented by in a 48-bit value.

This device address comes in different types and subtypes:

- public
- random
  - static
  - private
    - resolvable
    - non-resolvable

## BLE Beacon

A BLE Beacon is a Bluetooth device that typically only transmit advertising packets. This means that these types of devices are simple and will only handle small amounts of data that fits in the advertisement.

Beacons comes in some different application categories:

- Wireless sensors
  - Temperature
  - Humidity
  - Pressure
  - Motion
  - Etc.
- Payment systems
- Indoor navigation
- Asset tracking

## Central VS Peripheral

Two BLE devices can form a connection, after forming the connection one of the devices will take on a role known as the *peripheral* and the other will take a role known as the *central*.

A peripheral will typically be a battery powered device, can be some type of sensor. The central will typically be a more advanced device, commonly with some type of user interface where. The central can then collect the data from the sensor using BLE as transport medium and present the data to the user.

When planning the design of a BLE system it shall be decided, and documented, what role each device in the system will play.

## Connection Interval

When in connected states the two parts will turn on the radio at regular intervals, to exchange information. In between so will the radio be turned off to save power.
