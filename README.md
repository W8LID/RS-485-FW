# RS-485-FW
An RS-485 FeatherWing for the Adafruit Feather system.

![RS-485-FW-render](https://user-images.githubusercontent.com/28584917/110249045-fd0cac00-7f41-11eb-87d8-e848f4fe3260.png)

The RS-485 FeatherWing provides level shifting of the TTL UART on Adafruit Feather type development boards. This board is based on the Maxim MAX3485 transceiver. It also provides an automatic direction control circuit so as to not require any additional GPIO pins for direction control.

This board is designed with minimal components in mind to keep complexity and cost to a minimum. Component footprints were chosen to allow for hand soldering and no special equipment required for assembly.

Note: The 4.7kΩ bias resistors (R1 & R3) should only be populated on a single device on an RS-485 bus. That is, if attempting to communicate between two RS-485 FeatherWings on the same bus, only populate R1 & R3 on a single FeatherWing.
