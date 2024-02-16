# Bluetooth Low Energy

Bluetooth Low Energy (BLE) radio enables devices to exchange data wirelessly over short ranges. The purpose of the BLE radio is to have a communication link between devices without requiring a cable to be connected between the devices. It should also be mentioned that BLE can be used for location tracking of assets and people.

A concrete example of an BLE use case is an BLE enabled thermostat. By adding BLE radio to the thermostat it becomes possible to setup the configuration from a smartphone app. This simplifies the setup process such as setting a schedule for different temperatures for different times of the day. The smartphone will provide the user interface and the thermostat itself will be simplified without any need for buttons or display.

BLE have become an generally accepted standard and is widely supported by many hardware developers. Billions of BLE devices have been manufactured and shipped . This means that BLE comes built in a wide variety of devices, smartphones, computers, cars, wearables, medical devices, speakers, and even coffee mugs.

## BLE Protocol Stack

## Physical Layer

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
